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
   
# 回路写真

<img src="(https://user-images.githubusercontent.com/95764130/146651184-764b3f8e-e1d2-493e-91a3-deb256b17b59.jpg)"

   
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
 
 GNU General Public License v3.0
 
 COPYING 参照
 
 # 著作権
   Ueda Ryuichi
 
 
 



