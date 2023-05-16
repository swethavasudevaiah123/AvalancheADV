# AvalancheAdv

This code provides a brief understanding about the game that we created using own Avalanche subnet.

## Description

 This program is the code of the game in which we can do many functionalities like minting, burning, transferring, checking the balance of and also attack function in the game using our own subnet and token that we did using Avalanche CLI
 
 ## Running the code
 
 You can either download the solidity file or copy and paste it in remix.
 
To create your own Avalanche subnet , you need to install Avalanche CLI 

To download a binary for the latest release, run:

```shell

curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s

```

Adding Avalanche-CLI to Your PATH

```shell
export PATH=~/bin:$PATH
```

To create a subnet, we run :

```shell
avalanche subnet create mySubnet
```

## Configuration

$ avalanche subnet create mySubnet


Attempted to check if a new version is available, but couldn't find the currently running version information


Make sure to follow official instructions, or automatic updates won't be available for you


-✔ Subnet-EVM


creating subnet mySubnet


-Enter your subnet's ChainId. It can be any positive integer.


ChainId: 12345567
-Select a symbol for your subnet's native token


Token symbol: MYSUBNET


✔ Use latest version


✔ Low disk use    / Low Throughput    1.5 mil gas/s (C-Chain's setting)


✔ Airdrop 1 million tokens to the default address (do not use in production)


✔ No

Then to deploy, we can run :

```shell
avalanche subnet deploy mySubnet
```

After this you need to add the network to your metamask by entering the new RPC URL, chain ID, network name and token symbol .

Then, you need to import the account using the private key provided while deploying the subnet.

In remix, we have to change the environment to injected provider-metamask and add the account that we imported.
 
 ## Authors
 
 Swetha V
 
 @shwetharajiv@gmail.com
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
