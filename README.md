# PIIP

this file allowes you to get a notification on your smartphone with the IP address of your Rasbery PI 


This file is a modified version of 
oliverscheer/send-email-with-device-ip-address

it has been modified for use with IFTT's webhooks 

it can also be used for fireing any other IFTT event upon startup (just name the event the same name) 

to use, start by downloading on your pi and placing it in a folder, coppy the file path of the folder 


for it to run on startup: 

open rc. local using 
    sudo nano /etc/rc.local 

then add the following code 

  (sleep 30; python PATH-OF-PROGRAM-HERE)&

