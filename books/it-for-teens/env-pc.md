---
title: "01-1: PCの調達"
---

# 背景
ほとんどの中高生、もしくは小学生は自らの「自由に」使えるPCを所持していないと思う。この「自由に」というのは勝手にOSを入れ替えたり初期化しても良いということである。大抵の場合与えられるPCというのは家族との共用であったり、学校からの貸与品であったりすると思う。後述するが、このような「自由でないPC」で何かの開発を行うことは容易ではない。そこで、まともなPCを所持していない場合にどうすればいいのか解説する。

# 自由でないPCの問題点
自由ではないPCでは、自由にソフトウェアをインストールすることができない。これではIDEやコンパイラなどの開発に必須となるソフトウェアをインストールできない。また、PCのシステムに関わる開発をしようと思ったときに、PCを壊す可能性があるということでそれらが妨げられる可能性がある。その他にも、くだらないフィルタリングにより必要な情報にアクセスできないなど、ITに入門する上で問題点が多数ある。

# 手段
自由なPCを手に入れる手段はいくつかあるが、最も手っ取り早いのは自分の持っているお金で購入してしまうことだろう。「そうはいっても、手持ちのお金でPCなど買えない」と思う人も多いだろうが、何もPCというのは最新式のゲーミングPCでなければ開発ができないわけではない。

## ジャンク・中古PCを買う
ある程度お金に余裕があるなら、中古で保証のついているPCを買うと良いだろう。中古ならおすすめはノートPCである。なぜなら、モニターやキーボード、マウスなどの周辺機器を買う手間が省けるからである。また、古くても気合を入れればACアダプターと一緒に運ぶことができるから、授業で必要なときに持ち運んだり~~学校で見せびらかしたりできる。~~本当にお金に余裕がないなら、頑張って下の条件に合うジャンク品を買うとよい。

条件としては
- Core iシリーズを搭載している
- AMD Aシリーズ以降を搭載している
- メモリを4GB以上搭載している
- Let's Note、Thinkpad、HP、DELLだとなお良い（後述する）
- バッテリーは気にしなくても良い
    - 中古でバッテリーが持つ方が珍しい
- OSの有無は気にしなくても良い
    - ただし、自宅に一つもPCがないならWindowsが入っているものを買うと良い

といったところだろうか。次のようなPCは**買ってはいけない。**
- Atomシリーズを**搭載している**
    - 本当に使い物にならない、反骨心があるなら買うといい
- Windows VistaとかXPとかのシールが貼ってある
- タバコの匂いがする
- 通電しない
- 液晶が割れている
- 64Bit対応でないPC
    - CPUの型番を検索するとよい
- mac
    - 中古だと修理も改造も難しい

また、「PCお譲りします」というチラシは無視して良い。コストパフォーマンスがどうしようもないほど悪い。

## 次
次は、手に入れたPCの上にどのようにして開発環境を構築するか述べる。