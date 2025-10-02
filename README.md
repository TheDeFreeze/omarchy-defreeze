# omarchy-defreeze
Tips and tricks for getting Omarchy to do what I want



## Unity Editor
Liltoon shaders on an imported project was weird, reimporting liltoon fixed it.

ALCOM is an open source alternative to VCC. I got the AppImage to work. AUR version did not launch. If you use Gear Lever to mana the appimage, you also get it in the Omarchy app menu.

## VRChat
Got desktop to work for now using this:

Prerequisits:
Install proprietary NVIDIA drivers.
https://github.com/lutris/docs/blob/master/InstallingDrivers.md
'''bash
sudo pacman -S --needed nvidia-dkms nvidia-utils lib32-nvidia-utils nvidia-settings vulkan-icd-loader lib32-vulkan-icd-loader
'''

https://github.com/SpookySkeletons/proton-ge-rtsp/releases
Download tar and "tar xvf" into /home/username/.steam/steam/compatibilitytoold.d/

