# linux-newbies
linux guide for newbies 
I recommend to read this in a pc or laptop for better understanding and for a better alignment of texts.
I prefer linux mint os over others since :---

i) It is user friendly
ii) lightweight distro
iii) Can run in a low end laptops 
iv) Huge community to trouble shoot our problems 
v) Simple to use 
vi) It can run in a 10 year old laptops.

Here is a download Link for Mint :---

There are three editions available namely

i)Cinnamon ( for colorful desktop and highly customizable )
ii)Mate    ( It is simple , fast , Stable )
iii)Xfce   (light weight, for low end pc or laptops ,speed )

links for mint os  :----   https://linuxmint.com/download.php 

Here I provide necessary instructions and links for your linux mint os  after the installion process 

1) Enable firewall ( for network security )
   
    go to search tab and find firewall applications ,once you found 
     enable this 
     
     i) incoming   : deny
     
     ii) outgoing  : allow 

2) flameshot ( Highly customizable and powerful screenshot tool )

    go to linux terminal ( using search tab, search for terminal once you found launch that terminal )
    steps to be followed :----- ( go to terminal and copy paste the below code )
    i) sudo apt install flameshot
    
    ii) sudo apt update
    
    
3) Install kdeconnect ( for file transfer between pc and phone )
          
      go to linux terminal 
      steps to be followed 
      i) sudo apt install kdeconnect  
       or directly install from software manager 
       or install using the link  https://community.linuxmint.com/software/view/kdeconnect
       
      ii) once you installed  kdeconnect in laptop or pc then install kdeconnect in android phone 
               just simple go to playstore and search for kdeconnect and install it 
               
      iii) connect your phone with laptop using kde connect steps to be followed 
               i) open kde connect simultaneously  in phone and pc 
               
               ii) make sure both connected  to same wifi 
               
               iii) once connected to same wifi network  your phone then displays your pc name just simply click and connect that's it .
             
 4) install libre office ( an free alternative to ms office )
 
     i) simply install it in software manager 
     
     ii) by using linux terminal 
              sudo add-apt-repository ppa:libreoffice/ppa
              sudo apt update
              sudo apt upgrade
              
     for  more info :--   https://libre-software.net/how-to-install-libreoffice-on-ubuntu-linux-mint/ 
     
     iii) download directly using the link :----   https://community.linuxmint.com/software/view/libreoffice
     
     
  5) brightness controller ( some laptops or pc do not able to adjust the brightness  in mint os so here is a solution )
  
      open terminal and run the following code 
      
      i) sudo add-apt-repository ppa:apandada1/brightness-controller
      
      ii) sudo apt-get update
      
      iii) sudo apt-get install brightness-controller
    
 6) sound volume issue :---------------------------------------------------
 
    one of the main issue I have faced after installing mint is that ,whenever I played a video  or audio  there will be no sound and hence forth after day and night of research and online videos I didn't found a solution . But somehow I found an indirect solution  and this solution works like  a charm . 
    Instructions to be followed :-------
    
    i) go to search tab and search for keyboard shortcuts 
    
    ii)keyboard shortcuts --> application shortcut then 
    
    iii)Then you will  see a customizable keyboard shortcuts in that click ---> add
    
    iv)A command tab will appear in that just copy paste a  code given below 
    (**********an important point to be noted is that before entering the code just go to terminal and type alsamixer and click enter, it shows the graphical                          representation of the system sounds  in that  see whether headphone  is set to 100 if it is not set just follow the below code ***************)
    
    v) amixer sset Headphone playback 100%+  
    
    vi) and set a shortcut key for that (eg : f4,f5 ) that's it .
    
    vii) once you find the video or audio volume is muted, just click the shortcut key you have customized  and that's it .
    
  7) customizing shortcuts for easy volume control  :-------
  
    if you wanna control the volume (high,down,mute) in just a click then this shortcut code is for you 
    
    i) go to search tab and search for keyboard shortcuts 
    ii)keyboard shortcuts --> application shortcut then 
    iii)Then you will  see a customizable keyboard shortcuts in that click ---> add
    iv)A command tab will appear in that just copy paste a  code given below  and press any key to access the shortcut (f1,f2,f3) 
         1) to increase the volume :-------
               amixer sset Master playback 10%+  
               (****here 10%+ is my choice it can also be 10,20,31, any number but < 100 *****)
                and customize a shortcut key of your choice ,  say f1  
         2) to decrease the volume  :--------
                amixer sset Master playback 10%-
                customize a shortcut key of your choice ,  say f2 
         3) to mute all volumes     :---------
                 amixer sset Master playback 100%-
                  customize a shortcut key of your choice ,  say f3 
                  
                  and that's it so now 1) if you wanna increase the volume --------> press f1
                                       2)  if you wanna decrease the  volume ---------> press f2
                                       3) if you wanna mute all volumes --------> press f3
                  
                  
               
    
                                                  :-)        :-)       :-)        
    


---------------------------------------------------------------------Thank You ----------------------------------------------------------------------------------------
------------------------------------------------------There are many tips , tricks , softwares I will update shortly --------------------------------------------------




