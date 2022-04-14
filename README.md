<h1 align="center">View Bitcoin price in terminal</h1>
<p align="center">Simple cURL and JQ script</p>

##
<p align="center">
<img src="./btcgif.gif" alt="Video Preview" width="1000px">
</p>

Watch my [video](https://youtu.be/PcrhBHvcouo) on this

### Credit
Credit goes to [alpheratz0](https://github.com/alpheratz0) who commented on a privated video of mine on how to solve my original issue <3

### Install 
```
sudo curl -sL "https://raw.githubusercontent.com/Edesem/BTCPriceInTerminal/main/btc" -o /usr/local/bin/btc
sudo chmod +x /usr/local/bin/btc
```

### Usage
Type btc in the terminal

  **Clarification**, this may break in the future if the website [bitcoinprice.com](https://www.bitcoinprice.com/) has an api change, goes down or of such (as this script essentially just scrapes the api of the website for the stats). This may not work for you if you are unable to access the aforementioned website for whatever paticular reason.

### Update
Just redo the curl command

### Unistall
`sudo rm /usr/local/bin/btc`

### License
[GPL 3.0](https://raw.githubusercontent.com/Edesem/BTCPriceInTerminal/main/LICENSE)
