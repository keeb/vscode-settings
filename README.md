# vscode-settings
settings for vs-code

## Deploy to new machine (Linux)
```bash
# Copy settings
cp settings.json ~/.config/Code/User/settings.json

# Install extensions (see extensions.md for full list)
code --install-extension drewxs.tokyo-night-dark
code --install-extension ms-vscode-remote.remote-ssh
# ... (install others as needed)

# Install font
sudo apt install fonts-bitstream-vera
```
