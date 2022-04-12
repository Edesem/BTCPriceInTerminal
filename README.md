<h1 align="center">View Bitcoin price in terminal</h1>
<p align="center">Simple curl script</p>

### Install

```bash
if hash jq 2>/dev/null; then
  sudo curl -sL "https://raw.githubusercontent.com/Edesem/BTCPriceInTerminal/main/btc" -o /usr/local/bin/btc
  sudo chmod +x /usr/local/bin/btc
else
  if hash apt 2>/dev/null; then
    sudo apt install -y jq
  fi
  if hash dnf 2>/dev/null; then
    sudo dnf -y install jq
  fi
  if hash pacman 2>/dev/null; then
    sudo pacman -S --noconfirm jq
  fi
  sudo curl -sL "https://raw.githubusercontent.com/Edesem/BTCPriceInTerminal/main/btc" -o /usr/local/bin/btc
  sudo chmod +x /usr/local/bin/btc
fi
```

### Usage

Type btc in the terminal

### Update

Just redo the curl command

### Unistall

`sudo rm /usr/local/bin/btc`

### License

[GLP 3.0](https://raw.githubusercontent.com/Edesem/BTCPriceInTerminal/main/LICENSE)
