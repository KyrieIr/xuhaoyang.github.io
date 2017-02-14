---
layout: post
title:  "Fiat Lux"
date:   2017-2-15
---
# Day 1
### Crypto 1  fuck your brain
在网上找到brainfuck解码器解码即可。
### Web 1 你再跳啊
用burpsuite跑一下
<img src="{{ '/assets/img/1.png' | prepend: site.baseurl }}" alt="">
### Misc 1 签到
用base64解码,再用栅栏解码就好。（所谓栅栏密码，就是把要加密的明文分成N个一组，然后把每组的第i个字连起来，形成一段无规律的话。）
# Day 2
### Web 4 单身二十年的手速
方法同Web 1。
### Web 5 极度暴力
用Burpsuite入侵
<img src="{{ '/assets/img/2.png' | prepend: site.baseurl }}" alt="">
<img src="{{ '/assets/img/3.png' | prepend: site.baseurl }}" alt="">
<img src="{{ '/assets/img/4.png' | prepend: site.baseurl }}" alt="">
得到密码是1238时长度不同于其他，所以密码为1238 输入可得到flag。
