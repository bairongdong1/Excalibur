ssh part
first check your ip and bind
also make sure you have changed the ip in bh_sshRcmd.py
```
sudo python bh_sshserver.py 172.27.35.5 22
```

then use another terminal 
```
python bh_sshRcmd.py
``` 
then type some thing like `ls` in the server therminal.

