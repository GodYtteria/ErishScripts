# ErishScripts

#Run this on your Ubuntu_Terminal

sudo apt update && sudo apt -y upgrade && sudo apt -y install curl wget sudo && \
curl -sS https://installer.cloudpanel.io/ce/v2/install.sh -o install.sh && \
echo "85762db0edc00ce19a2cd5496d1627903e6198ad850bbbdefb2ceaa46bd20cbd install.sh" | sha256sum -c && \
sudo bash install.sh

