# robosis
# 目標
   ・raspiを使ってLEDを光らせてみる。
# 動作環境 
   
   ・Ubuntu
   
   ・rasberry pi
   
   ・LED
   
   ・Lanケーブル
   
   ・モニター
   
   ・ブレッドボード
   
   ・抵抗
# 概要
   ・数字の0~5でLEDを消したり、光らせる。
# インストール・アンインストール・ビルド　コマンド
# 実行コマンド

　消去コマンド
  
    echo 0 > /dev/myled0 (0を入力するとLED1が消える)
    echo 2 > /dev/myled0 (2を入力するとLED2が消える)
    echo 4 > /dev/myled0 (4を入力するとLED3が消える)
    
    点灯コマンド
    
    echo 1 > /dev/myled0 (1を入力するとLED1が点灯する)
    echo 3 > /dev/myled0 (3を入力するとLED2が点灯する)
    echo 5 > /dev/myled0 (5を入力するとLED3が点灯する)
 # ライセンス
 
 https://github.com/inadashogo/robosis/blob/baec4107f14362a07abd488b6190be8065011150/COPYING



