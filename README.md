Peak is the package manager of K2-linux, it's source based and extremely lightweight weighing only 3 KiB.
It automates the building process cloning the repo with curl and building it. To download something you type in the terminal sudo/doas peak -S grub and it will compile the grub package on your system.
You can build a local PEAKBUILD and install it on your system with sudo/doas peak -B and the package and install it on your system
