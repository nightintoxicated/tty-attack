# tty-attack
This is a proof of concept for pts-attacks, it currently works with pts terminal connections.
[New Feature]: disconnect a users terminal session via a hard or soft kill signal (not shown in gif)

Click the gif for a better view!
![](https://github.com/lewisrobson/tty-attack/blob/main/tty-attack.gif)


Q. Am i able to use this?
A. go to your terminal and type: who | awk '{print $2}'
do you see pts/x?
Then you're golden.


standard disclaimer.

This is for educational purposes / testing only.
It has been made in order to demonstrate how a terminal
session can be tampered with and to provide insight
into the inner workings of terminal sessions so that
this can be acknowledged as a security issue that
should be considered, and mitigated against where 
possible, this has been developed in a test lab.

Only use this when and where you are authorized to do so.
I am not responsible for how you use this.



