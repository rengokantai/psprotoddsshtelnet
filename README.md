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
