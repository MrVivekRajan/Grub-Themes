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

# Minimal
![Minimal](https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/7fab7ba5-9008-4283-8b27-428b7168405c)

# Cool - Aesthetic - Stylish
![cool](https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/85dc9a2d-42a7-4ad3-9f71-c2a0ee57669c)

# WINDOWS - Preview
https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/92712653-e448-4ad5-a4c3-56401d786e7b


# Thanks for Visiting !! ❤️❤️
I Hope You Like my project, if yes then don't forget to give it a star as it means a lot.


<h4> <span>· </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"> Request Feature </a> </h4>
