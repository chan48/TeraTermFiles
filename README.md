TeraTermFiles
=============

these files are macro for TeraTerm(http://sourceforge.jp/projects/ttssh2/).

## LICENSE

these files are provided under WTFPL(http://en.wikipedia.org/wiki/WTFPL).

## 使用方法 How To Use

プログラム内の以下の箇所を編集する。

1. dynamicpassを編集する(9行目)
   - パスワードを実行時に入力する場合は「1」。
   - あらかじめ設定ファイルに記載する場合は「0」。
2. hostname0, portnum0, username0, password0を編集する。
   - 中継サーバのログイン情報。
   - password0は、dynamicpass=0の場合のみ有効。
3. hostname1, portnum1, username1, password1を編集する。
   - 目的のサーバへのログイン情報。
   - password1は、dynamicpass=0の場合のみ有効。

プログラム(.ttlファイル)をttpmacro.exeに関連づけて実行する。

