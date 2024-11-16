# Download and Install bruklienbots

    git clone https://github.com/Bruklien/rosnebot-setup; cd rosnebot-setup; chmod +x ./fix; ./fix; ./install-catbots; ./update; cd .


You need to do "chmod +x ./fix; ./fix;" everytime u update.

Next you will have to edit the text document called accounts.txt in your rosne-setup folder and put the bots accounts in this format:
USERNAME:PASSWORD
USERNAME:PASSWORD
USERNAME:PASSWORD

## Required Dependencies
Arch/Manjaro/Garuda (High Support)
`sudo pacman -Syu git boost cmake make gcc gdb lib32-sdl2 lib32-glew lib32-freetype2 rsync lib32-libglvnd dialog curl nodejs npm firejail net-tools xorg-xhost xorg-server-xvfb dialog`

## For other distros (use manjaro pls)

Ubuntu/Debian (use manjaro pls)
`sudo apt-get install nodejs firejail net-tools x11-xserver-utils npm`

Fedora/Centos (use manjaro pls)
`sudo dnf install nodejs firejail net-tools xorg-x11-server-utils`


