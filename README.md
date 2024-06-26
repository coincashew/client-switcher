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

### Installation Screen:
Select the Ethereum network, client to delete, client to install, then click "Install".

![Screenshot from 2024-01-23 11-35-14](https://github.com/accidental-green/client-switcher/assets/72235883/f26e0138-06ea-4894-a595-b11245cb54ea)

The script will delete all old client data, install the new client, and create service files, usernames, directories etc

### Sucessful Install Screen:
![Screenshot from 2024-01-23 21-51-08](https://github.com/accidental-green/client-switcher/assets/72235883/f121a02e-74ae-4538-8017-d1e2c996b678)


Once installation has finished, you can start the new client and begin syncing.

**NOTE:** This code only changes the execution client and does not affect the beacon, validator, mev, or keystores.

This project has not been audited yet, but working to make that happen soon.

**Other Ethereum related repos:**

[Validator Install](https://github.com/accidental-green/validator-install): Fresh Ubunutu to syncing validator in minutes

[Validator Updater](https://github.com/accidental-green/validator-updater): Instantly update clients (Execution, Consensus, and Mevboost)

[Validator Controller](https://github.com/accidental-green/validator-controller)
: Easily control the validator with a single click (start, stop, journals, service files)
