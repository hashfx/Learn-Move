# Move Langauge for Aptos Blockchain Ecosystem

## Setup Guide
+ Make sure python 3.6+ is installed
+ Run in terminal
    + for Linux/WSL: 
    ```move
    curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3
    ```
    + with wget: 
    ```move
    wget -qO- "https://aptos.dev/scripts/install_cli.py" | python3
    ```
    + for WindowsNT in Powershell: 
    ```move
    iwr "https://aptos.dev/scripts/install_cli.py" -useb | Select-Object -ExpandProperty Content | python3
    ```
    + on MacOS: ```brew install aptos```
    + update Aptos CLI: ```aptos update```


## Initial Setup
Navigate to your project directory and create a new move directory

+ create and change current directory to your dapp: ```cd YOUR_DIR_NAME```
+ create **move** directory: ```mkdir move```
+ select move as current directory: ```cd move```
+ init move: ```aptos move init --name YOUR_DAPP_NAME```
+ This command creates a Move.toml file and a sources/ directory inside the move directory.

## Create move module
+ In <kbd>move</kbd> directory, run: 
```move
aptos init --network devnet
```
+ press <kbd>enter</kbd> when prompted
+ copy the address string in ```account```
+ open the ```Move.toml``` file.
+ add the following code to <kbd>move.toml</kbd>, substituting your actual default profile account address from aptos/config.yaml:
```move
[addresses]
todolist_addr='<default-profile-account-address>'
```
+ Create a new ```.move``` file within the <kbd>sources</kbd> directory and add your **smart contract** code in it

