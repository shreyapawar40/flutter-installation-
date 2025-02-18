# flutter-installation-
DOWNLOAD THE SDK FROM THE FLUTTER WEBSITE 
THEN MOVE IT 
            cd ~/Downloads
            mv flutter_linux_3.29.0-stable.tar.xz /home/it/development/

 Extract the Flutter SDK:
            cd /home/it/development
            tar -xf flutter_linux_3.29.0-stable.tar.xz

Add Flutter to Your PATH:

              nano ~/.bashrc  
              CTRL + O 
              ENTER 
              paste this at the bottom : 
                 export PATH="$PATH:/home/it/development/flutter/bin"
              CTRL + X, then Y, and Enter


Reload the Shell Configuration:

            source ~/.bashrc   # or source ~/.zshrc for Zsh users

           flutter --version 
           flutter doctor 



ANDROID STUDIO 
AFTER THE INSTALLATION OF ANDROID STUDIO  GO TO PLUGINS AND DOWNLOAD DART AND FLUTTER 
THEN GO TO SDK MANAGER
      FROM SDK PLATFORM 
              DOWNLOAD ANDROID 12 
              DOWNLOAD ANDROID 13 
      FROM SDK TOOLS 
              Android SDK Build-Tools
              Android Emulator
              Google Play services
              Intel x86 Emulator Accelerator (HAXM)


