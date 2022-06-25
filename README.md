# ani-cli-ppa
A ppa for the ani-cli package for debian.

This package will be update after every relase of the offical ani-cli tool. So if you want to alwayse be on top of erverthing you can use ``` ani-cli -U ``` (only as long as they are no mayor changes).

If you dont want to wait install from github.com/pystardust/ani-cli directly.


# Install # 
To add the PPA to your system use the following commands.

``` 
wget -qO- https://Wiener234.github.io/ani-cli-ppa/KEY.gpg | sudo tee /etc/apt/trusted.gpg.d/ani-cli.asc
wget -qO- https://Wiener234.github.io/ani-cli-ppa/ani-cli-debian.list | sudo tee /etc/apt/sources.list.d/ani-cli-debian.list
sudo apt update
```
