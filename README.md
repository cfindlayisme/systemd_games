Oct 5, 2022: I now dockerize everything because I'm too darn lazy. This is no longer updated, but you can probably find start lines in my dockerfiles themselves per game

Systemd files for various games installed into /opt/<gamename>. Put in /etc/systemd/system and run systemctl daemon-reload. 

Then service <gamename> start/stop or systemctl enable <gamename> to start at boot. 

Some options like configuration or world will have to be specified too, and this can be done in the .service file itself.

Terraria scripts taken from a tutorial. I don't have the link saved, but thank you kind stranger!

TODO: Tidier README per service