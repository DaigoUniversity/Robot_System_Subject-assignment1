# ロボットシステム学 課題1
 
LEDを光らせるデバイスドライバのプログラムです。
C言語を使用しています。
 
# デモ
### デモ動画
https://www.youtube.com/watch?v=6jj6drCYsUE

### 回路例

<img src="https://user-images.githubusercontent.com/93714969/146319800-2da83175-fd14-4953-8905-f17996abc907.jpg" width="640px">


 
# 特徴
 
LEDを光らせることができます。
 
# 必要品
 
* Ubuntu
* Raspberry Pi
* LANケーブル
* ルーター
* USB Micro-B

# 使用法
 
DEMOの実行方法など、"hoge"の基本的な使い方を説明する
 
```bash
git clone git@github.com:DaigoUniversity/Robot_System_Subject-assignment1.git
cd Robot_System_Subject-assignment1

make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0

echo 1 > /dev/myled0 //LED点灯
echo 0 > /dev/myled0 //LED消灯

sudo rmmod myled
```

# 著者
 
作成情報を列挙する
 
* 作成者
* 所属
* E-mail
 
# ライセンス
ライセンスを明示する
 
"hoge" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
 
社内向けなら社外秘であることを明示してる
 
"hoge" is Confidential.

