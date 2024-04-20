# Aethir Tutorial ( make sure you already have Node Key )

1. Open Terminal

wget https://aethir-checker-client.s3.ap-southeast-1.amazonaws.com/sg/AethirCheckerClient-linux-cli-installer.tar

2. Extract file

tar -xvf AethirCheckerClient-linux-cli-installer.tar

3. Run Program 

 command : ./AethirChecker or using sudo  ./AethirChecker 

4. Create new wallet ( currently we cant import wallet )

aethir wallet create 

5. Backup your public key & private key

6. Open https://app.aethir.com/dashboard and delegate your public key 

7. Check your terminal and write aethir license approve [License ID] or 
use: aethir license approve --all

8. Check if your node working 

aethir license summary

Please input:aethir license summary
Number              Status
1                   Running
0                   Offline
0                   Banned
0                   Pending
1                   Total Delegated

Done :)

