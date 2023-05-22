# Wrec (Web Remote Execution Code) 1.0
Web Remote Execution Code

## Description
wrec monitors automatically your webserver log for pre configured patterns
when a specific pattern is found it releases a command on the server
this script creates an html page that can be transfer to any portable device
and be opened with a web browser , from there the user can launch anything remotely
on his server in case needed just by sending a specific pre configured 404 pattern
to the web server running in his server , it works with nginx and apache access.log
This script needs a daemon running to monitor the web server logs witch can be installed
using the config script .

## How to install
* git clone https://github.com/peterpt/wrec.git
* cd wrec && chmod +x wrec-conf
* ./wrec-conf
* wrec-conf -i (To install Daemon)

## all switches
 -i (Install Daemon)
 -u (Uninstall Daemon)
 -a (Add new code to config)
 -c (Read current configuration)
 -f (Edit current configuration)
 -d (Delete configuration files)
 -w (Create personal Webpage with config)
 -h (This Help)
 
 ## Pictures and Videos
 * Switches
 ![alt text](https://i.postimg.cc/Y02cZjNV/switches.png)
 
 * Reading Current Config
 ![alt text](https://i.postimg.cc/8PrwDNyn/reaconfig.png)
 
 * Html Web Creation to Remote activate commands
  ![alt text](https://i.postimg.cc/Bnpm7N7q/htmlremote.png)
  
 * Daemon Log Example file (/usr/local/share/wrec/daemon.log)
  ![alt text](https://i.postimg.cc/Y02PCVsy/daemonlog.png) 
  
  Video
<video src='https://youtu.be/5RqGCfKjPp8' width=180/>



