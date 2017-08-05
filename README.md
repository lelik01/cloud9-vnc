Cloud9VNC2
===

Running X11 in a Cloud9 IDE

![Screenshot](screenshot2.png)

Fluxbox replaced with icewm,
resolution 1280x864 replaced by 1024x768

Installation
------------


Clone the repository to where you'd like (in the example I use the home folder ~)
    
    
    cd ~
    git clone https://github.com/lelik01/cloud9vnc2.git
    

Enter the repository sub-directory

    cd cloud9vnc2/

Now make sure apt-get has been updated with 

    sudo apt-get update

Run the install script with privileges

    sudo ./install.sh
    
Clean up installation directory
    
    rm -rf ./

Uninstallation
--------------

Run the uninstallation script with privileges

        sudo /opt/c9vnc/uninstall.sh
    

Running
-------

Use the custom C9 runner

    Run > Run With > C9vnc
    
Run the start script symlinked into your /usr/local/bin
    
    
    c9vnc
    
    Usage: c9vnc <args>
       -h          Print this message
       -f          Run in the foreground
       -k          Kill running daemon
    No arguments will try to start daemon process
    
