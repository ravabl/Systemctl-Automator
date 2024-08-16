# Systemctl-Automator  


## About  
A Bash script that automates the execution of the 'systemctl' command on multiple servers with multiple applications on each server  



## Prepare script  

### For the script to work correctly, you need to provide values for the following variables:  

 * #### Username and password  
Note: you can certainly modify the script as you see fit and include username and password   
input as a security measure, so that the script’s operation aligns more closely with security   
requirements. However, since the connection uses the SSH protocol, it is likely that the password  
 of an authenticated user will be cached on the server side, making it unnecessary to enter it every time  
* ##### List of servers    
* ##### List of applications    


### Usage  
The script executes the sudo systemctl command on the server after entering 3 types   of variables in the console:    

1. Variables (or a range of servers using a dash '-') assigned the name of the server.    
2. Variables assigned the name of the systemd unit.    
3. The systemctl command that should be executed on the server.    

