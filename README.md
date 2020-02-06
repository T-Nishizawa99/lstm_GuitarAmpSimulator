# lstm_GuitarAmpSimulator
「機械学習でギターアンプをモデリングする」
https://qiita.com/coz-a/items/aeab3c52e3f12ba52a8b
を基にデータの解像度を変化させたときの影響を検証しました．

変更点は2つ
データの解像度の種類を
ビット深度-サンプリングレート：①16bit-48kHz，②24bit-192kHz
の2種類に変更しました．
スライディングウィンドウを110ms->100msにしました．

使い方：

google colabolatoryでdriveを同期させた後に上から順に実行していくだけです．
config_16_48.yml,config_24_192.yml
に学習の際に使用する変数やデータのディレクトリが書かれています．
用途に合わせて解像度の指定を行ってください．

データは以下のgoogle driveからダウンロードをしてください
https://drive.google.com/open?id=1nJvCkyxJ_JzfGXaWn5p-1u8r2Z3mubTx
また高解像度でデータを作成してあるのでデータ量が膨大です（3.51GB）．ダウンロードの際は容量に注意しながらお願いします．
