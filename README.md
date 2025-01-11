# Slock fork

This fork is for my personal use, adding a few patch and other minor config

# Config

Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

After config you need to compile the program

# Install 

Require Xlib headers files

install cmd
`make clean install`

sometimes slock wont run because need this aditional step
`sudo groupadd nogroup`

# Running slock

Simply invoke the 'slock' command. To get out of it, enter your password.
