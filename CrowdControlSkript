#!/bin/bash

while true
do

# Logo

echo "========================================================================================================================"
curl -s https://raw.githubusercontent.com/Flip-ok/Logo/main/Logo4861.sh | bash
echo "========================================================================================================================"

# Menu

PS3='Select an action: '
options=(
"Install Node"
"Check Log"
"Check balance"
"Request tokens in discord"
"Create Validator"
"Exit")
select opt in "${options[@]}"
do
case $opt in

"Install Node")
echo "============================================================"
echo "Install start"
echo "============================================================"
echo "Setup NodeName:"
echo "============================================================"
read NODENAME
echo "============================================================"
echo "Setup WalletName:"
echo "============================================================"
read WALLETNAME
echo export NODENAME=${NODENAME} >> $HOME/.bash_profile
echo export WALLETNAME=${WALLETNAME} >> $HOME/.bash_profile
echo export CHAIN_ID=Cardchain >> $HOME/.bash_profile
source ~/.bash_profile
