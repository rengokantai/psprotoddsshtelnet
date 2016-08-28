#### psprotoddsshtelnet
######2 Terms.
OSI 7 layers.  
Appli, repres, session,transfer-> Host layers  
Network, data,phy -> media layers
######4 OpenSSH
```
/etc/ssh/ssh_config  #control client behavior
/etc/ssh/sshd_config #control server behavior
```
hide paraphrase: in local machine
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa #enter paraphrase
```
######4 Debugging tool
```
ssh -v
```
check log
```
cat /var/log/auth.log | grep sshd
```
bind ssh to another port
```
sudo /usr/sbin/sshd -d -p 2020
```
