# Test 01

Create a bash script that sets up the following system properties on Ubuntu 18.04 server:
* Time zone
* Locale
* Move sshd to listen port 2498 instead of 22
* Deny remote login as `root` user
* Create the `serviceuser` account to system
* Limit `serviceuser` sudo rights to start|stop|restart services (without adding `serviceuser` in groups wheel/sudo)
* Deploy Nginx server and make it autostart on reboot
* Deploy Monit server and make it autostart on reboot
* Set Nginx to proxy requests to the Monit server with the basic auth using `monit`/`tinom` credentials.
