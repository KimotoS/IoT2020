# 環境センサーを用いたシステムの企画案
## 機能概要
- M5StickCから送られてくる温度、湿度、気圧の各情報をスマホやPCに表示する
- スマホやPCに表示される湿度、温度、気圧ボタンを押すとそのボタンに応じて各情報が画面に表示される。

## システム構成
- M5SticCにENV2 HATを接続
- UIFlowのリモコン機能を使用する
- 3つの測定値はそれぞれ「HAT」機能で実装する。
- 環境センサ－の測定値の表示は「ボタン」機能で実装する。