1. /dev/sdaはHDDとのインターフェースである。HDDの情報を
取得するコマンドhdparmを用いて，以下を調査せよ．
`sudo hdparm -I /dev/sda`
A.  1セクタ当たりの容量（byte）
- 512bbyte
B. HDDの容量（Mbyte, M=1000x1000）
- 32212MByte
C. HDDがサポートしている転送モードと現在の転送モード
PIO，DMA（sdma, mdma, udma），*付きが現在の転送モード
13.1.2.2. Direct Memory Access (DMA) Modes - PC Hardware in a Nutshell, 3rd Edition
[Book] (oreilly.com)
- サポートしている転送モード
  - pio0,1,2,3,4
  - mdma0,1,2,udma0,1,2,3,4,5
- 現在の転送モード
  - udma6
D. cycle time（ns）
- 120
E. セクタの位置を表す方式
- CHS
  - current
- LBA,LBA48
  - user

2. このPCのCPUのモデル名，最大動作速度を調べよ．

モデル名
- 13th Gen Intel(R) Core(TM) i5-13400
最大動作速度
- 2496[MHz]

