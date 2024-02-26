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

# VS Codeの環境構築(主にAtcoder用)
## 概要
- VS Codeの基本設定
- WSLの設定
- C++関連の設定
- AtCoder用の設定

### VS Codeの基本設定
VSCodeで拡張機能のインストール
- Japanese Language Pack for Visual Studio Code
- Vim
### WSLの設定
1. [wslのインストールガイド](https://learn.microsoft.com/ja-jp/windows/wsl/install)の手順でインストール
2. ディストリビューションでUbuntuをインストール
3. 初期設定(ユーザー、パスワードの設定)
4. Ubuntuのパッケージ一覧を更新&必要なパッケージの導入
```
sudo apt update -y && sudo apt install gcc build-essential
```
### C++関連の設定
VSCodeで拡張機能のインストール
- WSL
- C/C++
### AtCoder用の設定
ライブラリAtCoder Library (ACL)の導入
atcoder-cliのインストール
online-judge-toolsのインストール
上2つの設定


