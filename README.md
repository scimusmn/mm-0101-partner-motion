# Math Moves - 0101 - Partner Motion

## Install instructions

This project does not require any files from this Git repository. This README.md is the only file here!


With a little setup, you can install this application using the private SMM Boxen repo. This requires an internal SMM account.
First, install the basic boxen repo, using our [Boxen setup script](https://github.com/scimusmn/boxen-setup). 
Once the Boxen script has run through without errors, move on to setting up AWS access below.

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
