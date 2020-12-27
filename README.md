```
echo deb https://raw.githubusercontent.com/nagasawa/apt/master/ nagasawa main | sudo tee /etc/apt/sources.list.d/nagasawa.list
wget -qO - https://raw.githubusercontent.com/nagasawa/apt/master/gpg-public.key.backup | sudo apt-key add -
apt update
```
