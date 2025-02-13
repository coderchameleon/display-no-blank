# display-no-blank
A simple bash script I used to solve a screen blanking issue on Debian machines using X11
I ran into this issue with some Debian (32-bit) machines running IceWM on x11. I could not get screen blanking to be disabled within system configs and that was an issue in this case.
I was able to cobble together this script to solve that problem.
This may not be the "proper" fix but it worked so 😁.
I am basically putting this up here so I have the script saved somewhere than on the machines themselves. 
I am not developing this script and likely will just archive this repo straight away.
Maybe it could help someone else with this very specific and annoying issue
# Purpose 
To be run either manually or via a tool like cron to turn off screen blanking on the effected machine until it is rebooted
I *suggest* setting it to be run with cron so there is less manual work invovled.
# Usage
Either copy/paste or clone the repo and copy the .sh file and put it wherever. You can then run it such as: 
```./home/user/scripts/noblank.sh```
