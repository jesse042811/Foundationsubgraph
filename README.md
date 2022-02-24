# Foundationsubgraph
Subgraph for querying NFTs

## Install and Update Script to run NVM

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash


export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")" [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"


## To Confirm if installed 

command -v nvm


## Need to run this in terminal

npm install -g @graphprotocol/graph-cli


## Commands for the Subgraph: Subgraph that indexes data off Ethereum mainnet

graph init --product hosted-service <GITHUB_USER>/<SUBGRAPH NAME>

yarn install

yarn codegen
  

## Commands for the Subgraph: Deploy your subgraph to the Graph Node
    
graph auth --product hosted-service <ACCESS_TOKEN>

graph deploy --product hosted-service <GITHUB_USER>/<SUBGRAPH NAME>
  
  
## Select the following to run Subgraph
  
✔ Protocol · ethereum
✔ Subgraph name · jesse042811/Foundationsubgraph
✔ Directory to create the subgraph in · Foundationsubgraph
✔ Ethereum network · mainnet
✔ Contract address · 0xc9fe4ffc4be41d93a1a7189975cd360504ee361a
✔ Fetching ABI from Etherscan
✔ Contract Name · Token
  

## Next Steps

1. Run `graph auth` to authenticate with your deploy key.

2. Type `cd Foundationsubgraph` to enter the subgraph.

3. Run `npm run deploy` to deploy the subgraph.

  
  
  
  
  
  
  
  
  
