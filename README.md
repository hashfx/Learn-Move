# Move Langauge for Aptos Blockchain Ecosystem

## Setup Guide
+ Make sure python 3.6+ is installed
+ Run in terminal
    + for Linux/WSL: ```curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3```
    + with wget: ```wget -qO- "https://aptos.dev/scripts/install_cli.py" | python3```
    + for WindowsNT in Powershell: ```iwr "https://aptos.dev/scripts/install_cli.py" -useb | Select-Object -ExpandProperty Content | python3```
    + on MacOS: ```brew install aptos```
    + update Aptos CLI: ```aptos update```


## Initial Setup
Navigate to your project directory and create a new move directory

+ create and change current directory to your dapp: ```cd YOUR_DIR_NAME```
+ create **move** directory: ```mkdir move```
+ select move as current directory: ```cd move```
+ init move: ```aptos move init --name YOUR_DAPP_NAME```
+ This command creates a Move.toml file and a sources/ directory inside the move directory.


