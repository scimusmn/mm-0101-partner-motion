# Math Moves - 0101 - Partner Motion

## Install instructions

Manually set the Exhibits user to auto log in. Go to System Preferences > Users & Groups > Login Options > Automatic login: "Exhibits"

Before running the Boxen manifest for this project, you must first setup AWS sync access.
Open Terminal and run these commands:

    sudo easy_install pip
    sudo pip install awscli
    aws configure
    
Next you will be asked for two keys. Log in to LastPass and copy the keys found under "Amazon key - smm-machines". 
For region name, enter ```us-west-2```.
For output format, enter ```JSON```.

You can install this application using the private SMM Boxen repo. This requires an internal SMM account.
First, install the basic boxen repo, using our [Boxen setup script](https://github.com/scimusmn/boxen-setup). 
Once the Boxen script has run through without errors, you can run the custom Partner Motion install.

    boxen mm_0101_partner_motion
    

Note this project does not require any files from this Git repository. This README.md is the only file here.


# Run the application
The application should start correctly after rebooting the computer.
