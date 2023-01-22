# Build guide

## Parts list


| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|番号|名前|数|備考|調達先|参考価格（送料込）|<br>
|1|PCB|2|40%splite keyboard|[elecrow](https://www.elecrow.com)<br>[JLCPCB](https://jlcpcb.com)<br>[ALLPCB](https://www.allpcb.com)|５枚で10〜20ドル|<br>
|2-1|Switch Plate1<br>スイッチプレート1|2|アクリル<br>[Plate data](https://github.com/telzo2000/cool536/tree/main/case_design)|[工房Emerge+](https://www.emergeplus.jp/laser-cutting-service/contact/)<br>[遊舎工房](https://yushakobo.jp)<br>[elecrow](https://www.elecrow.com)|種類による。|
|2-2|Switch Plate2<br>スイッチプレート2|2|↑|↑|↑|
|2-3|Switch Plate3<br>スイッチプレート3|2|↑|↑|↑|
|2-4|Cover Plate<br>カバープレート|2|↑|↑|↑|
|2-5|Bottom Plate<br>ボトムプレート|2|↑|↑|↑|
|3|M2screw<br>M2ネジ|26|3mm<br>BottomPlate(20)とCoverPlate(6)で使用|DIYショップなど|10本で100円程度|
|4|M2screw<br>M2ネジ|6|8mm<br>BottomPlateで使用|↑|↑|
|5A|M2screw<br>M2ネジ|22|8mm<br>MXスイッチ使用時SwitchPlate1・2で使用|↑|↑|
|5B|M2screw<br>M2ネジ|22|5mm<br>chocスッチ使用時SwitchPlate1・2で使用|↑|↑|
|6A|M2spacer<br>M2スペーサー|50|3mmメス-メス<br>MXスイッチ使用時|[ヒロスギネット](https://www.hirosugi-net.co.jp/shop/c/c10/)<br>[遊舎工房](https://yushakobo.jp)|20本で800円程度|
|6B|M2spacer<br>M2スペーサー|28|3mmメス-メス<br>chocスイッチ使用時|[ヒロスギネット](https://www.hirosugi-net.co.jp/shop/c/c10/)<br>[遊舎工房](https://yushakobo.jp)|20本で800円程度|
|7|M2spacer<br>M2スペーサー|6|8mmメス-メス<br>CoverPlateで使用|[ヒロスギネット](https://www.hirosugi-net.co.jp/shop/c/c10/)<br>[遊舎工房](https://yushakobo.jp)|20本で800円程度|
|8A|Swith socket<br>スイッチソケット|38|cherry MX互換|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|10個で165円程度|
|8B|Swith socket<br>スイッチソケット|38|choc互換|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|10個で165円程度|
|9|Diode<br>ダイオード|39|リードタイプでもSMDでも可|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|10|AZ-CORE|1|whiteでもBlackでも可|[パレットシステムAZ-CORE](https://booth.pm/ja/items/3985327)<br>[パレットシステムAZ-CORE BLACK](https://booth.pm/ja/items/4086382)|9500円|
|11|PAnda_micro|2||[パレットシステムPada_micro](https://booth.pm/ja/items/3959822)|500円〜|
|12|AZ1UBALL|0〜2||[パレットシステムAZ1UBALL](https://booth.pm/ja/items/4202085)|2500円|


In addition, you will need a TRRS cable, keycaps, etc.
<br>
この他に、TRRSケーブル(通常１本)、キーキャップ等が必要です。

<br>

## Firmware

###  AZTOOL
[Here](https://github.com/palette-system/aztool)

<br>

## Build 1(PCB only)

### 1 Parts check

The cool536azcore2 is a PCB that uses both the front and back sides for left and right PCBs.
<br>
cool536azcore2は左右のPCBに対して、表裏両面を使用するPCBです。
<br>


### 2 Diode soldering


Solder the diodes to the back of each of the left and right.
<br>
左右それぞれの裏面にダイオードのハンダ付けをします。
<br>

There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>
However, those who adopt the choc switch should use SMD diodes.
<br>
ただし、chocスイッチを採用する人は、SMDのダイオードを使用してください。
<br>


Use a lead bender to bend the legs of the diode.
<br>
リードベンダーを使い、ダイオードの足を曲げます。
<br>


Insert the diode into the board.
<br>
ダイオードを基板に挿しこみます。
<br>

Please pay attention to the orientation of the diode.
<br>
ダイオードの向きに注意してください。
<br>


Secure the diode with masking tape, then face up.
<br>
マスキングテープでダイオードを固定してから、表面を上にします。
<br>
Solder the protruding legs.
<br>
はみ出ている足部分に、ハンダ付けをします。
<br>
After soldering, use nippers to cut off the protruding legs.
<br>
はんだ付けが終わったら、はみ出ている足をニッパーで切り取ってください。
<br>

[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)


<br>
<br>

### 3 Soldering switch sockets

Notice <br>
A switch socket cannot be attached to the place where AZ-CORE is placed.
<br>
AZ-COREを置く場所にはスイッチソケットをつけることができません。
<br>
<br>
Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>
cool536azcore2 is compatible with both choc and cherry MX switches.
<br>
cool536azcore2はchocスイッチとcherryMXスイッチの両方に対応しています。
<br>
Both can be installed.
<br>
両方を取り付けることが可能です。
<br>
Here, solder the cherryMX switch.
<br>
ここでは、cherryMXスイッチのハンダ付けを行います。
<br>
Place the switch socket on the white frame.
<br>
白枠に、スイッチソケットを乗せてください。
<br>
That is the correct switch socket orientation.
<br>
それが正しいスイッチソケットの向きになります。
<br>
Place the switch socket on the white frame in the same way for the choc switch.
<br>
chocスイッチの時も同じように、白枠にスイッチソケットを乗せてください。
<br>

Apply solder to both pads.
<br>
両方のパッドにハンダを盛ります。
<br>
Place the switch socket and fix it with a warm soldering iron while melting the solder.
<br>
スイッチソケットを乗せて、温めたハンダゴテで、ハンダを溶かしながら、固定します。
<br>
You can make it easier by working while holding it with tweezers.
<br>
ピンセットで押さえながら、作業をすると楽にできます。
<br>

[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)

<br><br>

### 4　Soldering 7pins 


The connection between AZ-CORE and cool536azcore2 is done with 7 pins.
<br>
AZ-COREとcool536azcore2との接続は、7本のピンで行います。
<br><br>
Cut the pin and adjust the length.
<br>
ピンをカットして、長さを調整してください。

![](img/img00025.jpg)
![](img/img00026.jpg)
![](img/img00027.jpg)

When attaching AZ-CORE to the right side, insert the pin from the bottom and solder it as shown in the image below.
<br>
AZ-COREを右側に付けるときは、下の画像のように、下からピンを差し込み、はんだ付けをしてください。
<br>
![](img/img00028.jpg)

When attaching AZ-CORE to the left side, insert the pin from the bottom and solder it as shown in the image below.
<br>
AZ-COREを左側に付けるときは、下の画像のように、下からピンを差し込み、はんだ付けをしてください。
<br>
![](img/img00030.jpg)

By doing this, the power supply of AZ-CORE will be on the outside, making it easier to operate.
<br>
この向きにすることで、AZ-COREの電源が外側になり、操作しやすくなります。
<br>
<br>

### 5 Rotery Encoder

cool536azcore2 can have 2 switches and 1 rotary encoder on the side without AZ-CORE.
<br>
cool536azcore2では、AZ-COREを付けない側に、スイッチ２つとロータリーエンコーダー１つを付けることができます。
<br>
<br>
If you had a combination of cool536azcore1 on one side and cool536azcore2 on the other, you wouldn't need this story.
<br>
もしも、あなたが片方にcool536azcore1と、もう片方にcool536azcore2の組み合わせをした場合、この話は不要です。
<br>
![](img/img00031.jpg)


###  6　Panda_micro 

cool536azcore requires panda_micro on each side.
<br>
cool536azcoreは左右それぞれにPanda_microが必要となります。
<br>
Install the panda_micro with the TRRS jack facing up.
<br>
panda_microのTRRSジャックが上に向くようにして、取り付けをします。
<br>
Pay attention to the orientation of the conthrough.
<br>
コンスルーの向きに注意してください。
<br>
<br>
When using AZ1UBALL, please divide the 12-pin cons through into 3 equal parts.
<br>
AZ1UBALLを使う場合、12ピンのコンスルーを３等分してください。
<br>
One is for Panda_micro.
<br>
１つはPanda_microに使います。
<br>
The remaining two are used for AZ1UBALL.
<br>
残り２つはAZ1UBALLに使います。

<br>

### 5　Test

Please write the firmware and check the operation.
<br>
ファームウェアを書き込んで、動作確認をしてください。
<br>


## Firmware

###  AZTOOL
[Here](https://github.com/palette-system/aztool)

<br>

### cool536azcore <--> AZ-CORE
[Here](https://github.com/telzo2000/cool536azcore/blob/main/aztool_for_cool536azcore.md)

<br>


### 6 Installation of key switch

Attach your favorite key switch.
<br>
好きなキースイッチを取り付けてください。
<br>

<br>
If you like, attach a rubber cushion to the back and you're done.
<br>
お好みで裏面にラバークッションを取り付けたら、完成です。
<br>
<br>
<br>


### OPtion  Installing Trackball(AZ1UBALL)

You can install the AZ1UBALL on either the left or right side.
<br>
左右どちらでも、AZ1UBALLを取り付けることができます。
<br>
<br>
At that time, solder the 4 jumpers on the front side (upper side) of the PCB where AZ1UBALL is attached.
<br>
その時は、AZ1UBALLを取り付けるPCBの表側（上面）のジャンパー４箇所をハンダで繋いでください。
<br><br>

![](img/img00019.jpg)


![](img/img00032.png)


<br>
<br>


## Build 2(Acrylic sandwich mount case)


After 1 ~ 5 of build1, please do the next step.
<br>
build1の5の後、次の工程をしてください。
<br>

### 1-1 Installation of switch plate（choc switch）

The switch plate consists of three parts, the thumb and fingers, and the outer part.
<br>
スイッチプレートは親指と他の指、外側に分かれて、３つで構成されています。
<br><br>
Prepare switch plates (3 pieces), M2 spacers 3 mm (11 pieces), and M2 screws 5 mm (11 pieces).
<br>
スイッチプレート（３枚）、M2スペーサー３mm（11本）、M2ネジ５mm（11本）を用意します。
<br><br>
Fix the screws in 11 places.
<br>
ネジを11箇所、固定します。
<br>
Insert the screws in the order of the switch plate and the PCB, and fix them with spacers on the back of the PCB.
<br>
ネジはスイッチプレート、PCBの順でさしこみ、PCBの裏面でスペーサーで固定します。
<br>

<br><br>

### 1-2 Installation of switch plate（cherry MX switch）

The switch plate consists of three parts, the thumb and fingers, and the outer part.
<br>
スイッチプレートは親指と他の指、外側に分かれて、３つで構成されています。
<br><br>

Prepare a switch plate, M2 spacer 3 mm（x22）, and M2 screw 8 mm（x11）.
<br>
スイッチプレート、M2スペーサー３mm（22本）、M2ネジ８mm（11本）を用意します。
<br>
Fix the screws in 11 places.
<br>
ネジを11箇所、固定します。
<br>
Insert the switch plate into the screw and fix it with a spacer.
<br>
ネジはスイッチプレートをさしこみ、スペーサーで固定します。
<br>

![](img/img00009.jpg)


Next, insert the switch plate into the PCB and secure it with a spacer on the back of the PCB.
<br>
次に、スイッチプレートをPCBにさしこみ、PCBの裏面でスペーサーで固定します。
<br>

### 1-3 AZ-CORE

When placing AZ-CORE, there is no need for a switch plate.
<br>
AZ-COREを置く場合、そこにはスイッチプレートは不要となります。
<br>
![](img/img00034.jpg)

Pass the 5mm M2 screws (4) from the top through the holes in the PCB, and tighten the 3mm M2 spacers (4) from the bottom.
<br>
上からM2ネジ5mm（４本）をPCBの穴に通して、下からM2スペーサー3mm（４本）で締めてください。
<br>
<br>
I think that double-sided tape is good for fixing AZ-CORE.
<br>
AZ-COREの固定には、両面テープが良いと思います。
<br><br>

### 2 Installation of bottom plate 

Prepare the bottom plate,M2 spacer 3 mm（x３）,M2 ３mm screws（x11） and M2 8mm screws(x3).
<br>
ボトムプレート、M2スペーサー3mm（３本）、M２ネジ３mm(11本）、M２ネジ8mm（３本）を用意します。
<br>
Place the bottom plate according to the spacer on the back of the PCB and fix it with screws.
<br>
PCB裏面にあるスペーサーに合わせて、ボトムプレートをのせて、ネジで固定します。
<br>
However, 8mm screws and spacers are used for the part that connects to the cover plate fixing.
<br>
ただし、カバープレート固定に繋がる部分は、8mmネジとスペーサーを使います。

![](img/img00015.jpg)

![](img/img00016.jpg)

![](img/img00017.jpg)

### 3 Installation of cover plate

Prepare a cover plate, M2 spacer 8mm（x3）, and M2 screw 4mm（x6）.
<br>
カバープレート、M2スペーサー8mm（3個）、M2ネジ3mm（6本）を用意します。
<br>
Screw the spacer to the cover plate in the same orientation.
<br>
カバープレートに同じ向きで、スペーサーをネジで固定します。
<br>

![](img/img00012.jpg)

![](img/img00013.jpg)

Then attach the cover plate to the PCB by adjusting the screw on the bottom plate side.
<br>
次に、ボトムプレート側のネジを調整して、カバープレートをPCBに取り付けます。
![](img/img00018.jpg)

<br>
There is an orientation of the cover plate, so it is good to check it once before starting work.
<br>
カバープレートの向きがあり、作業前に一度、重ねて確認すると良いです。
<br>
<br>
A special cover plate is required when installing AZ1UBALL.
<br>
AZ1UBALLを取り付けているとき、専用のカバープレートが必要となります。
<br><br>


<br>
From here, proceed with step 6 of build1.
<br>
ここからは、build１の６の工程を進めてください。
<br>

Have a fun selfmade keyboard life!
<br>
楽しい自作キーボード生活を!

![](img/img00033.jpg)
