Seeed deb Package Repository for ARM-Linux 
==============================================

| Codename | Architecture | 
| :------: | :----------: |
| buster   | armhf        | 
| bionic   | armhf        | 
| stretch   | armhf        | 


### Add repository
```
echo "deb https://seeed-studio.github.io/seeed-linux-deb/ buster main" | sudo tee /etc/apt/sources.list.d/seeed.list
```

### Add public GPG key
```
curl https://seeed-studio.github.io/seeed-linux-deb/public.key | sudo apt-key add -
```
