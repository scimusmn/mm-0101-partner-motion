# Math Moves - 0101 - Partner Motion

## Install instructions

This project does not require any files from this Git repository. This README.md is the only file here!


If starting with a fresh out-of-box machine, start with the [official exhibit computer setup](http://projects.smm.org/atrium/media/node/280246).  Once base Boxen has successfully been installed, move on to setting up AWS access below.

To setup AWS sync access, open Terminal and run these commands:

    sudo easy_install pip
    sudo pip install awscli
    aws configure
    
You will be asked for two keys. Login to [LastPass](https://lastpass.com/) and copy the keys found under "Amazon key - smm-machines". 
For region name, enter ```us-west-2```.
For output format, enter ```JSON```.


At this point, you should be ready to run the custom Partner Motion install.

    boxen mm_0101_partner_motion
    


# Run the application
The application should start correctly after rebooting the computer.

# Hardware Notes
This is a legacy application that does not run true fullscreen, and unfortunately displays a menu bar. Therefore, the screen being used must either offset 60px via settings, or the cabinet must be built to cover the menu bar with a lip.
