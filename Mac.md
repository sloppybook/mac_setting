# これは何？

さかもとのMacでの開発環境構築
※2022/11/11時点

# Mac本定基本設定

## 「共有」
- コンピュータ名を変更

## 「トラックパッド」
- 「ポイントとクリック」はすべてチェックする
- 「スクロールとズーム」は「スクロールの方向： ナチュラル」以外すべてチェックする
  - なぜかこれで慣れてしまった
- 「その他のジェスチャ」は「アプリケーションExpose」以外すべてチェックする

## 「キーボード」
- 「キーボード」の「Apple内蔵キーボード/ドラックパッド」にてCaps Lock -> Control, Control -> Caps Lockにする
  - USの場合だけかもしれん
- 「ショートカット」でspotlightの項目の「spotlight検索を表示」と「Finderの検索ウィンドウを表示」のチェックを外す

## 「セキュリティとプライバシー」

- 「一般」で「スリープとスクリーンセーバの解除にパスワードを要求」を「開始後：すぐに」に設定
- 「ファイアウォール」でファイアウォールを「オン」に設定する

## スクショの保存先を変更
デフォルトではデスクトップになっているが画面ぐちゃぐちゃして苦手なので
Command + Shift + 5のオプションより変更可能
`/Users/{User}/Pictures/screenshot`とかに設定してます

# 日常利用系アプリケーション


## Google Chrome
プライベートではSidekickとかBraveとかも使ってみたり

## Slack

## Google 日本語入力

## Clipy
コピペ拡張アプリ

# 開発系アプリケーション

## Visual Studio Code

## Xcode

## homebrew

## git
```
brew install git

vi ~/.zshrc
# 以下追加
export PATH="/usr/local/git/bin:$PATH"
# 反映
source .zshrc
```
https://acokikoy.hatenablog.com/entry/2021/03/10/133558

## iTerm2

## LICEcap
画面上の動作をGifで見せたいときに便利

## ファインダーでの隠しファイルの表示
```
defaults write com.apple.finder AppleShowAllFiles -bool true
killall Finder
```
