# 必要なパッケージのインストール
## Scoopのインストール
[scoop.sh](https://scoop.sh/)にアクセスして下2つのコードをPowershellに入力する
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
```powershell
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

aria2c と git をインストールする
```powershell
scoop install aria2 git
```

extraパッケージを有効にする
```powershell
scoop bucket add extras
```

パッケージをインストールする
```powershell
scoop install firefox vscode musicbee discord
```

### Firefoxのプロファイル設定
1. firefox profile managerを開く
2. "Scoop"のプロファイルを選択
3. "Use the selected profile without asking at startup"にチェックを入れ､"Start Firefox"で起動

### Scoopでインストールできないパッケージのインストール(管理者権限のいるやつ)
- [google-chrome](https://www.google.com/intl/ja_jp/chrome/) Scoop経由でいれると自動アップデートがおかしくなる為
- [Voicemeeter Potato](https://shop.vb-audio.com/en/win-apps/21-voicemeeter8.html) 画面上で使えるオーディオミキサー
- [logicool ghub](https://gaming.logicool.co.jp/ja-jp/innovation/g-hub.html) Webカメラとマウスの設定ソフト
- [Nvidia driver](https://www.nvidia.co.jp/Download/index.aspx?lang=jp) グラフィックドライバー

ゲーム関連
- [Steam](https://store.steampowered.com/about/)
- [EA app](https://www.ea.com/ja-jp/ea-app)
- [genshin_impact](https://genshin.hoyoverse.com/ja):100:

## Microsoft Store経由でインストール
- [Monitorian](https://apps.microsoft.com/detail/9nw33j738bl0) マルチモニター環境で便利

