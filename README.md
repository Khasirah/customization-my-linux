# config my bspwm and polybar

i use **ubuntu 22.04**

1. go to [switching-to-ubuntu](https://christitus.com/switching-to-ubuntu/) follow the tutorial except **installing your dekstop** and go to [ubuntu-titus](https://github.com/christitustech/ubuntu-titus/) and follow the instruction
2. when the installation finish, you will restart the pc and than login as usual, after that you asked about wallpaper, just accept it so the wallpeper will set by the app
3. [polybar-theme](https://github.com/adi1090x/polybar-themes) follow the **installation** part, then follow **launch the bar** part
4. to make polybar start automatically with **bspwm**, do `vim ~/.config/bspwm/bspwmrc` search for "#Start polybar first" and change to `bash ~/.config/polybar/launch.sh --shades` *--shades* can be replaced with other theme of **polybar-themes**
5. just copy my backup to `.config/{app}` according to name of folder and restart the pc
