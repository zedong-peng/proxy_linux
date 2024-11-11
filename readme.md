clash release page: https://github.com/MetaCubeX/mihomo/releases

download [mihomo-linux-amd64-alpha-08dcef8.gz](https://github.com/MetaCubeX/mihomo/releases/download/Prerelease-Alpha/mihomo-linux-amd64-alpha-08dcef8.gz)
```
wget https://github.com/MetaCubeX/mihomo/releases/download/Prerelease-Alpha/mihomo-linux-amd64-alpha-08dcef8.gz

chmod +x mihomo-linux-amd64

mv mihomo-linux-amd64 clash

mkdir -p $HOME/.config/clash

wget -O $HOME/.config/clash/config.yaml [订阅链接]


./clash
```
no need to set http_proxy env in .bashrc