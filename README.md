# headless-vnc
install and use vnc headless on your server with a simple script

Made by [KM4ACK](https://github.com/km4ack/pi-scripts/blob/master/monitor-check) I only uploaded it here to save it and find it easier

You can create a new alias to start vnc when you need it:

```bash
alias svnc='echo run \"ssh -L 5900:localhost:5900 user@ip\" on your pc in another terminal window before trying to connect via vnc && echo "adress to connect to: 127.0.0.1:5900" && x11vnc -rfbauth /home/user/.x11vnc.pwd -ncache 10'
```
