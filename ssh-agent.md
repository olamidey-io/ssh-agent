## SSH Agent Lab guide

### Step 1: Generate an ssh key pair
* Use this command to generate an ssh key pair - **ssh-keygen -t rsa -b 4096 -C "ibrahimolamide999@gmail.com"**
* Add path to save key and also add the passphrase and the randomart image representing your key loads as shown below
![alt text](images/Capture2.PNG)

### Step 2: Copy your Public key to the remote server
To enable passwordless SSH access, you must copy your public SSH key and add it to your GitHub account.
* Use this command to view your public key - **cat  ~/.ssh/id_rsa.pub** as shown below
![alt text](images/Capture3.PNG)

### Step 3: Add the public key to github
Login to your github - settings - SSH and GPG keys - New SSH key - add title - paste key - click add to save.
![alt text](images/Capture1.PNG)