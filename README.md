# Flutter

A new Flutter project.
I am going to attempt to make a GitHub
mobile application

# Setup

1. Install Flutter SDK: https://flutter.dev
    - Extract in desired location /home or /development
    - tar xf ~/Downloads/flutter_linux_v1.12.13+hotfix.5-stable.tar.xz
Or

git clone https://github.com/flutter/flutter.git

2. Add Flutter To Path
    - Linux: vim .bashrc
    - export PATH="$PATH:/home/jasonanrico/development/flutter/bin"
    - source ~/.bashrc 
    - echo $PATH
    - which flutter
    - flutter precache
    - flutter doctor

3. Install Android Studio
    - Install Plugins
    - Install Emulator:
        - Tools/AVD Manager
        - Create Virtual Device
    - After Step 4:
        - Run Emulator
        - Debug
        


4. Changing KVM Group
    - sudo apt install qemu-kvm
    - ls -al /dev/kvm
    - grep kvm /etc/group
    - sudo adduser $USER kvm
    - kvm:x:128:username
