<p align="center">
    <a href="https://github.com/MrVivekRajan/Grub-Themes/stargazers"><img src="https://img.shields.io/github/stars/MrVivekRajan/Grub-Themes?colorA=32302f&colorB=8f8452&style=for-the-badge"></a>
     <a href="https://github.com/MrVivekRajan/Grub-Themes/contributors"><img src="https://img.shields.io/github/contributors/MrVivekRajan/Grub-Themes?colorA=32302f&colorB=8651BB&style=for-the-badge"></a>
    <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"><img src="https://img.shields.io/github/issues/MrVivekRajan/Grub-Themes?colorA=32302f&colorB=3B4068&style=for-the-badge"></a>
</p>

 <p align="center"> 
   <a = href="https://www.pling.com/p/2142488/">
            <img src="https://img.shields.io/badge/Pling-Page-red.svg?style=for-the-badge&labelColor=32302f&color=4e0bb5"></a> 
</p>

## :star2: Description
A warm welcome to all the people reading out this 🤗. Here at this repo you will find some Aesthetic, cool, stylish and minimal themes for Grub Boot Menu.

## Currently Supported Themes

<br><div align="center"><table><tr><td><img width="60" src="https://www.shareicon.net/data/2016/02/07/281237_theme_512x512.png"></td><td>

<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/Aesthetic"><img src="https://img.shields.io/badge/Aesthetic-purple.svg?style=for-the-badge&color=8f8452"></a>
<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/Anime"><img src="https://img.shields.io/badge/Anime-yellow.svg?style=for-the-badge&color=d33c2d"></a>
<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/SekiroShadow"><img src="https://img.shields.io/badge/Sekiro-purple.svg?style=for-the-badge&color=3B4068"></a>


<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/CartoonGirl"><img src="https://img.shields.io/badge/CartoonGirl-yellow.svg?style=for-the-badge&color=a953bb"></a>
<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/Doraemon"><img src="https://img.shields.io/badge/Doraemon-orange.svg?style=for-the-badge&color=4575ba"></a>
<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/Windows-Main"><img src="https://img.shields.io/badge/Windows-blue.svg?style=for-the-badge&color=0864C5"></a>

<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/GradientColor"><img src="https://img.shields.io/badge/GradientColor-yellow.svg?style=for-the-badge&color=f25781"></a>
<a href="https://github.com/MrVivekRajan/Grub-Themes/tree/main/NeonPurple"><img src="https://img.shields.io/badge/NeonPurple-yellow.svg?style=for-the-badge&color=4e0bb5"></a>

</td></tr></table></div><br><table><td><br>

# INSTALLATION :-
# For Windows Theme.
(1) Download Windows-Main theme file either by cloning this repository or from release section.

(2) Once downloaded, you will find Windows folder inside it simply copy and paste it to /boot/grub/themes/ directory.

(3) Then edit /etc/default/grub using any text editor or filemanager and add :
GRUB_THEME=/boot/grub/themes/Windows/theme.txt

(4) Then copy paste menu.cfg file present in Windows-Main folder to /boot/grub/

(5) Also copy paste Menu script file present in Windows-Main folder to /etc/grub.d/

(6) Then simply run chmod +x /etc/grub.d/Menu command in terminal

(7) Now simply set env variable using the command :
    sudo grub-editenv - set config_file=menu.cfg 
    
(8) Everything done just simply update grub by :
    sudo update-grub
           or
    sudo grub-mkconfig -o /boot/grub/grub.cfg 

# For other themes
(1) Download your favourite theme either by cloning this repository or from release section.

(2) Copy the downloaded theme folder to /boot/grub/themes/ directory.

(3) Then edit  /etc/default/grub using any text editor or filemanager.

(4) And add : 
    GRUB_THEME=/boot/grub/themes/(theme-name)/theme.txt
            don't forget to replace (theme-name) with your real theme name.
 
(5) Update grub by:  
    sudo update-grub
           or
    sudo grub-mkconfig -o /boot/grub/grub.cfg 

# Preview
WINDOWS
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/15e67497-8c77-4a6d-8294-15fb534465fb" align="center" width="750"> </p>
NEON - PURPLE
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/7e042c85-2aad-4952-96ae-173b495d8479" align="center" width="750"> </p>
SEKIRO - SHADOW
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/cfcd94fb-6de2-4971-8ffd-e2abdb75a817" align="center" width="750"> </p>
DORAEMON
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/23566a60-906a-4695-9bf8-0cee056f97b5" align="center" width="750"> </p>
CARTOON - GIRL
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/e4974df4-eaa0-4269-95e1-12ac41dab685" align="center" width="750"> </p>
ANIME
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/9f9d0732-ad3e-4bd6-a40c-da0dacf6ee55" align="center" width="750"> </p>
GRADIENT - COLOR
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/ddf0d599-e3f7-4110-984d-99e01dfdd9c2" align="center" width="750"> </p>
AESTHETIC
<p align="center"> <img src="https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/078eff71-2120-4c27-84d3-8cd4d32d6fbb"> </p>


# Video - Preview
https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/96cbe251-077f-449f-b1b7-a3c1e6c49662

# Thanks for Visiting !! ❤️❤️
I Hope You Like my project, if yes then don't forget to give it a star as it means a lot.


<h4> <span>· </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"> Request Feature </a> </h4>
