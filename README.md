# Ethereum Client Switcher

Ethereum client switcher allows validators to easily switch their execution client (Besu, Nethermind, Erigon, Reth, Geth) with a single command!

The code is open source and available for CLI (terminal).

### CLIENT SWITCHER (CLI):

## Install Unstructions:

There are two ways to install.

*1. One-liner: easiest way for beginners*

```bash
sudo /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/coincashew/client-switcher/master/install.sh)"
```

*2. Manual Install:*
Paste the following commands into the terminal:

**Install updates and packages:**

`sudo apt-get update && sudo apt-get install git curl ccze python3-pip python3-tk -y && sudo pip install requests console-menu`

**Clone the client-switcher repo:**

`git clone https://github.com/coincashew/client-switcher.git`

### Run Client Switcher:


**CLI Installation:**

`python3 client-switcher/client_switcher_cli.py`
