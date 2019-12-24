Seeed deb Package Repository for ARM-Linux 
==============================================

| Codename | Architecture | 
| :------: | :----------: |
| buster   | armhf        | 
| bionic   | armhf        | 


### Add repository
```
# For STM32MP1
echo "deb https://seeed-studio.github.io/seeed_linux_bundle/ buster main" | sudo tee /etc/apt/sources.list.d/seeed.list
```

### Add public GPG key
```
curl https://seeed-studio.github.io/seeed_linux_bundle//public.key | sudo apt-key add -
```
