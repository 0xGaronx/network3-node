# network3-node
Installing Network3.ai Node On Ubuntu.

# SETUP
```sudo apt update && sudo apt upgrade -y```
```sudo apt install net-tools -y```

# DOWNLOAD & EXTRACT FILE
```cd $HOME```
```wget https://network3.io/ubuntu-node-v2.1.1.tar.gz```
```tar -xzf ubuntu-node-v2.1.1.tar.gz```

# INSTALL
```cd ubuntu-node && sudo bash manager.sh up```
*Open Output on browser with replacing ``xxx.xxx`` to your IP.

# MANAGING
* GET PRIVATE KEY AND BIND ON WEBSITE
```sudo bash manager.sh key```

* START NODE
```sudo bash manager.sh up```

* STOP NODE
```sudo bash manager.sh down```

