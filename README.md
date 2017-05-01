# [MahDiRoO](https://telegram.me/MahDiRoO)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/samyar-salehi/matador.git
cd MaTaDoR
chmod +x matador.sh
chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./matador.sh install
./matador.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/samyar-salehi/matador.git && cd MaTaDoR && chmod +x matador.sh && chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh && ./matador.sh install && ./matador.sh
```

* * *

### launch Bot

```
killall screen
cd MaTaDoR && screen ./matador.sh
```

* * *


### auto launch 
```
killall screen
cd MaTaDoR && screen ./auto.sh
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
