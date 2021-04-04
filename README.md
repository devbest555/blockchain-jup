----
# Welcome to Jupiter!

----
## What is Jupiter? ##
Jupiter is the base platform needed to run the [Gravity](https://github.com/jupiter-project/gravity) framework for information storage and decentralized application building. Jupiter is built from [Nxt's](https://nxt.org) system based on cryptography and blockchain technology.

----
## Get it! ##

  - *pre-packaged* - `https://github.com/jupiter-project/jupiter/releases` and download the latest release.

  - *dependencies*:
    - *General* - Java 8
    - *Ubuntu* - `apt install openjdk-8-jdk-headless`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`
    - *MacOS* (from Terminal)
      - `brew tap AdoptOpenJDK/openjdk`<br>
      - `brew install --cask adoptopenjdk8`<br>
      - To check, `java -version`

  - *Repository* - `git clone https://github.com/jupiter-project/jupiter/`
  
----
## Run it! ##

  - Click on the Jupiter icon, or start from the command line:
     - Unix: `bash start.sh`
     - Window: `run.bat`

  - Wait for the JavaFX wallet window to open.
  - On platforms without JavaFX, open http://localhost:7876/ in a browser.

----
## Compile it! ##

  - If necessary with: `./compile.sh`.
  - You need jdk-8 as well.

----
## Improve it! ##

  - We love **pull requests**
  - We love issues (resolved ones actually ;-) )
  - In any case, make sure you leave **your ideas** at GitHub
  - Assist others on the issue tracker
  - **Review** existing code and pull requests

----
## Troubleshooting the JRS (Jupiter Reference Software) ##

  - How to Stop the JRS Server?
    - Click on Jupiter Stop icon, or run `bash stop.sh`.
    - Or if started from command line, ctrl+c or close the console window.

  - UI Errors or Stacktraces?
    - Report on Github

  - Permissions Denied?
    - No spaces and only latin characters in the path to the JRS installation directory.
    - Known jetty issue.

----
## Further Reading (WIP)##

  - In this repository: 
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    
----

