# open-source-mouse
## sfc2013-design-strategy    
This document is made by [gitfab](http://gitfab.org)
---
#動くマウス

「動く」マウスです。
動きます。

用意するものリスト<br>
1.<a href="http://akizukidenshi.com/catalog/g/gM-01905/">サーボモータ PICO/STD/F</a><br>
2. <a href="http://www.switch-science.com/catalog/663/">ATmega328P</a><br>（<a href="http://www.switch-science.com/catalog/1414/">こちら</a>だと3,4を省略できて楽）<br>
3. <a href="http://akizukidenshi.com/catalog/g/gP-00545/">水晶発信器(16MHz)</a><br>
4. <a href="http://akizukidenshi.com/catalog/g/gP-03620/">セラミックコンデンサ 22pF</a><br>
5. <a href="http://akizukidenshi.com/catalog/g/gR-25103/">抵抗器10kΩ</a><br>

![DSC00501.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00501.JPG)

ネジ止め用の出っ張りを除去します。

![DSC00508.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00508.JPG)

反対側も除去します。ついでに球が入っている場所のプラスチックも少し除去します。

![DSC00507.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00507.JPG)

球に穴を開けて、サーボモータを接着します。

![DSC00503.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00503.JPG)

小型の自作arduinoを作ります。<br>
実際に半田付けする前にマイコンにArduinoのExamples>Servo>Sweepを書き込んでおきます。<br>
<a href="https://sites.google.com/a/gclue.jp/android-docs-2009/zi-zuoarduinono-zuo-cheng">参考</a>

![DSC00504.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00504.JPG)

電源はUSBから分けてもらいましょう。

![DSC00505.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00505.JPG)

最後にボンドで絶縁やら接着をして完成です。

![DSC00509.JPG](https://raw.github.com/mkono/open-source-mouse/master/gitfab/resources/DSC00509.JPG)
---
#あとがき

TAの人の暇つぶしです。


サーボじゃなくてDCモータの方が良さ気。


球に穴を開ける際に軸がずれると中途半端な動きになります。


動画は何れ！

---
