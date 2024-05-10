Another Box64+Wine project for Termux.

Instructions and notes - TBD.

# How to install:

Execute this script inside Termux:

## ```curl -o install https://raw.githubusercontent.com/airidosas252/glibc-wine/main/install.sh  && chmod +x install && ./install```

you need to do ```glibc-wine --install``` too.

# How to run
do ```glibc-wine --start``` to start wine

# Does (app) work?
check box86.org and winehq.org for more information.

# winetricks doesnt work!
you need to manually copy the script to $PREFIX/bin or symlink it.

# Does it include virgl?
It doesnt, you have to manually install and configure virgl(like making a file called 'zink' and making it start virgl zink in $PREFIX/bin)
