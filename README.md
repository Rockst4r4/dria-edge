# What is Dria?
Dria is a distributed, crowdsourced hyperscaler—a movement led by everyday people that unlocks faster, more affordable inference for everyone.
Dria network is a decentralized Edge AI network that allows anyone to contribute to AI by running a node and earn rewards for their contribution. Our goal is to make AI inference accessible and efficient by leveraging a global network of contributors. Dria powers scalable, high-performance inference across diverse CPU and GPU platforms. Our mission is to deliver accessible, cutting-edge performance anytime, anywhere.
# Installation
Its Simple , Install DRIA
```
sudo apt update && sudo apt upgrade -y && curl -fsSL https://ollama.com/install.sh | sh && curl -fsSL https://dria.co/launcher | bash
```
create a screen
```
screen -S dria

```
just Replace your private key and Copy paste codes!
```
sed -i -e 's/DKN_MODELS=.*/DKN_MODELS=gemini-2.0-flash,gemini-2.5-pro-exp-03-25,gemma3:4b,llama3.1:8b-instruct-q4_K_M,llama3.2:1b-instruct-q4_K_M/' -e '/^DKN_WALLET_SECRET_KEY=/ s|=.*|=PRIVATE_KEY|' /root/.dria/dkn-compute-launcher/.env && dkn-compute-launcher start
```
## Just Replace your Private key with PRIVATE_KEY
You need google gemini API, take it from here: https://aistudio.google.com/app/apikey
## then exit your screen using CTR+A+D

you can check your points from here : https://dria.co/edge-ai
