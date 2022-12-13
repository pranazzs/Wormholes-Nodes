# Upgrade the process of node 0.10.3
## 1. Conduct the command as follows and upgrade the node.
```
wget -O wormholes_install.sh https://docker.wormholes.com/wormholes_install.sh && sudo bash wormholes_install.sh
```
## 2. When the figure is displayed below, the node has upgraded successfully.
  ![image](https://user-images.githubusercontent.com/35629804/207285796-fdd49d9f-63d2-4de1-9084-0bbf43ebe097.png)
## 3. Conduct the command as follows, check whether the Wormholes container is normally running or not and if it Shows “UP,” which means yes.
```
sudo docker ps -a
```
  ![image](https://user-images.githubusercontent.com/35629804/207286067-c0a97141-540f-4b62-9e68-2c9314f1469e.png)
## 4. Check your Node version
```
curl -X POST -H "Content-Type:application/json" --data '{"jsonrpc":"2.0","method":"eth_version","id":64}' http://127.0.0.1:8545
```
**Successfully Upgrade**

![image](https://user-images.githubusercontent.com/35629804/207287011-e40323ae-9292-4bf7-a07a-ab24b2fab16e.png)
