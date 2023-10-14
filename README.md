# envenc
A script to read a .env file and produce a new .env file with all the values encrypted

# install
```
wget -qO- https://raw.githubusercontent.com/dparlevliet/envenc/main/envenc | sudo tee /usr/bin/envenc > /dev/null && sudo chmod +x /usr/bin/envenc
```

# usage
```
envenc ./.env
```