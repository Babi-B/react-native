# react-native
I'm working on UBUNTU 18.04
react-native is a repo i created to keep track of all the mini-projects i make while studying react-native and android app development
The process of react-native installation is no way as easy as react.js setup...OMG
I used https://www.techomoro.com/how-to-install-and-setup-react-native-on-ubuntu-18-04-1-lts-bionic-beaver/ as my instruction guide. This link is for linux os but there's also that for windows
Ok, in the installation of react-native these are some points to remember that MUST be done:
    -make sure the necessary requirements at Android 6.0 (Marshmallow) are checked
    -make sure to CONFIGURE ANDROID_HOME ENVIRONMENT VARIABLE
During the installation process make sure to have a steady,reliable and fast(as fast as possible) internet supply. A slow network may trigger errors...or fustrate you 


Installing react-native is more difficult than I expected. I'm going to journal my experiences here
I used WATCHMAN for installation. The ./configure command does not automatically create a Makefile as it is expected to.
The reason why i just doon't create an empty .txt document manually is because (from what i have read) the Makefile created by ./configure contains info that is to be used for installation.


Okay, now to device a way to create a Makefile. This [--> ./configure did not automatically create a makefile. What should i do <-- ] is the question i dropped on google
    NOTE! Without the Makefile file the 'make' command WILL NOT run
    During my search i discovered some files were also missing. That is, they were not created by default either. They are ./README and some other 4 which i have forgotten. I manually created this is it did not seem to hold any system needed data.
