---
title: "2026/10/06版リリース"
date: 2026-10-06
categories: ["語学講座CS2"]
tags: ["リリース"]

---
#### 語学講座CS2の2026/10/06版　2026年度後期（Qt6.12LTS）版をリリースしました。更新は必須ではありませんが、バグ修正があるので更新を推奨します。
####                
#### [語学講座CS2](https://csreviser.github.io/CaptureStream2/)
####  
####  2026年度後期（Qt6.12LTS）版

#### ＜変更内容＞　　　
#### ＜全OS共通＞
#### （１）Qt6.12.0に移行しました。
#### 　・Qt6の最新LTSバージョンに更新しました。

#### （２）番組IDを指定して録音を実行する機能を追加
#### 　・番組IDは１番組に特定できれば部分一致でも指定可能です。

#### （３）日付補正機能追加
#### 　・放送設備メンテによる放送前倒しに伴う日付け補正追加
#### 　・深夜の再放送時間帯が初回放送となった場合の日付補正機能追加
#### 　・デフォルト有効ですが、無効にすることができます。

#### （４）ffmpeg自動検索対象拡大しました。
#### 　・Mac版は「/Applicasions」を検索対象に追加
#### 　・Windows/Linuxはパスが通っているffmpegを検索機能追加

#### （５）拡張子：m4b 追加

#### （６）CLIモードで-t、-fオプションが機能しない不具合を修正しました。
#### 　・-t、-fオプションは今週番組向け
#### 　・-t2、-f2オプションは前週番組向け

#### （７）Windowsでファイル名禁止文字（半角文字）を全角文字に修正する機能を追加しました。

#### 　＜macOS＞
#### 　・dmgファイルに「Applicasions」ショートカット(エイリアス）追加

####  　　　  
####  






####  　　　  
####  　
* ### MacOS用 
**[QtとOSの対応はこちらで確認できます。](./Qt_vs_OS#macos)**
* ### **[CaptureStream2-MacOS-AppleSilicon-20261006.dmg](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-MacOS-AppleSilicon-20261006.dmg)**
* ### **[CCaptureStream2-MacOS-Universal-20261006.dmg](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-MacOS-Universal-20261006.dmg)**
* ### **[CaptureStream2-MacOS-qt6-5-20261006.dmg](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-MacOS-qt6-5-20261006.dmg)**
**macOS-10.14／macOS-10.15(Qt6.2)**

### Windows用
* ### **[CaptureStream2-Windows-20261006.zip 【64bit版】](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-Windows-20261006.zip)**
* ### **[CaptureStream2-Windows-x86-20261006.zip 【32bit版】](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-Windows-x86-20261006.zip)**

### Linux用（参考公開）
* ### **[CaptureStream2-AppImage-x64-20261006.zip](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-AppImage-x64-20261006.zip)**
* ### **[CaptureStream2-AppImage-arm64-20261006.zip](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-AppImage-arm64-20261006.zip)**

* ### **[CaptureStream2-ubuntu-20261006.zip](https://github.com/CSReviser/CaptureStream2/releases/download/20261006/CaptureStream2-ubuntu-20261006.zip)**
####  　　　  
####  　　　  
####  
