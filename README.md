# network3-node
Installing Network3.ai Node On Ubuntu.

# SETUP
<br>```sudo apt update && sudo apt upgrade -y && sudo apt install net-tools -y```

# DOWNLOAD & EXTRACT FILE
<br>```cd $HOME```
<br>```wget https://network3.io/ubuntu-node-v2.1.1.tar.gz```
<br>```tar -xzf ubuntu-node-v2.1.1.tar.gz```

# INSTALL
<br>```cd ubuntu-node && sudo bash manager.sh up```
<br>*Open Output on browser with replacing ``xxx.xxx`` to your IP.

# MANAGING
<br>* GET PRIVATE KEY AND BIND ON WEBSITE
<br>```sudo bash manager.sh key```

* START NODE
<br>```sudo bash manager.sh up```

* STOP NODE
<br>```sudo bash manager.sh down```

