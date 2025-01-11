# Network3-node
* Guide on running Network3 node on Linux
* Network3 has recently raised $5.5M. They have a pre-TGE program with a galxe task (not included here) and a Node program.
* Here are the details on how to install their node on your Linux servers:

# Register
* Signup on **[Dashboard](https://account.network3.ai/register_page?rc=37b588a4)** with email first.
![image](https://github.com/user-attachments/assets/5f2ca6fa-5c90-439f-87cc-5425e35af80a)
* We'll focus on Linux CLI here:

# Run Node
* First check any update is required for your packages:
```
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install curl wget -y
```
* Download the latest node package:
```
wget https://network3.io/ubuntu-node-v2.1.1.tar.gz
```
* Extract files:
```
tar -xf ubuntu-node-v2.1.1.tar.gz
```
* Navigate to the extracted directory:
```
cd ubuntu-node
```
* Run the node:
```
sudo bash manager.sh up
```
* Done! To access your dashboard use below format on your system:
https://account.network3.ai/main?o=xx.xx.xx.xx:8080

* Check your earnings on Dashboard
![image](https://github.com/user-attachments/assets/14de8b04-2bdb-48c3-aa51-90cc107c7c18)

# Add your wallet
* After the points started adding up, a pop-up windows will show up to connect wallet (log out and login again if it didn't). Connect your wallet:
* ![image](https://github.com/user-attachments/assets/f68312ab-63cd-4d03-9552-08f9ef847b30)
* Now click (+) on add node section:
* ![image](https://github.com/user-attachments/assets/53177440-7f31-4297-a493-08044103fc38)
* Retrieve the private key of your node and add it to your profile.
```
sudo bash manager.sh key
```

# Useful commands
* To shutdown node:
```
sudo bash manager.sh down
```


