# Okx multi-wallet withdraw
Only for 阿彬168
## Description

Okx 多地址提幣功能

## Getting Started

### Dependencies

okx-api-v5
### Installing

到okex-api-v5目錄下
```
1. hold down shift key and right-click
2. Open PowerShell
3. python setup.py install
```
### Executing program

```
1. Go to okx.com and get the api key, set multi-wallet addresses to whitelist.
2. Edit config.json and set token key secret passphrase (don't set network)
3. Run 1_getTokenSetting.bat, it will show the correct network config
4. Fill in the network and mount
5. Run 2_withdraw to start withdraw process...
```
## Help

Any advise for common problems or issues.
```
Need to add the address to whitelist or you can't use
```

## Authors

Contributors names and contact info

ex. Liz (https://t.me/liiiztw)
ex. Griselda (https://twitter.com/Griseld97265984)

## Version History

* 1.0
    * Initial Release

## License

BSD 3-Clause License

## Acknowledgments

* [okex-api-v5 - marzwu ](https://github.com/coinrising/okex-api-v5)
