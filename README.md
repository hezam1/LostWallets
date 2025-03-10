# LostWallets

![wallet.dat](https://user-images.githubusercontent.com/82582647/190867530-275ae6ad-eb78-43f1-9600-f5628739ed05.png)</br>

- [**wallet.dat (273) - Addresses Table**](https://github.com/phrutis/LostWallets/blob/main/Others/wallet.dat-addresses.md)
- [**wallet.dat (273) - HASHES Table**](https://github.com/phrutis/LostWallets/blob/main/Others/hashes.md)
- [**wallet.dat - Password Hints**](https://github.com/phrutis/LostWallets/blob/main/Others/Hints.txt)
- [**Fake wallet.dat**](https://github.com/phrutis/LostWallets/tree/main/fake-wallets)</br>
- [**Frequently asked Questions**](https://github.com/phrutis/LostWallets#frequently-asked-questions)

You can search by [**YOURSELF**](https://github.com/phrutis/LostWallets/blob/main/Others/alonene.md) if you find the password you will get 50%</br>
Or you can take part in a collective search<hr>

# Collective search
![diagram](https://user-images.githubusercontent.com/82582647/192157161-e88a1475-b909-4b58-beb4-c9214052cbfd.png)

## How it works:
```mermaid
flowchart LR

A[МАКСИМ-114] -->|Voucher| T(Connecting)
F[It's me-118] -->|Voucher| H(Connecting)
G[ie696-125] -->|Voucher| U(Connecting)
J[cpto_node-127] -->|Voucher| M(Connecting)
AA[Ervings-082] -->|Voucher| TT(Connecting)
FF[RY-214] -->|Voucher| HH(Connecting)
GG[K-Fed-219] -->|Voucher| UU(Connecting)
JJ[First Last-029] -->|Voucher| MM(Connecting)
AAA[N/A-105] -->|Voucher| TTT(Connecting)
FFF[Leonid-231] -->|Voucher| HHH(Connecting)
T[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
H[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
U[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
M[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
TT[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
HH[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
UU[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
MM[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
TTT[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
HHH[Connecting to your agent] <-->|Task| C{Server http://walletdatuss.work}
C -->|FOUND| D(Balance 12600 BTC)
D -->|70%| Y[8820 BTC Hunters:]
D -->|25%| E[3150 BTC Partner wallet.dat]
D -->|5%| X[630 BTC Organizers]
Y -->|27,3%| W[2407,8 BTC МАКСИМ-114]
Y -->|22,5%| Z[1984,5 BTC It's me-118]
Y -->|12,2%| P[1076,04 BTC ie696-125]
Y -->|11,9%| S[1049,5 BTC cpto_node-127]
Y -->|6,7%| WW[590,9 BTC Ervings-082]
Y -->|4,9%| ZZ[432,1 BTC RY-214]
Y -->|4,6%| PP[405,7 BTC K-Fed-219]
Y -->|3%| SS[264,6 BTC First Last-029]
Y -->|2,8%| WWW[246,9 BTC N/A-105]
Y -->|2,6%| ZZZ[229,3 BTC Leonid-231]

```
If you have a GPU and are willing to search 24/7. If not, you can rent it at [**vast.ai**](https://vast.ai/console/create/)</br>
Join telegram group [**LostWallets**](https://t.me/+bi0ifA-TRYQxODQy)

Hunters [**Table and diagram**](https://docs.google.com/spreadsheets/d/1SLxe01AsnJYXwecu0CcCTnAku8q_2dhnWWmuXDhr3rI/edit#gid=821323231)

Server hashtopolis [walletdatuss.work](http://walletdatuss.work/)</br>

Work task and statistics:</br>
Login: ```hunter```</br>
Password: ```demo```</br>

## Connecting a GPU card from [**vast.ai**](https://vast.ai/console/create/)

Step by Step [Instruction](https://github.com/phrutis/LostWallets/blob/main/Others/manual%20hashtopolis%20vast.pdf)

```
xasser/hashtopolis_agent_vastai:latest

cd htpclient
python3 hashtopolis.zip --url http://walletdatuss.work/api/server.php --voucher start
```
:warning: After connecting, find your agent at the end of the [**list of agents**](http://walletdatuss.work/agents.php)</br>
📢 Write your empty BTC address and agent number to the group [**LostWallets**](https://t.me/+bi0ifA-TRYQxODQy)</br>
 :white_check_mark: **Your agent will be assigned a nickname and the address will be added to the [**table**](https://docs.google.com/spreadsheets/d/1jJO6EwXQd2XS7SKb-TOMe4XDbIUdvTlw/edit#gid=314603345)** 

## Windows 
Download [Python](https://www.python.org/downloads/)</br>
When installing the program, check the patch in Windows</br>
![python path](https://user-images.githubusercontent.com/82582647/192131730-b6eac098-6581-4bbf-99f9-2c06cb929422.png)</br>
We press Start, we write ```cmd```, we press the left key and drag it to the desktop.</br>
We launch the cmd shortcut on the desktop, a window opens.</br>

We enter the commands:</br>
```py -m pip install --upgrade pip```</br>

```py -m pip install requests```</br>

```py -m pip install psutil```</br>

Download agent [hashtopolis.zip](http://walletdatuss.work/agents.php?download=1)

Create a CAT folder, copy hashtopolis.zip into it</br>
Go to the CAT folder, right-click on the folder, properties.</br>
Copy the path to the archive example: C:\Users\User\Downloads\CAT</br>
In the console window, enter the command:</br>
```cd C:\Users\User\Downloads\CAT```</br>

```py .\hashtopolis.zip```</br>
Please enter the url to the API of your Hashtopolis installation:</br>
```http://walletdatuss.work/api/server.php```</br>
No token found! Please enter a voucher to register your agent:</br>
```start```</br>
Successfully registered!</br>
Collecting agent data...</br>
Login successful!</br>
Hashtopolis Server version: 0.12.0 ()</br>
...

:warning: After connecting, find your agent at the end of the [**list of agents**](http://walletdatuss.work/agents.php)</br>
📢 Write your empty BTC address and agent number to the group [**LostWallets**](https://t.me/+bi0ifA-TRYQxODQy)</br>
 :white_check_mark: **Your agent will be assigned a nickname and the address will be added to the [**table**](https://docs.google.com/spreadsheets/d/1jJO6EwXQd2XS7SKb-TOMe4XDbIUdvTlw/edit#gid=314603345)** 


Continue after stop:</br>
```cd C:\Users\User\Downloads\CAT```</br>

```py .\hashtopolis.zip```</br>
![windows-countinue](https://user-images.githubusercontent.com/82582647/192131420-131554a9-2565-43ad-8f12-e6426eb33c92.png)

## Linux

```
sudo apt update
sudo apt-get update
sudo apt install git
sudo apt -y install nvidia-opencl-dev
sudo apt-get install python3-pip
python3 -m pip install psutil
pip3 install requests
wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-ubuntu2004.pin
sudo mv cuda-ubuntu2004.pin /etc/apt/preferences.d/cuda-repository-pin-600
wget https://developer.download.nvidia.com/compute/cuda/11.7.0/local_installers/cuda-repo-ubuntu2004-11-7-local_11.7.0-515.43.04-1_amd64.deb
sudo dpkg -i cuda-repo-ubuntu2004-11-7-local_11.7.0-515.43.04-1_amd64.deb
sudo cp /var/cuda-repo-ubuntu2004-11-7-local/cuda-*-keyring.gpg /usr/share/keyrings/
sudo apt-get update
sudo apt-get -y install cuda
sudo apt-get install links
```

Download agent [hashtopolis.zip](http://walletdatuss.work/agents.php?download=1)

```py hashtopolis.zip```</br>
Please enter the url to the API of your Hashtopolis installation:</br>
```http://walletdatuss.work/api/server.php```</br>
No token found! Please enter a voucher to register your agent:</br>
```start```</br>
Successfully registered!</br>
Collecting agent data...</br>
Login successful!</br>
Hashtopolis Server version: 0.12.0 ()</br>
...

:warning: After connecting, find your agent at the end of the [**list of agents**](http://walletdatuss.work/agents.php)</br>
📢 Write your empty BTC address and agent number to the group [**LostWallets**](https://t.me/+bi0ifA-TRYQxODQy)</br>
 :white_check_mark: **Your agent will be assigned a nickname and the address will be added to the [**table**](https://docs.google.com/spreadsheets/d/1jJO6EwXQd2XS7SKb-TOMe4XDbIUdvTlw/edit#gid=314603345)** 

Continue after stop:</br>
```cd C:\Users\User\Downloads\CAT```</br>

```py .\hashtopolis.zip```

## The advantage of collective search:
You will not go through combinations that have already been completed.</br>
Many lone hunters very often make mistakes.</br>
The server controls all ranges and issues new ones.</br>
You do not need to select the correct masks, hashes and more.</br>
If the password is found, all participants will win and receive coins.

## The terms of participation:
25% - Received by the partner (whose hash is in the table)</br>
 5% - Organizers</br>
70% - is divided among all participants in % of ranges covered.</br>

For example, you searched for 3 days and stopped.</br>
The password was picked up in 3-6 months from a wallet of 500 BTC.</br>
The sum of 70% of the find of 350 BTC is divided by the number of combinations passed.</br>
You will be paid % for your completed segment.</br>
The more combinations you have completed, the higher your %</br>
Make sure your address is in the [**table**](https://docs.google.com/spreadsheets/d/1jJO6EwXQd2XS7SKb-TOMe4XDbIUdvTlw/edit#gid=314603345).</br>
In a collective search, everyone wins.</br>
Enough coins for everyone
<hr>


## Frequently asked Questions

**I have frozen the process on the benchmark. What to do?**

You need to download and install the old version of nvidia driver:</br>
For Linux [455.23](https://ru.download.nvidia.com/XFree86/Linux-x86_64/455.23.04/NVIDIA-Linux-x86_64-455.23.04.run)</br>
For Windows x64 [456.38](https://ru.download.nvidia.com/Windows/456.38/456.38-desktop-win10-64bit-international-dch-whql.exe)<hr>

**I am a miner and I want to search anonymously!**

Connect your rigs to the server.</br>
Write in telegram ```phrutis``` your empty BTC address and the numbers of your agents on the list.</br>
An anonymous nickname will be created with your BTC addresses.</br>
If the password is found, your % will be paid to your address<hr>

**What guarantees that I will be paid when the password is found?**

If you need guarantees look for yourself [**here**](https://github.com/phrutis/LostWallets/blob/main/Others/alonene.md), you will find 50% of yours guaranteed.</br>
In a collective search, there is no way to guarantee that the participants are trustworthy.</br>
If you know a way to guarantee it, let the group know about it and we'll discuss it.</br>
I understand and appreciate the hunters who invest their money and GPU resources for our common victory.</br>
In a collective search, it makes no logical sense to deceive the hunters.</br>
There are many wallets, large sums, enough coins for everyone.<hr>

**Are your wallets real?**</br>

99% - YES</br>
Wallets were maximally checked for validity.</br>
Coins were sent to some dubious wallets for verification.</br>
There is no way to verify wallet.dat is 100%</br>
This can only be done if the correct password is entered.<hr>

**How do you have so many wallets?**</br>

Jacks were presented to me by various hunters for 25% of the amount of the find.</br>
Hunters received wallet.dat by exchanging with other hunters.<hr>

**I have an old wallet.dat (not from a table) want 25%**</br>

You can contact me in telegram ```phrutis```</br>
Provide me with the old wallet.dat</br>
After verification, it will be added to the table with your btc address.</br>
If hunters find password you will get 25%<hr>

**I have a wallet.dat with the same hex, there is a different amount, it's empty, it's a fake?**</br>

You may have an older version of wallet.dat</br>
There is a newer one in the challenge.</br>
In a later version, the user could add a new address and receive coins on it.</br>
The old version of wallet.dat does not have this address.</br>
Or vice versa.<hr>


**Sell me all your wallets**</br>

I don't sell or buy wallet.dat</br>
And I do not advise you to buy.

