
# DRIA NODE FULL GUIDE STEP - BY - STEP

Dria appears to be a decentralized platform, possibly focused on AI-driven data management or research, aiming to enhance transparency and collaboration in a Web3 environment, potentially within the MegaETH ecosystem.

Dria just announced their node run, and you can join in too! Run a node, contribute to their decentralized AI network, and earn $DRIA Points. Check out this repo for a complete, detailed guide to get started






## VPS Setup for Running a Dria Node



 - Get a VPS -- You’ll need a Virtual Private Server (VPS) to run a Dria node. We recommend using Contabo. Select the Cloud VPS 8C plan to meet Dria’s requirements.

 - 8 vCPUs and 16GB RAM are required to run even the basic models efficiently.

Important: Lower CPU counts will result in reduced performance, as systems with fewer CPUs process requests more slowly, especially for models demanding more CPU resources.

These specs are the minimum for running a Dria node. Your experience may vary depending on the specific tasks and workload, so consider higher specs for optimal performance.

![Image](https://github.com/user-attachments/assets/77662175-adc8-4bc8-9e40-7035906c5bc1)


## SYSTEM REQUIREMENTS

#### 8vCPU and 16GB required to run even the basic models. 


| Hardware | Requirements     |
| :-------- | :------- | 
| CPU | 8 vCPU |
| RAM | 16 GM RAM |

CONTABO LINK -- [CLICK HERE](https://contabo.com/en/vps/)

## DRIA NODE SETUP GUIDE STEP - BY - STEP

## Pre - requirements

Install Ollama -- [click here](https://ollama.com/download/windows)

Or for vps use this code
```bash
  curl -fsSL https://ollama.com/install.sh | sh
```
Check if it is installed correctly
```bash
  ollama --version
```
## Install Dria Node

Install Dria Launcher - linux/MacOS
```bash
  curl -fsSL https://dria.co/launcher | bash 
```
You can enter refer code to get points
```bash
  dkn-compute-launcher referrals

```
 - use arrows and choose 2nd option and enter the code

 ## Start the Node
Create screen so that even if you close the node will be running
```bash
  screen -S Dria
```

Run the node
```bash
  dkn-compute-launcher start
```
 - Create a new wallet and enter your `private key`
 - When prompted to choose a model, select one from the list, you can choose gemini
  - For gemini key check out this link -- https://aistudio.google.com/app/apikey
  - you can select `gemini-1.5-flash` or `gemini-1.5-pro`
  - Gemini is a google API with upto 1500 free requests daily, No cost, doesn't need VPS resources.

  After this skip the two options before running the node, then your node will be running smoothly.

Use this command to exit the screen -- `Ctrl A + D`

After a while check your points by opening your screen

```bash
  screen -r dria
```

To update the node you can use this code

```bash
  dkn-compute-launcher update
```

To uninstall Dria node
```bash
  dkn-compute-launcher uninstall
```

- You can check your points status here -- [click here](https://dria.co/edge-ai)

## Earn Node keeper role in discord

Join the discord channel -- [click here](https://discord.com/invite/dria)

Fill out the form to get the role

![Image](https://github.com/user-attachments/assets/0855f278-7fa5-4c04-a0f0-83d671d3a918)
## ABOUT ME

Twitter -- https://x.com/SHASHI522004

Github -- https://github.com/cryptowithshashi

Telegram -- https://t.me/crypto_with_shashi

I did not create or write any of these codes, they are all available on the official Dria website. This repository was created solely to help others from the community, with no other intentions. If you have any questions or concerns, feel free to chat with us on Telegram.

Let's gooo
