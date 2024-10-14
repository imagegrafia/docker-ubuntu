# Nvm install ref 
https://github.com/nvm-sh/nvm

# 0. download and restart terminal 
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# Exportpath
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"

# check install
nvm -v

# 1. install node 16
nvm install 16
# 2. use specific version 
nvm use 16
