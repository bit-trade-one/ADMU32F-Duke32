# 多機能リモコンボード「Duke32AIO」

定番のESP-WROOM-32無線モジュールを採用し様々なモータ駆動工作キットを無線遠隔操作可能にする拡張ボードです。

サイズはタミヤユニバーサルプレートに準拠。
既存のモータ駆動ロボットに組み込むことで、サーボモータやフルカラーシリアルLEDなど楽しさを増す機能を拡張できます。

豊富な外部インターフェースを持ち、Grove互換拡張ポート搭載でI²C通信による豊富なGrove対応センサも使用可能です。

無料のスクラッチベース プログラミングアプリ「つくるっち」やAruduinoIDEでのプログラミングが可能。

無線でつなげてヨシ、機能を拡張してヨシ、プログラミングしてヨシの多機能ボードが登場です。                                                                                

## [出荷時ファーム　操作方法はこちら](https://github.com/bit-trade-one/ADMU32F-Duke32/tree/master/Manual)

## [アプリケーションソフト「つくるっち」のページはこちら](http://sohta02.web.fc2.com/familyday_app.html)  

## [「つくるっち」・スマフォからのDuke32AIOの操作方法はこちら](http://sohta02.web.fc2.com/familyday_app3.html)  

## [サンプルコードはこちら](https://github.com/tomorrow56/Duke32_AIO/tree/master/examples/ESP32_WebserverSample_3)  

## [ファームウェアはこちら](https://github.com/tomorrow56/Duke32_AIO/tree/master/DefaultFW)

## [Q&A](https://github.com/bit-trade-one/ADMU32F-Duke32/blob/master/FAQ.md)

## [回路図](https://github.com/tomorrow56/Duke32_AIO/blob/master/ESP32_camrobo_v04_Schema.pdf)

### 製品用途
・既存のロボットや工作キットの拡張

         ・WiFiを通じたリモートコントロール対応
         
         ・サーボモータやシリアルLED機能の拡張
         
         ・Grove端子でセンサを実装
         
         ・スクラッチアプリによるプログラミング動作の実現
         
Etc…

### 製品の特徴
#### ・様々なモータ駆動キットに対応！汎用性のある無線遠隔化拡張ボード！
タミヤユニバーサルプレート準拠で多数のモータ駆動工作キットを無線遠隔可能。

サーボモータやフルカラーシリアルLEDなど、楽しさを増す機能を手軽に拡張できます。

#### ・豊富な外部インターフェースを搭載！Grove互換端子も搭載！
基板上には豊富な外部インターフェースを設置しサーボモータやフルカラーシリアルLEDによるイルミネーション機能などを実装できます。

またGrove互換拡張ポートも搭載、I²C通信による拡張性も確保し豊富なGrove対応センサも使用可能です。
 
#### ・信頼のESP32モジュールを使用！豊富な情報量でプログラミングアプリにも対応
WiFi対応の32 bit デュアルコアMCUをもつESP-WROOM-32を搭載。

定番モジュールとして情報量も多くプログラミングアプリにも対応。

無料のスクラッチベース プログラミングアプリ「つくるっち」やAruduinoIDEでプログラミングすることが可能です。
 
#### 「つくるっち」とは
「つくるっち」は、様々なハードウェアに対応するリアルタイム・グラフィカルロボットプログラミングツールです。

マウスでブロックを並べるだけの簡単操作でロボットの動きをプログラミングでき、作ったプログラムは即時実行可能なほか、ロボットに保存し自動で動かすことができます。
 
### プロダクト製作者ご紹介
ThousanDIY：山崎雅夫
電子回路設計エンジニア。

電器メーカーで量産設計業務に従事したのち、半導体設計会社へ移り、機能評価と製品解析を担当。

2016年から電子工作サイト「ThousanDIY」を運営中。
https://thousandiy.wordpress.com/

2018年より工学社の月刊IOで”「100円ショップ」のガジェットを分解してみる！”を連載中。
https://www.kohgakusha.co.jp/books/detail/978-4-7775-2101-2

ご注意！
本製品をお使いになるには電子工作や電子回路についての一般的な知識が必要です。
（＊USBケーブルは付属致しません。）
________________________________________
#### 基本仕様
【搭載マイコン】ESP-WROOM-32

【搭載モータドライバ】L293D

【外部インターフェース】DCモータ出力x2(ターミナル端子) 、サーボモータ出力x2(2.54mm3Pピンヘッダ)、 デジタルI/Ox4(Groveコネクタx2)、 アナログ入力x2(Groveコネクタx1)
シリアルLED出力(NeoPixel)x1(2.54mm3Pピンヘッダ)、I²C(Groveコネクタ)x1、 UART(Groveコネクタ)x1、 USB(MicroB)x1 

【電源】USB電源／モータ用外部電源端子(4.5~6V)(2電源必須)

※注意！モータ用外部電源端子に接続する電源電圧は、DCモータ、サーボモータの定格電圧をご確認の上、適切な電源電圧を接続してください。
適切な電源電圧を使用しないと、DCモータやサーボモータの動作不良や故障の原因となります。
モータ用外部電源端子にDC6Vを超えた電圧を絶対に接続しないでください。故障の原因となります。

【プログラミング環境】専用アプリ (対応OS Windows)or Arduino IDE(対応OS Windows,MAC OS,他)

【本体重量】約18g

【本体サイズ】W70×H11×D45mm

【使用温度】 0 ～ 40℃（結露なきこと）

#### ―――本製品取扱についてのご注意―――
・本製品は、ホビー向け商品です。個人利用に限定されます。

・記載の部品性能は部品単体での性能であり、製品寿命を保証するものではありません。

・すべての機能をご利用いただけない場合があります。

・本製品は電子回路部が露出しています。感電には十分に注意し、お子様が使用される場合には保護者の監視をお付け下さい。

・本製品の使用に関し当社の責に帰すべき事由に基づき、お客様に損害が生じた場合、直接被害に限り、販売代金を上限として損害を賠償し、いかなる場合においても販売代金以上の損害を賠償しないものとします。

 ・そのほか記載されているロゴ、システム名、製品名は各社及び商標権者の登録商標あるいは商標です。
 
・改良のため、予告なく仕様変更をすることがあります。あらかじめご了承下さい。
