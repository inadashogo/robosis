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
# 実行コマンド

　消去コマンド
  
    echo 0 > /dev/myled0 
    echo 2 > /dev/myled0
    echo 4 > /dev/myled0
    
    点灯コマンド
    
    echo 1 > /dev/myled0
    echo 3 > /dev/myled0
    echo 5 > /dev/myled0
 # ライセンス
 
 https://github.com/inadashogo/robosis/blob/baec4107f14362a07abd488b6190be8065011150/COPYING



