# Hotaru-Project-install-full 

![S__9969674.jpg](./S__9969674.jpg)

This installation is done for Raspberry Pi 3 model B+ (In fact, even if this version of Raspberry pi is the newest in model3, it took long time)
With some sort of upgrade or changes, it might be error to install in Raspberry pi 4
In this case it needs to be changed

Also would like to mention this is a personal memo 
So this read me includes many info that is not related to actual installation


#### [for little tip in writing Github](https://style.potepan.com/articles/33682.html)
#### [Little tip for writing Github](https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa)

# First step Raspberry pi setup

## Raspberry pi and other stuff preperation

- For the setup look this look this [link](https://qiita.com/Higemal/items/c817b96c3806f23b35f6) and prepare until 準備２.
  (For Raspberry pi 4　[link](https://raspida.com/rpi-setup2021) )
 
 {Copy from Hotaru initial Github read me}
- まずは、Raspberry PiにLANケーブルとHDMIケーブルをつなぎます。
  - Raspberry Piに挿す方はmicro HDMIケーブルです。
- micro変換アダプターを付けるなら幅狭の方が良いですが、ないなら仕方ない。
- このとき、モニターは電源をONにしておきます。
- 次に、5V3Aの電源アダプターをつなぎます。
- type-Cです。これくらいの電圧電流は確保しておきましょう。

## Ubuntu install

Follow this [Ubuntu install](https://ubuntu.com/tutorials/how-to-install-ubuntu-on-your-raspberry-pi#1-overview)

install ubuntu20.04.5 64bit arm64

Raspberry Pi Imager is useful

For istallation of desktop → if you don't needed you can skip it

If you installed desktop, you can always change GUI(desktop showing) to CUI(terminal only
) 

Follow the [link](https://tek2tech.com/ubuntu-2004-desktop-environment/)

When you insert SD card and try to open by raspberry pi, ***do not write the login name and pass word imidately***

You need to wait for 2 min ~

#### For Raspberry pi3, it is better not to install ubuntu desktop or install xubuntu, lubuntu desktop

xubuntu lubuntu desktop detail [link1](https://waldorf.waveform.org.uk/2020/ubuntu-desktops-on-the-pi.html) 
[link2](https://kledgeb.blogspot.com/2013/04/ubuntu-2-ubuntukubuntuxubuntulubuntu.html)

#### When you got ubuntu running, prefered to follow and install from this [link](https://qiita.com/karaage0703/items/705f1b750c486f00d554)

Setup supporting web page [link](https://tek2tech.com/ubuntu-2004-desktop-environment/)

Small tips for biginner of ubuntu [link](https://qiita.com/karaage0703/items/705f1b750c486f00d554)

## SSH Wifi Setup

If you finish installing ubuntu, next is wifi and ssh setup

(If you already done at *Ubuntu install*, skip this part and only check ssh)

Follow the [Link](https://github.com/Danish-Ai-Lab/Hotaru-Project-install-full/blob/main/wifi%20ssh%20setup%20process)

This the [web page](https://bitto.jp/posts/%E6%8A%80%E8%A1%93/raspberry-pi/pi4-setup-wifi/) I looked for

[(Vim tips)](https://qiita.com/hide/items/5bfe5b322872c61a6896)

[(Vim indent error インデント エラー)](https://simpledancer.hatenablog.com/entry/2017/06/04/%E3%82%A4%E3%83%B3%E3%83%87%E3%83%B3%E3%83%88%E3%81%AE%E3%82%A8%E3%83%A9%E3%83%BCInconsistent_indentation%E3%82%92%E8%A7%A3%E6%B1%BA%E3%81%99%E3%82%8B)

[(tips2)]()
