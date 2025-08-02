# termux-repos
echo "deb [trusted=yes] https://trh4ckn0n.github.io/termux-repos/ ./" | sudo tee /etc/apt/sources.list.d/trh4ckn0n.list
sudo apt update
sudo apt install trh4ckn0n-tool
trh4ckn0n_tool
