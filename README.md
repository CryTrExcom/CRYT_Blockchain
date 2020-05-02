----
# Welcome to CRYT BLOCKCHAIN! #

----
## What is CRYT? ##
CRYT is a Blockchain ecosystem to make the world a better place.

----
## Run it! ##

  - Download this Repository and extract or `git clone https://github.com/CryTrExcom/CRYT_Blockchain.git`.
  - Go to CRYT_Blockchain Folder.
  - Run with sh ./run.sh (Linux) or run.bat (Windows).

  - wait for the JavaFX wallet window to open.
  - on platforms without JavaFX, open http://localhost:11112/ in a browser.

----
## Blockchain SnapShot 2 May 2020 v 1.30.10! ##

  - Download a copy of Blockchain, extract to CRYT_Blockchain (linux) C:\Users\YOURNAME\AppData\Roaming\CRYTREXCOIN (windows) 
  `https://crytrex.com/cryt_db.zip`.
----

## CRYT_Blockchain on Android Device! ##

  - Now is possible to run the CRYT_Blockchain on Android Device following this tutorial. HELP THE NETWORK TO GROW!
  - Setting up Node on Android take around 15 minutes following these steps.

  - 1) Install UserLAnd from Google Play, Open and Install Ubuntu - https://play.google.com/store/apps/details?id=tech.ula
  - 2) On Console run these commands to setup:
  - `sudo apt-get update`
  - `sudo apt-get install build-essential`
  - `sudo apt-get install git`
  - `sudo apt-get install default-jdk`
  - `sudo apt-get install wget`
  - `sudo apt-get install zip`
  - `git clone https://github.com/CryTrExcom/CRYT_Blockchain.git`
  - `cd CRYT_Blockchain`
  - `sh ./compile.sh`
  - 3) Download a snapshot of CRYT_Blockchain @ block 1178380
  - `wget https://crytrex.com/cryt_db.zip`
  - 4) When download is finished run this command:
  - `unzip cryt_db.zip`
  - 5) Run the Node
  - `sh ./start.sh`

Now can close window of UserLAnd, Kepp active the UserLand Terminal and activate Wake Lock!
DONE!

----
## Troubleshooting the NRS (CRYT Reference Software) ##

  - How to Stop the NRS Server?
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report @ dev@crytrex.com

  - Permissions Denied?
    - no spaces and only latin characters in the path to the CRYT installation directory
    - known jetty issue

----
## Setting up Node and Help Network ##

  - Ubuntu 18:04
    - `sudo apt-get install default-jdk`
    - `git clone https://github.com/CryTrExcom/CRYT_Blockchain.git`
    - `sudo ufw allow 11111`
    - `sudo ufw allow 11112`
    - `cd CRYT_Blockchain`
    - `sh ./compile.sh`
    - `sh ./start.sh`

----
## Further Reading ##

    - Official Website: https://cryt.crytrex.com
    - Click Wiki on Official Website for all Detailed Informations.

----
