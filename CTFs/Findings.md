*CRONJOBS 
Discovered that it is possible to elevate privileges on a kali machine by overwriting a cronjob task. for example if a user called John running a txt file say every 30 minutes, an attacker can overwrite that task to say open a reverse shell.

NOTE: After generating an ssh key always rename the public key to authorized keys before copying it to the target ssh account!!
