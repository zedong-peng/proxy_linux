clash release page: https://github.com/MetaCubeX/mihomo/releases

download [mihomo-linux-amd64-alpha-08dcef8.gz](https://github.com/MetaCubeX/mihomo/releases/download/Prerelease-Alpha/mihomo-linux-amd64-alpha-08dcef8.gz)
```
wget https://github.com/MetaCubeX/mihomo/releases/download/Prerelease-Alpha/mihomo-linux-amd64-alpha-08dcef8.gz

chmod +x mihomo-linux-amd64

mv mihomo-linux-amd64 clash

mkdir -p $HOME/.config/clash

wget -O $HOME/.config/clash/config.yaml [订阅链接]

vim $HOME/.config/clash/kingfast.yaml # edit the conflict port

git config --global http.proxy "http://127.0.0.1:8080"
git config --global https.proxy "http://127.0.0.1:8080"

./clash -f $HOME/.config/clash/kingfast.yaml
```