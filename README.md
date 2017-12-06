# Pre-requisites
- SELinux is Disabled (it is in DigitalOcean by default)
- A CentOS 7 droplet (of any size)

# Step 1: Get/Clone (if you have git) the script found in my GitHub Repository
wget https://raw.githubusercontent.com/cameronbackus/doPBX/master/install_freepbx.sh

# Step 2: Run the Script
sh install_freepbx.sh

The Script will run for a bit more, you then will be able to choose if you would like any more Asterisk modules to be installed.

The script will then finish and you can browse to the FreePBX WebGUI using the droplet IP address.
