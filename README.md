# CREA 2.0 SWAP APP

## Download
 - For [Windows](https://github.com/creativechain/swap-app/releases/download/1.0/creaswap-windows-x64-1.0.exe)
 - For [MacOS](https://github.com/creativechain/swap-app/releases/download/1.0/creacwap-osx-1.0.zip)
 - For [Debian/Ubuntu](https://github.com/creativechain/swap-app/releases/download/1.0/creaswap-debian-x64-1.0.deb)
 - for [Other Linux](https://github.com/creativechain/swap-app/releases/download/1.0/creaswap-linux-generic-x64-1.0.tar.gz)

## How to use

1 - Execute the CreaSwap on your computer. On Windows is possible that Windwos Defender block app execution the first time, in this case yous must be click on "More information" button after click on "Run anyway".

2 - For this step is necessary a Crea 2.0 account to receive your creas. If you already have an account, you will need  your @username and your masterkey (not a private key). If you still don't have a account, you can sign up trough CreaSwap using an email. Follow the instructions to complete de sign up.
Fill inputs with your account's @username and masterkey. Click on Login button.

3 - If the login is correctly, the app will load the wallet.dat of **Creativechain Platform**. The load process can take several minutes (0-3 min). Be patient.

4 - When load process ends, the app will show the balance calculated with wallet.dat's information. If you not recognize the balance, don't worry, continue with process. Here you have two options:

  - Click on button "Swap" and the app will show the real balance on snapshot (taken on February 19th, 12:00pm CET).
  - Click on Load wallet.dat to load another wallet.dat (for example, wallet used by Creativecoin-Qt).
  
 5 - If your clicked in Swap button you can see a list of your wallet.dat addresses and his balances on snapshot. If your wallet was encrypted, you must provide the passphrase typying it on password input. This is necessary because the app must sign an message with each private key of each address. This is de unique way to demostrate that the balance belongs you. Clicking on Accept button wiil perform swap, this is a **IRREVERSIBLE PROCESS**. If everything went well you will see the "Swap Performed" message. 
  
## Wallet.dat paths
This is the paths of common wallet.dat files
#### Creativechain Platform
  - Linux: `home/mysuser/.creativechain-platform/bin/wallet.dat
  - MacOS: `home/mysuser/.creativechain-platform/bin/wallet.dat
  - Windows: `C:\Users\myuser\AppData\Roaming\Creativechain\bin\wallet.dat
  

#### Creativecoin QT - creativecoind
  - Linux: `home/mysuser/.creativecoin/wallet.dat
  - MacOS: `home/mysuser/.creativecoin/wallet.dat
  - Windows: `C:\Users\myuser\AppData\Roaming\Creativecoin\wallet.dat
