----
# Welcome to CRYT BLOCKCHAIN! #

----
## What is CRYT? ##
CRYT is a Blockchain ecosystem to make the world a better place.

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##

  - Download this Repository and extract or `git clone https://github.com/CryTrExcom/CRYT_Blockchain.git`.
  - Go to CRYT_Blockchain Folder.
  - Compile with sh ./compile.sh (Linux) or win-compile.sh (Windows).
  - Run with sh ./run.sh (Linux) or run.bat (Windows).

  - wait for the JavaFX wallet window to open.
  - on platforms without JavaFX, open http://localhost:11112/ in a browser.

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

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder
    - Official Website: https://crytrex.com
    - Click Wiki on Official Website for all Detailed Informations.

----
