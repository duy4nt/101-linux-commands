# The `nmcli` command

The `nmcli` command is used for managing network connections by controlling the NetworkManager, a daemon that handles networking. 
The command stands for Network Manager Command Line Interface. 

### Installation:

The `nmcli` command is already installed by default on most Linux distros. To check if it is installed on your system type: 

```
nmcli --version
```
If you don't have nmcli installed you can do it by using the package manager:

Ubuntu or Debian:

```
sudo apt install network manager
```
This will install NetworkManageron in your system. 
Now we have to start the network managing service.

```
sudo systemctl start NetworkManager
```

Red Hat-based System(such as Fedora, CentOS, REHL):

```
sudo dnf install NetworkManager
```
This will install NetworkManager in your system.
Now we have to start the network managing service.

```
sudo systemctl start NetworkManager
```

Arch Linux:

```
sudo pacman -S networkmanager
```
This will install NetworkManager in your system.
Now we have to start the network managing service.

```
sudo systemctl start NetworkManager
```

### Examples:


### Syntax: 



### Additional Flags and their Functionalities: