# apt
apt is a command line utility for installing, updating, removing, and otherwise managin deb packages on linux distribution.

It combines the most frequently used commands the apt-get and apt-cache tools with different default values of some options.


## Updating package index 
The APT package index is a database that holds records of available packages from the repositories enabled in system.
$ sudo apt update


## To upgrade the installed packages to their latest versions run:

$ sudo apt upgrade 
$ sudo apt upgrade package_name

## Full Upgrading

$ sudo apt full-upgrade

Use with caution 


## Installing packages 
sudo apt install package1 package2 

to install deb files provide the full path to file 

## remove package 
sudo apt remove package_name

remove command will uninstall the given packages but it may leave some configureation files behind. 
If you want to remove package with all its associted files use 

sudo apt purge package_name

## remove unused packages 
sudo apt autoremove

## list packages 

sudo apt list

sudo apt list | grep package_name

sudo apt list --installed 

sudo apt list --upgradable

## search 

sudo apt search package_name 

## package information 

sudo apt show package_name




