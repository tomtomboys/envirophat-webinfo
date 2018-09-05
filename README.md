# envirophat-webinfo

Enviro pHATのWeb情報画面表示スクリプト


## 導入用意

### Python2

```
sudo pip install -r requirements.txt
```


### Python3

```
sudo pip3 install -r requirements.txt
```


## 継続化

[isaax](https://isaax.io) を使う場合、以下のようなisaax.jsonを挿入する。

```json
{
  "name": "envirophat-webinfo",
  "version": "0.0.0",
  "description": "enviro pHATWeb display",
  "main": "main.py",
  "author": "nc30",
  "license": "GPL",
  "language":"python",
  "scripts": {
     "start": "python3 main.py"
    },
   "dependency": null
}
```
