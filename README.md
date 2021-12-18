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
# インストール・ビルド・アンインストール　コマンド
　インストール
     
     git clone https://github.com/inadashogo/robosis.git
     cd robosis
     
  ビルド
  
     make
     sudo insmod myled.ko
     sudo chmod 666 /dev/myled0
     
   アンインストール
     
     sudo rmmod myled
     
# 実行コマンド
    
     echo 0 > /dev/myled0(LEDをつける)
　
 # ライセンス
 
 https://github.com/inadashogo/robosis/blob/baec4107f14362a07abd488b6190be8065011150/COPYING
 
 # 著作権
 
 
 



