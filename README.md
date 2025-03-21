# ClipStore Debian Repository

This repository hosts the Debian packages for ClipStore, a modern clipboard manager for Linux.

## Adding this repository

```bash
# Download and install the GPG key
wget -O - https://yourusername.github.io/clipstore-repo/public.key | sudo apt-key add -

# Add repository to sources.list
echo "deb [arch=amd64] https://zahid4kh.github.io/clipstore-repo stable main" | sudo tee /etc/apt/sources.list.d/clipstore.list

# Update package database
sudo apt update

# Install ClipStore
sudo apt install clipstore
```
