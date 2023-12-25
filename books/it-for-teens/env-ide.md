---
title: "01-3: 開発環境"
---

# 開発環境
PCがとりあえずLinuxで使えるようになったら、次は開発環境を整える必要がある。ここでは、どのように開発環境を整えるかについて解説する。

とは言ってみたものの、開発環境など個人の好みでいくらでも変わってしまうので、あまり解説することがない。とりあえず、エディタには[Visual Studio Code](https://code.visualstudio.com/)をダウンロードして、好みの言語の開発環境を整えると良い。

C++なら、
```sudo apt install g++```
Pythonなら、
```sudo apt install python3-pip```
とすれば完了である。

AIでの分野での開発をしたい場合には、Pythonに加えてAIのためのライブラリとCUDA関係のライブラリをインストールする必要があるだろう。とりあえず、
```sudo apt install python3-numpy python3-torch```
とした後に、[この資料（英語）](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html)を参考にCUDAをインストールすると良い。なお、買ったPCにnvidia製のGPUがついていないなら、CUDAをインストールする必要はない（というより、インストールできない）。

Webの分野での開発をしたい場合は、FlaskやRubyOnRailsなどのフレームワークや[Docker](https://docs.docker.com/get-docker/)やKubernetesの基本的な使い方を学ぶと良いと思われる。
