```
Arduino® VENTUNO™ Q
```

User Manual SKU: ABX00181 



<!-- Start of picture text -->
‘or ee fee<br>AE & ie 5 gms Be<br><!-- End of picture text -->

# **`English`** 

### **`Description`** 

Arduino® VENTUNO™ Q is a high-performance edge AI computer designed specifically for next-gen AI and robotics. By seamlessly bridging industrial-grade computing with real-time actuation, VENTUNO Q gives you the processing power to deploy complex AI models and the precision control to manipulate the physical world, all from a single, compact edge device. 

At its core lies a revolutionary Dual-Brain architecture: the robust Qualcomm Dragonwing™ IQ8 (QCS8275) Microprocessor (MPU) delivers up to 40 dense TOPS of AI compute for advanced computer vision and local LLMs running a full Ubuntu Linux OS (Debian also supported), while the dedicated STMicroelectronics STM32H5F5 Microcontroller (MCU) running Arduino Core on Zephyr OS ensures the low-latency precision required for complex motor control and robotics. 

VENTUNO Q allows you to remain connected and ready to deploy. It features integrated Wi-Fi® 6 (Tri-band) and Bluetooth® 5.3 connectivity, alongside a comprehensive suite of built-in connectors, including high-speed USB 3.0, HDMI, 2.5 Gb Ethernet, and an M.2 connector for expandable NVMe Gen 4 storage. The board supports the vast ecosystem of Arduino UNO shields natively, as well as Raspberry Pi® HATs via a 40-pin header, and Arduino® Modulino™ nodes via Qwiic connector. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**1 / 62** 

```
Arduino® VENTUNO™ Q
```

### **`Target Areas`** 

Edge AI, Local LLM/VLM, Smart Home, Robotics, Motion Control, Smart City, Industrial Vision, Education & Research 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**2 / 62** 

```
Arduino® VENTUNO™ Q
```

# **`CONTENTS`** 

|**1 Application Examples**|**5**|
|---|---|
|**2 Features**|**6**|
|2.1 VENTUNO Q Variants|6|
|2.2 General Specifications Overview|6|
|2.2.1 Processing & Memory|6|
|2.2.2 Connectivity & Media|7|
|2.2.3 Expansion & Headers|8|
|**3 Ratings**|**9**|
|3.1 Input Power|9|
|3.2 Recommended Operating Conditions|10|
|3.3 On-Board Voltage Rails|11|
|3.4 Typical Power Consumption|12|
|3.4.1 Typical Power Consumption - 12 V DC|12|
|3.4.2 Typical Power Consumption - 24 V DC|12|
|3.4.3 Typical Power Consumption - USB-C® PD (20 V)|12|
|**4 Functional Overview**|**13**|
|4.1 Pinout|13|
|4.2 Block Diagram|14|
|4.3 Power Supply|17|
|**5 UI & Indicators**|**21**|
|**6 MPU & MCU**|**23**|
|6.1 Application Processor (MPU)|23|
|6.2 Real-Time Microcontroller (MCU)|23|
|**7 Inter-Processor Communication**|**24**|
|**8 Hardware Acceleration**|**25**|
|8.1 AI Acceleration (NPU)|25|
|8.2 Graphics Acceleration (GPU)|25|
|8.3 Video Acceleration (VPU)|26|
|**9 Peripherals & Headers**|**27**|
|9.1 JANALOG|27|
|9.2 JDIGITAL|28|
|9.3 JSPI|29|
|9.4 Qwiic|29|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**3 / 62** 

```
Arduino® VENTUNO™ Q
```

|9.5 JCTL (MPU Remote Debug)|30|
|---|---|
|9.6 JHAT|31|
|9.7 JMISC|33|
|9.8 JMEDIA|35|
|9.9 JOMEGA|37|
|9.10 MIPI CSI Camera Connectors (J3_1, J3_2, J3_3)|39|
|9.10.1 J3_1 - Camera 2|40|
|9.10.2 J3_2 - Camera 0|40|
|9.10.3 J3_3 - Camera 1|41|
|**10 High-Speed Peripherals**|**42**|
|10.1 Networking|42|
|10.2 Storage|42|
|10.3 USB-C|42|
|10.4 USB Type-A|43|
|10.5 Display|44|
|10.6 Camera|44|
|**11 Device Operation**|**45**|
|11.1 Getting Started - Arduino App Lab|45|
|11.2 Bricks|46|
|11.3 Buttons & Boot Modes|46|
|11.4 Vertical Pushbutton|47|
|11.5 User Button|48|
|**12 Mechanical Information**|**49**|
|12.1 SoM Heatsink & Thermal Design|50|
|**13 ESD Warning**|**55**|
|**14 Antenna Use and Compliance**|**55**|
|14.1 Warning - External Antenna Use|55|
|14.2 Requirements for Integrators|56|
|14.3 Operation in the 6 GHz Band|56|
|14.4 Responsibility|56|
|**15 RED / UK**|**56**|
|15.1 Radio Equipment Information (RED Compliance)|58|
|**16 UKCA Declaration of Conformity**|**58**|
|**17 FCC**|**58**|
|**18 ISED**|**60**|
|**19 Trademarks**|**61**|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**4 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`1 Application Examples`** 

VENTUNO Q combines an AI-capable Linux processor with a real-time microcontroller, delivering the best of highlevel computing and deterministic control. It is specifically designed for makers and developers who want AI that can directly shape the physical world. 

- **AI Assistants & Smart Home:** Build offline voice assistants, local agentic hubs, touchless interface kiosks, and real-time speech translators. 

- **Robotics & Motion Control:** Autonomous Mobile Robots (AMRs) using Visual SLAM, vision-guided manipulators, and companion & service robots. 

- **Smart City & Industrial Vision:** Edge traffic monitors, automated quality inspection on assembly lines, 

- proactive site security, and vision-based inventory monitoring. 

- **Education & Research:** Advanced AI learning kits, rapid research prototyping, voice-based coding assistants, and mobile manipulation research platforms. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**5 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`2 Features`** 

#### **`2.1 VENTUNO Q Variants`** 

VENTUNO Q is available in one variant: 

**ABX00181** : 16 GB LPDDR5 RAM, 64 GB eMMC storage 

#### **`2.2 General Specifications Overview`** 

#### **`2.2.1 Processing & Memory`** 



<!-- Start of picture text -->
<a eh@ cet ancrin Son@ Me a<br>ee ewwes IAB teoat oe eensee a fx:a A‘ ae egg ies<br>rome HE GTE oeeeE “Bet. fg. ee<br>ie+) Sere| 135Seo ee: ire:ee Byee bia pa4<br>He |: am he o*% z | a3: Atte a<br>: A! scees fl e 0, o's<br><!-- End of picture text -->

|**Subsystem**|**Details**|
|---|---|
|Main MPU|Qualcomm Dragonwing™ IQ8 (QCS8275)|
||CPU: Octa-core Arm® Cortex®|
||Adreno™ 623 GPU (3Dgraphics & OpenCL)|
||Adreno™ VPU 623 (Videoprocessing)|
||Hexagon™ Tensor AI Processor (NPU): upto 40 dense TOPS|
||Qualcomm Spectra 692 ISP|
||Ubuntu Linux OS (Debian also supported)|
|Real-time MCU|ST STM32H5F5 (MCU), Arm® Cortex®-M33 upto 250 MHz|
||Arduino Core on Zephyr OS|
||4 MB Flash, 1.5 MB RAM|
|System Memory|eMMC 64 GB for OS/data|
||OSPI SAIL Memory(MX25UW25345GXDI00-TR) for MCU boot/shared data|
||M.2 KeyM 2230 connector for NVMe Gen 4 storage (PCIe x4 direct from SOM, non-bootable)|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**6 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Subsystem**|**Details**|
|---|---|
||2x8 GB LPDDR5 RAM (16 GB total)|



#### **`2.2.2 Connectivity & Media`** 



<!-- Start of picture text -->
L Bratt @ ic itlanSarin “n@)| Bre Al Peae ET -)<br>Feet Ale = {] = iit AN = se<br>- 4{ mti 1 a, GSSSssa 1 ed at ° OL o's_<br>EX<br>Pa<br><!-- End of picture text -->

|**Subsystem**|**Details**|
|---|---|
|Network &<br>Wireless|Wi-Fi® 6 2.4/5/6 GHz (Tri-band) with 2x onboard antennas (NFA725B module)|
||Bluetooth® 5.3 with onboard antenna|
||1x 2.5 Gbit RJ45 Ethernet (QCA-8081 PHY)|
|USB Connectors|1× USB-Cport with host/device role switching,power role switch and video output|
||2x USB 3.0 Type A|
||2x USB 3.0 on JOMEGA header|
|Video|1x HDMI output via onboard ADV7535 DSI-to-HDMI bridge. HDMI and MIPI DSI share|
||the same DSI lines, when HDMI is active, MIPI DSI on JMEDIA header is muxed out|
||Video output (DP Alt mode) via USB-C|
|Camera|3x MIPI CSI connectors on board (J3_1, J3_2, J3_3)|
||2x MIPI CSI lanes also available on JMEDIA header (muxed with onboard connectors)|
||USB camera support via USB Type-A or USB-C|
|Audio|Audio Codec: MAX98091ETM+T (Maxim)|
||On JMISC: 1x LINE OUT mono, 1x SPEAKER OUT mono, 1x HEADPHONES OUT stereo, 1x MIC<br>IN|
||On JOMEGA: 1x MIC IN|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**7 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Subsystem**|**Details**|
|---|---|
|CAN Interfaces|1x CAN-FD with PHY (ATA6563-GBQW1) on screw terminal, driven byMCU (STM32H5F5)|
||CAN-H and CAN-L lines are TVS-protected (PJGBLC24C-AU_R1_000A1, bidirectional, 24 V, 350<br>W)|
||Onboard split termination on screw terminal CAN bus (2× 60.4 Ω + 100 nF)|
||3x CAN-FD (no PHY) on JOMEGA header,pin-muxed via MCU|
||1x CAN-FD (no PHY) on UNO Shield headers (D4/D5),pin-muxed via MCU|



📝 **Note:** The CAN bus on the screw terminal includes onboard split termination (2× 60.4 Ω + 100 nF). If the board is not at the end of the bus, this termination should be considered when designing the network topology. 

#### **`2.2.3 Expansion & Headers`** 

|**Interface**<br>**(Connector)**|**Details**|
|---|---|
|UNO Shield Headers|- Compatible with standard Arduino UNO Shields (3.3 V logic)|
||- Most digital pins are 5 V-tolerant. A0 and A1 on JANALOG are direct ADC inputs and are<br>not 5 V-tolerant|
|Expansion Header<br>(JOMEGA)|- Extensive expansion capabilities including USB 3.0, CAN-FD, JTAG, MIC IN, MPU SPI|
|Carrier Headers|- JMEDIA: MIPI CSI0/CSI1 camera lanes and MIPI-DSI displaylanes at 1.8 V|
||- JMISC: audio endpoints, MPU GPIO at 1.8 V and MCU signals at 3.3 V|
|Qwiic Connector|- I2C (3.3V) connected to MCU for instantplug-and-playaccess to Modulino® nodes|
|JHAT connector|- Raspberry Pi® compatible 40-pin header (MPU GPIO, level-translated to 3.3 V for HAT<br>compatibilityvia TXS0108ERKSR and TXS0104ERUTR)|
|JCTL (MPU Remote<br>Debug)|- 10-pin (2×5) header for MPU remote debugging, compatible with Arduino Bughopper|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**8 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`3 Ratings`** 

#### **`3.1 Input Power`** 

|**Source**|**Voltage Range**|**Maximum Current**|**Connector**|
|---|---|---|---|
|USB-C PD|20 V|upto 3 A|USB-C connector|
|Barrel Jack (5.5×2.1 mm)|12-24 V|upto 5 A|5.5×2.1 mm Barrel Jack|
|Screw Terminal|7-24 V|upto 10 A|Screw Terminal|





<!-- Start of picture text -->
a | ee, hea y r Po paesa a! ge<br>j cod Fe— |<br>fel (2! (2) ————— ae<br>ez,<br>1c Power Supply Input: 12 ~ 24<br>(BhoDc Powerrove supaySupply Input:toa 7 ~ 24 vDC<br><!-- End of picture text -->

_Input Power Options_ 

Both input paths are TVS-protected (SMBJ24CA, 24 V bidirectional) and route through independent power switches (KTS1900GXAA-TA + SQS414CENW-T1_GE3) to a current-sensing stage (INA232AIDDFR). Two multi-phase buck converters (MPQ4371GVE-1001-AECC901-Z) generate the main 3.3 V rail, while another buck converter (MPQ4371GVE-1001-AECC901-Z) generates the 5 V rail. The USB-C® PD controller (CYPD6129-52LQXI) negotiates voltage profiles up to 20 V from compatible USB-C® power supplies. 

📝 **Note on DC input current and power budgeting:** The barrel jack connector is rated for a maximum of 5 A. The available power budget depends on input voltage: at 7 V (5 A) the maximum deliverable power is 35 W; at 12 V it is 60 W; at 24 V it is 120 W. Under worst-case conditions with the MPU, NPU and GPU running simultaneously at full performance, the SoM alone can draw approximately 23-25 W. The entire board including the Ethernet PHY, audio codec, USB hub and other on-board ICs will draw more, leaving limited headroom at 7 V before reaching the connector's limit. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**9 / 62** 

```
Arduino® VENTUNO™ Q
```

When powering the board at 7 V be sure to keep into account cable drop, since the board requires a minimum of 7 V at its connectors and will not switch on with a voltage lower than 7 V. 

The two USB Type-A ports can each deliver up to 5 V × 1.71 A = 8.55 W, for a combined maximum of ~17 W additional draw. With the board at full power and both USB-A ports at maximum load, total draw can approach 42 W, exceeding the 35 W limit of the DC jack at 7 V and risking connector damage. 

**Operating at 12 V or 24 V is strongly recommended** for any deployment involving AI inference, USB peripherals and connected shields or HATs simultaneously. 

For heavy workloads involving AI inference, USB peripherals or expanded applications, a power supply rated for **60 W or greater** is recommended across all power sources to make sure operation stays stable during possible peak consumption. When using the **barrel jack** (5.5×2.1 mm, max 5 A), a supply of **12 V / 5 A or 24 V / 3 A** is recommended as an example. 

#### **`3.2 Recommended Operating Conditions`** 

|**Parameter**|**Symbol**|**Minimum**|**Typical**|**Maximum**|**Unit**|
|---|---|---|---|---|---|
|USB-C PD input|VUSBC|-|-|20.0|V|
|DC input (Screw Terminal)|VIN|7.0|-|24.0|V|
|DC input (Barrel Jack)|VIN|12.0|-|24.0|V|
|5.0 V rail (output)|V+5V|4.75|5.0|5.25|V|
|3.3 V rail (output)|V3P3|3.14|3.3|3.47|V|
|Operating temperature|TOP|-10|-|60|°C|



📝 **Note:** The USB-C® PD controller supports multiple voltage profiles (9 V, 15 V, 20 V) when connected to a PD-capable power supply. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**10 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`3.3 On-Board Voltage Rails`** 

|**Voltage**|**Rail**|**Origin/Regulator**|
|---|---|---|
|7-24 V|VIN|Jack/screw terminal input (TVS protected, SMBJ24CA)|
|5.0 V|+5V|MPQ4371GVE buck converter|
|3.3 V|+3V3|2x MPQ4371GVE buck converters|
|1.8 V|SOM_VREG_MDPX3_1P8|SOM main application domain 1.8 V rail (user-accessible via JMISC, JCTL)|
|1.8 V|SOM_VREG_S5S_SPX3_1P8|SOM safetysubsystem (RTSS) domain only, not forgeneral use|
|1.8 V|+1V8|MPQ2179GQHE buck converter (for on board ICs QCA8081, ADV7535,<br>MAX98091)|
|1.28 V|+1.28V|MP20312GTF LDO (for audio codec MAX98091)|
|1.1 V|+1V1|MPQ2179GQHE buck converter (for on board ICs TUSB7340RKMR,<br>QCA8081 and PI7C9X2G304EV)|



📝 **Note:** The board features three independent 1.8 V rails. `SOM_VREG_MDPX3_1P8` is the QCS8275 SoM main application domain rail and is the recommended reference for all user-accessible 1.8 V interfaces including JMISC and JCTL. `SOM_VREG_S5S_SPX3_1P8` is the SoM safety subsystem (RTSS) domain rail and should not be used as a general-purpose supply or reference. `+1V8` is the board-level 1.8 V rail generated by the MPQ2179GQHE buck converter, supplying the QCA-8081 Ethernet PHY, the ADV7535 display bridge and the MAX98091 audio codec. 

📝 **Note:** Separately from the rails above, JMISC pin 59 accepts an RTC backup battery up to 3.3 V to maintain the SOM and MCU real-time clocks when the board is otherwise unpowered. `SOM_VCOIN` (SOM RTC) and `VBAT` (MCU RTC) are two RTC backup battery inputs that are physically tied together at this single pin, rather than a shared power rail. Each connects through its own 0 Ω resistor to a common node, which is protected by a bidirectional TVS diode (Vr = 5.5 V) referenced to ground. The expected current draw is very low, and this pin does not supply power to keep the rest of the board on. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**11 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`3.4 Typical Power Consumption`** 

The following measurements are based on ambient temperature of 24.4°C, using a power analyzer, across three power input methods of 12 V DC, 24 V DC and USB-C® PD at 20 V. Blink on MCU, Hello World on MPU, Edge AI Assistant and Detect Objects on Smartphone Camera are available as built-in examples within Arduino App Lab. The Smart Mirror example is based on a dedicated application note. 

#### **`3.4.1 Typical Power Consumption - 12 V DC`** 

|**Scenario**|**Average Power**|**Min Power**|**Max Power**|
|---|---|---|---|
|Booting|7.07 W|–|17.9 W|
|Blink on MCU|7.42 W|5.30 W|12.6 W|
|Hello World on MPU|7.52 W|5.32 W|13.3 W|
|Edge AI Assistant|13.5 W|6.13 W|24.6 W|
|Smart Mirror example¹|14.7 W|7.65 W|33.0 W|
|Detect Objects on Smartphone Camera|9.63 W|5.80 W|21.2 W|



#### **`3.4.2 Typical Power Consumption - 24 V DC`** 

|**Scenario**|**Average Power**|**Min Power**|**Max Power**|
|---|---|---|---|
|Booting|9.71 W|–|23.7 W|
|Blink on MCU|10.6 W|7.04 W|18.9 W|
|Hello World on MPU|10.8 W|7.09 W|18.3 W|
|Edge AI Assistant|15.5 W|7.44 W|28.8 W|
|Smart Mirror example¹|17.3 W|8.47 W|36.6 W|
|Detect Objects on Smartphone Camera|11.5 W|7.88 W|24.7 W|



#### **`3.4.3 Typical Power Consumption - USB-C® PD (20 V)`** 

|**Scenario**|**Average Power**|**Min Power**|**Max Power**|
|---|---|---|---|
|Booting|6.56 W|–|20.2 W|
|Blink on MCU|7.84 W|6.33 W|16.1 W|
|Hello World on MPU|9.68 W|6.42 W|16.1 W|
|Edge AI Assistant|15.3 W|6.61 W|25.6 W|
|Smart Mirror example¹|15.1 W|8.05 W|34.2 W|
|Detect Objects on Smartphone Camera|11.3 W|7.85 W|23.1 W|



¹ Smart Mirror test setup: Logitech BRIO 4K USB camera, USB headset (microphone and speakers) and an HDMI display connected. 

📝 **Note:** Measurements were taken using an Otii Ace Pro power analyzer for reference. The highest peak recorded across all scenarios and input sources was 36.6 W (Smart Mirror example at 24 V DC), within the 60 W or greater power supply recommendation above. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**12 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`4 Functional Overview`** 

#### **`4.1 Pinout`** 



<!-- Start of picture text -->
=>= © .08 ore coste carat<br>4<br>ona rearieaD wens SRE<br><=. : j a 4 es<br>Soom: : Cae aacon? ie<br>- i<= is a aes:<br>nue<br>om oo<br>sin<br>vss e toc<br>SamSeanSeeimseeae , @ 7 L_] <=<br>Se ns ell on<br>Siem toes 30 Om we<br>Sm8<br>Sas ee f ,<br>oon ame e° a j e<br>=. i eco ce<br>Sem ess<br>28 om camer eon ae ~ wee GED me So“W8 vOCtacoma.Sppping io<br>cas beret ==<br>Legend: MM vigitar = 12c Clother serra (oo)<br>Mipower [1] Analog © ser MH Analog inane<br>Wi cround Main Part i UART/USART Internal Part cant eon tate<br><!-- End of picture text -->

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**13 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`4.2 Block Diagram`** 



_Complete Overview of Block Diagram_ 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**14 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
Creanaaneatment<br>Caramea) Audie codec en<br>aaron eR) —|_MANDAWOTETRET uaa) CT ea<br>eS . ex<br>— (<br>“(CONTSC) (orst ><br>a)<br>=<br>am<br>==.<br>Coesma—<)wo)<br>><br>JANALOGeet re)UNO Female ——=, stws2HsFSLJH7a<br>om Merocgncite) scatter<br>—a—><br>am<br>za a=» [nnenicorse oie)<br>Gz rar-coummeanea ve<br>Lrsr-cammpeeitn (ota) 9 nD<br>:| rer-anlietsth (208.2)(us.0) og depnenaranxEEasco<br>eget: comctar— Blystonon eane (ute) uscras Dour eo<br>fain Part mi eanrsvsanr mor att<br>Iesernat Part Blaney 70 Diteservae ae<br><!-- End of picture text -->



<!-- Start of picture text -->
Block Diagram (Page 1/2)<br><!-- End of picture text -->

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**15 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
ccc)rem) Crocenae non)<br>—_cT) —_i)a) JONEGA Fenale<br>Gaim) eSEC202-s002K001C1AF<br>Cis0"3.0, FORTS) GY)<br>“mmm<br>< exura=<br>(oxen az) pa e xcrEu=»x<br>WisFie 6 (Trh-Bend) on<br>Bivetodthe eS) rete<br>‘weavasn (uta) Torstente use 9.0 coerceane eeexa<br>Ca 1e31-225-0-55H(800)<br>‘etesasies erssn 7 cameras<br>a Cas) ‘Tsabvedzaanuanwie) «(cis== )— JESEy<br>niet nx Fist connector<br>“uie-2) Cia<br>esti fsnressonwSe) ery<br>ee rsabvoazhonuan ont magne<br>Es CEDCC stBieto wont conversesSe—C_tt? > — angle pated<br>Gu Came tinsinee ><br>i ee wowiseadenertiafeetere(v6) uso-c<br>rn 2.560 pay ornse L GERD ©‘ us0-c v0 controtter a -! cxsou2-24Pco)<br>ee ET) C=<br>a><br>Lesend: connector MU tyaten on mogute (main) Mi ze/128 other ovo}<br>oternah Pars Ml Anatog 2/0 Ci heserves wa<br><!-- End of picture text -->

_Block Diagram (Page 2/2)_ 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**16 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`4.3 Power Supply`** 

VENTUNO Q supports two independent power input paths: a USB-C® port with Power Delivery (PD) negotiation up to 20 V, and a 7-24 V DC input via the 5.5×2.1 mm barrel jack or screw terminal. Both paths are protected by bidirectional 24V TVS and routed through a power OR of independent, reverse polarity and reverse current protected power switches (KTS1900 + 2x NMOS) before reaching the buck converters. 

A current-sensing IC (INA232AIDDFR) monitors total input current across the active path. Two multi-phase buck converters (MPQ4371GVE-1001-AECC901-Z) generate the main `+3V3` rail, which powers the SOM (QCS8275) and the board's 3.3 V peripherals. A third MPQ4371GVE buck converter generates the `+5V` rail. 

One MPQ2179GQHE buck converter generates the `+1V8` rail, supplying the QCA-8081 Ethernet PHY, the ADV7535 display bridge and the MAX98091 audio codec. One MPQ2179GQHE buck converter generates the `+1V1` rail, supplying the TUSB7340RKMR and the QCA-8081 and PI7C9X2G304EV PCIe switch. 

The SOM provides the `MDPX3_1P8` (1.8 V) main application domain rail via its internal PMIC 

( `SOM_VREG_MDPX3_1P8` ), which is user-accessible via JMISC and JCTL. The separate `SOM_VREG_S5S_SPX3_1P8` rail is dedicated to the real-time safety subsystem (RTSS). It should not be used as a general-purpose reference. An MP20312GTF LDO generates the `+1.28V` rail for the MAX98091 audio codec. 

Dedicated MP5077GG-Z load switches independently gate the M.2 NVMe slot, the `+3V3_LIMITED` rail (for UNO Shields, HATs and Qwiic) and the `+5V_LIMITED` rail (for shields and HATs). The VBUS rail for each USB Type-A port is enabled and protected by the TUSB7340RKMR. All other peripheral load switches are controlled by SOM GPIOcontrolled enable lines, allowing the MPU to power-gate unused subsystems. 



_Complete Overview of Arduino VENTUNO Q Power Tree_ 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**17 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
usec_vaus ™ our<br>CBB —sv nig<br>ee i ests oe<br>Pane Atyere |<br>: ed<br>7 = 24 06 wnditithe,,™ our 5 o ona<br>Legend: connector inputs & Pre-negutator nodes TH 7-24-v 0c Regulated MM Syston on Module [MPU Domain Distribution foro)<br>i otn pare sv, veotn,vaAT systen oistributton  1v28,v1,son orzo] sv Lintted Miers oomsin vistribution one<br>i tncerner part ava Goerd nasa Bove ent Cavs tanteee soc ie S<br><!-- End of picture text -->

_Arduino VENTUNO Q Power Tree (Page 1/3)_ 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**18 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
nyeSEER ey<br>+ sra2HSFSLIH7O,<br>ai: - > ‘our J (310) u Ve TaKT 8A<br>- «xp oraerist (Bie6)<br>En<br>Pome Switch USB-A 3.0 x2 Stacked measunasyeyare (va)<br>SSB ssc HERS<br>(AN ay<br>Mea emma we<br>‘DPROTASL, LaF (DES), i Cam—<br>Ws 24y Bidirections! Bald T5 20y siirections?<br>a PLES<br>ERE SU BRD pone<br>I<br><!-- End of picture text -->



<!-- Start of picture text -->
Arduino VENTUNO Q Power Tree (Page 2/3)<br><!-- End of picture text -->

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**19 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
‘OM. VREG_MDPX3_1P! JeTL Made a Ea Car<br>}0M_VREG_MDPX3_1P Ra -<br>our CAMERAS<br>rain Pare (ESV, VCOIN, VBAT System Distribution — [ 1v28,1¥1,50m GPIO sv Limited: WE RTSS domain Distribution =e<br><!-- End of picture text -->

_Arduino VENTUNO Q Power Tree (Page 3/3)_ 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**20 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`5 UI & Indicators`** 

|**Indicator**|**Type**|**Controller**|**Notes**|
|---|---|---|---|
|LED Matrix|104x blue LEDs (LTST-<br>C191TBKT-5A)|MCU via GPIO|Programmable display matrix|
|4x RGB<br>LEDs|LTST-C28NBEGK-2A|MCU via GPIO|User-addressable status indicators|
|Power LED|Green (LTST-C190KGKT)|Hardware (+3V3 rail)|Indicates +3V3 rail is active|
|Fault LED|Red (XHY-STB0603SR)|USB-C® PD controller<br>(CYPD6129, GPIO9/P4.1)|Indicates a fault condition detected by<br>the PD controller|



- **4× RGB LEDs:** Four tri-color LEDs driven by the STM32H5F5 microcontroller (MCU) via 12 individual GPIO pins (3 per LED). They are user-addressable and can be used to indicate application state, connectivity status or custom events from within an Arduino sketch. 

|**Designator**|**RGB LED**|**Red**|**Green**|**Blue**|
|---|---|---|---|---|
|DL1_1|RGB LED 1|PG3|PG6|PK2|
|DL1_2|RGB LED 2|PG4|PD10|PK1|
|DL1_3|RGB LED 3|PD11|PG5|PK0|
|DL1_4|RGB LED 4|PG2|PG8|PC6|





<!-- Start of picture text -->
= DOOPPOCOOO<br>Eeya SSASS AAAA A A A OIGLAS =Sigse [eteMA e<br>ETTwer MRR RAR ARAR A AAARA ASEA S| |<br>Oe tH IROOoAAARARARAAAA corai=<br>@ BE,URED SAAAASARAASAA9999999999999 a= f 5ie<br>soconpyHlal = SSS SSS SSANALOG © es cave r ) 7<br>Same = b= b= b= b= p= D= p= B= D= b= d= d= D> SeFits fyanyteeta<br>660 0<br>RGB LED 1 MCU PIN RGB LED 3 MCU PIN<br>oO Lek ED Oto. ED<br>© Lept.c (PG) © Levs_c | PEE)<br>@ vept.8 (PK) = @ Lev3_8 | PKB)<br>RGB LED 2 MCU PIN RGB LED 4 MCU PIN<br>oe ed<br>© tev2s PID © Lev PEED<br>© tevzs RD = @ Leva_s [PCED<br>Connected to the Microcontroller (MCU) - STM32H5F5<br><!-- End of picture text -->

- 📝 The RGB LEDs are active-low and they turn on when driven to logic `0` . 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**21 / 62** 

```
Arduino® VENTUNO™ Q
```

- **LED Matrix:** An 8×13 monochrome blue LED matrix (104 pixels) driven by the STM32H5F5 MCU. It displays the boot animation for approximately 20-30 seconds during Linux startup. Accessing the matrix before startup completes may interfere with MCU operation. 

- 📝 **Note:** The boot animation only plays when the MCU bootloader is loaded and a valid sketch is running. If it does not appear, please refer to the VENTUNO Q User Manual for more details. 



<!-- Start of picture text -->
Mae<br>HIEIEIFEEEEEIEEeS S:. q3aSsss935 35555<br>[27ce)| 26 ei20] 2620|)22 25] 24] 2s|)26 | a7] 20] 29] wn .ri| (eeRFME €<br>af [a2 | fos | 5 [0] 47 [8 [40 | sof on] 2] hee<br>[se se] s5[ so] 57 se se cof or oa] ca [oa | os] Bi Soeceessssees |<br>[ 22 | 92 | eos] v6] 97] 28 | 20 100] 101] 102] 109] 104 ini fe S59 990050 555<br><!-- End of picture text -->

- **Power LED:** Green indicator (LTST-C190KGKT) tied to the `+3V3` rail. It is illuminated whenever the board is powered. 

- **Fault LED:** Red indicator driven by the USB-C® PD controller (CYPD6129, GPIO9/P4.1). It indicates a fault condition detected by the PD controller. 



<!-- Start of picture text -->
ei EH po can-t aD)<br>tiie F|i a cnn =<br>La # to<br>Tbe &] oi<br>i) oo<br>Ee kkk b EU =: —<br>: ooZSEH ussHDMI3.0<br>° a<br><!-- End of picture text -->

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**22 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`6 MPU & MCU`** 

An MPU (Microprocessor unit) is a high-performance application processor designed to run a full operating system and complex software. An MCU (Microcontroller unit) is a small, power-efficient controller designed for fast, precise timing of I/O and control. VENTUNO Q combines both to pair OS-level compute with responsive, time-critical control on a single board, and to communicate via Bridge, an RPC layer implemented on both sides. 

#### **`6.1 Application Processor (MPU)`** 

The Qualcomm® Dragonwing™ IQ8 (QCS8275) is an Octa-core Arm® Cortex® processor running Ubuntu Linux OS (Debian also supported). Its I/O operates at 1.8 V and it handles high-speed media interfaces and AI inference. 

- Voltage domain: 1.8 V for MPU (SoC) GPIO and high-speed interfaces. 

- Drives JMEDIA: MIPI CSI camera lanes and MIPI-DSI display lanes. 

- Drives 1.8 V MPU GPIO and audio endpoints on Carrier headers (JMEDIA, JMISC). 

- USB-C: role switching managed via the CYPD6129 PD controller, which handles PD negotiation independently (supports up to 20 V profiles). 

- DisplayPort output via USB eDP MUX (TMUXHS4446RETT) on the USB-C connector. 

- Runs the Hexagon™ NPU (up to 40 dense TOPS) and Adreno™ 623 GPU for edge AI and graphics workloads. 

#### **`6.2 Real-Time Microcontroller (MCU)`** 

The STMicroelectronics® STM32H5F5 is an Arm® Cortex®-M33 running Arduino Core on Zephyr OS at 250 MHz. It provides fast, deterministic timing for robotics, motor control and general I/O. 

- Voltage domain: 3.3 V for GPIO and analog interfaces. 

- Manages ADC, PWM, LED matrix, RGB LEDs and timers. 

- Handles 3.3 V headers: JDIGITAL, JANALOG and JSPI. 

- Controls all CAN-FD interfaces: PHY on screw terminal and no-PHY ports on JOMEGA and UNO Shield headers. 

JMISC handles both domains: 1.8 V MPU lines sit alongside 3.3 V MCU signals (PSSI, I²C, GPIO) and analog audio. Always verify voltage levels when attaching carriers or external logic to JMISC. 

- 📝 **Note on VDDIO2:** The STM32H5F5 has a secondary I/O power domain (VDDIO2) powered by `SOM_VREG_MDPX3_1P8` (1.8 V). This allows specific MCU pins to communicate directly with the MPU at 1.8 V without requiring external level translators. The following interfaces operate in the VDDIO2 domain: 

   - **MCU I2C1** is used for direct MCU to MPU communication 

   - **MCU GPIOs PG9, PG10, PG11, PG12, PG13 and PG14** communicate directly with the MPU at 1.8 V 

- Do not apply 3.3 V logic to these pins. All other MCU GPIO signals operate at 3.3 V on the standard VDDIO domain. 

⚠ **Voltage Level Warning:** MPU GPIO signals operate at 1.8 V, while MCU GPIO signals operate at 3.3 V. Make sure any external connections to the expansion headers are compatible with the voltage level of their 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**23 / 62** 

```
Arduino® VENTUNO™ Q
```

respective processor domain to prevent hardware damage. 

## **`7 Inter-Processor Communication`** 

The Qualcomm® Dragonwing™ IQ8 (QCS8275) (MPU) and the STM32H5F5 (MCU) communicate through the Arduino Bridge, a software-based Remote Procedure Call (RPC) layer implemented on both the Linux and MCU sides. Bridge provides a service-oriented API that allows either processor to expose services for the other to call, while also supporting one-way notifications for asynchronous events. It manages message routing between processors and accommodates multiple physical transports. 

Through its API, Bridge enables type-safe function calls, allowing microcontroller sketches to invoke Linux services and receive structured responses or push data via notifications. 

The physical transport layer between the two processors includes the following interfaces: 

|**Interface**|**Direction**|**Purpose**|
|---|---|---|
|USB 2.0|SoC -> MCU (host)|High-bandwidth data transport|
|SWD|SoC -> MCU|Debuginterface (1.8 V to 3.3 V level-translated)|



If a hardware indicator is required for a carrier board or external logic, firmware can dedicate a 1.8 V MPU GPIO on JMISC, or an available JCTL GPIO, as a ready or wake output. This signal can be received on an MCU GPIO through level-compatible circuitry, such as a level shifter or open-drain configuration with a pull-up resistor. 

📝 MPU GPIO signals operate in the application processor's low-voltage domain (1.8 V). Make sure any connection to the microcontroller is level-compatible with its I/O voltage rail (3.3 V). For example, use a level shifter or an open-drain configuration with a pull-up to the microcontroller's I/O rail. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**24 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`8 Hardware Acceleration`** 

VENTUNO Q provides hardware acceleration for edge AI, 3D graphics and video encoding/decoding through the integrated Hexagon™ Tensor AI Processor (NPU), Adreno™ 623 GPU and Adreno™ VPU 623. 

#### **`8.1 AI Acceleration (NPU)`** 

The onboard Hexagon™ Tensor AI Processor delivers up to 40 dense TOPS (Tera Operations Per Second) of neural network compute. It allows VENTUNO Q to run Local LLMs (Large Language Models), VLMs (Vision Language Models) and complex computer vision pipelines offline. 

The NPU is integrated with the Qualcomm AI Stack and supported natively in Arduino App Lab. Developers can deploy models optimized via **TensorFlow Lite, ONNX Runtime and PyTorch** . VENTUNO Q also features direct integration with **Edge Impulse Studio** for quick training and deployment of custom edge AI models without writing boilerplate code. 

|**Component**|**Specification**|
|---|---|
|Processor|Hexagon™ Tensor AI Processor|
|Peak Performance|Upto 40 dense TOPS|
|Architecture|Hexagon DSP +quad HVX + dual HMX coprocessors|
|Supported Frameworks|TensorFlow Lite, ONNX Runtime, PyTorch|
|Integration|Qualcomm AI Stack, Arduino AppLab, Edge Impulse Studio|



#### **`8.2 Graphics Acceleration (GPU)`** 

The Adreno™ 623 GPU provides hardware-accelerated 3D graphics and general-purpose compute (GPGPU) on the QCS8275 SoM. On Qualcomm Linux, GPU acceleration is provided through Qualcomm's proprietary Adreno driver stack via the KGSL kernel driver. 

For the full GPU hardware specification refer to the QCS8275 Data Sheet (80-73475-1) and the Qualcomm Linux Graphics Guide. 

📝 **Note:** The Adreno driver libraries and firmware files are present in `/lib/firmware/` on the device. Not all GPU features listed in the QCS8275 documentation may be available in the software distributed with VENTUNO Q. Refer to the VENTUNO Q Documentation for the current list of supported features. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**25 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`8.3 Video Acceleration (VPU)`** 

The Adreno™ VPU 623 provides hardware-accelerated video processing on the QCS8275 SoM. Supported codecs, resolutions and integration details depend on the software stack distributed with the board. For the full hardware specification refer to the QCS8275 Data Sheet (80-73475-1). 

📝 **Note:** Not all codecs or frameworks listed in the QCS8275 documentation may be available in the software distributed with VENTUNO Q. Refer to the VENTUNO Q Documentation for the current list of supported features. 

📝 **Note:** The Qualcomm-specific GStreamer plugins ( `gstreamer1.0-plugins-qcom` ) are not included by default in the Ubuntu image distributed with VENTUNO Q. They can be installed manually when hardwareaccelerated camera capture or video pipelines are needed. Refer to the VENTUNO Q User Manual for setup details. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**26 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`9 Peripherals & Headers`** 

VENTUNO Q exposes its dual-brain architecture through a comprehensive set of headers and connectors. MCU driven headers operate at **3.3 V** logic, while MPU driven headers operate at **1.8 V** . Always verify the voltage domain of any header before connecting external peripherals to prevent hardware damage. 

#### **`9.1 JANALOG`** 

The JANALOG header provides analog inputs, power rails and MCU control signals. It is compatible with the standard Arduino UNO analog header layout. Analog inputs reference `VREF+` on the 3.3 V rail and should not exceed `VDD + 0.3 V` (~3.6 V). **Do not apply 5 V to analog pins** . `IOREF` is a 3.3 V reference output, so please do not back-feed power through it. 

|**Pin**|**Designation**|**Net**|**Domain**|**MCU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|NC|JANALOG_BOOT_MCU_3V3|3.3 V MCU|BOOT0|MCU boot strap|
|2|IOREF|+3V3_LIMITED|Power|-|I/O voltage reference out|
|3|RESET|JANALOG_RESET_MCU_3V3|3.3 V MCU|NRST|MCU reset|
|4|+3V3 OUT|+3V3_LIMITED|Power|-|3.3 V supplyout|
|5|+5V USB|+5V_LIMITED|Power|-|5 V supplyout (USB-limited)|
|6|GND|GND|Power|-|Ground|
|7|GND|GND|Power|-|Ground|
|8|VIN|7-24V|Power|-|DC input (power only)|
|9|A0|JANALOG_A0_MCU_3V3|Analog|PA4|ADC input, not 5 V tolerant|
|10|A1|JANALOG_A1_MCU_3V3|Analog|PA5|ADC input, not 5 V tolerant|
|11|A2|JANALOG_A2_MCU_3V3|Analog|PE12|ADC input / SPI4_SCK|
|12|A3|JANALOG_A3_MCU_3V3|Analog|PE13|ADC input / SPI4_MISO|
|13|A4|JANALOG_A4_MCU_3V3|Analog|PE14|ADC input / SPI4_MOSI|
|14|A5|JANALOG_A5_MCU_3V3|Analog|PE15|ADC input|



📝 **Note:** A0 and A1 are direct MCU ADC inputs and are not 5 V tolerant. Valid input range is 0 V to `VREF+` (~3.3 V). The VIN on pin 8 is a power only input and should not be used as a GPIO. The VIN pin is protected by a 1.1 A PTC fuse, limiting it to approximately 26 W at 24 V. Powering the board from this pin is not recommended under full load. It is better suited for extracting power to supply a shield or peripheral rather than as a main board power source. 

📝 **Note:** A4 (PE14) and A5 (PE15) are analog and SPI-capable pins only and do not have a hardware I2C peripheral. Shields requiring I2C on A4 and A5 will need software I2C (bit-banging). Hardware I2C is available on JDIGITAL pins 17 (SDA, PH12) and 18 (SCL, PH11). 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**27 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.2 JDIGITAL`** 

The JDIGITAL header provides digital I/O, UART, SPI, I2C and PWM signals driven by the MCU at 3.3 V logic. It is compatible with the standard Arduino UNO digital header layout. 

|**Pin**|**Designation**|**Net**|**Domain**|**MCU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|D0 / RX|JDIGITAL_MCU_UART_3V3|3.3 V MCU|PB11|UART RX|
|2|D1 / TX|JDIGITAL_MCU_UART_3V3|3.3 V MCU|PB10|UART TX|
|3|D2|JDIGITAL_D2_MCU_3V3|3.3 V MCU|PB0|GPIO|
|4|D3|JDIGITAL_D3_MCU_3V3|3.3 V MCU|PB1|GPIO / PWM|
|5|D4|JDIGITAL_D4_MCU_3V3|3.3 V MCU|PB6|GPIO / FDCAN2_TX|
|6|D5|JDIGITAL_D5_MCU_3V3|3.3 V MCU|PB5|GPIO / PWM / FDCAN2_RX|
|7|D6|JDIGITAL_D6_MCU_3V3|3.3 V MCU|PB2|GPIO / PWM|
|8|D7|JDIGITAL_D7_MCU_3V3|3.3 V MCU|PB3|GPIO|
|9|D8|JDIGITAL_D8_MCU_3V3|3.3 V MCU|PB4|GPIO|
|10|D9|JDIGITAL_D9_MCU_3V3|3.3 V MCU|PB7|GPIO / PWM|
|11|D10 / CS|JDIGITAL_MCU_SPI_3V3|3.3 V MCU|PB12|SPI ChipSelect|
|12|D11 / MOSI|JDIGITAL_MCU_SPI_3V3|3.3 V MCU|PB15|SPI MOSI / PWM|
|13|D12 / MISO|JDIGITAL_MCU_SPI_3V3|3.3 V MCU|PB14|SPI MISO|
|14|D13 / SCK|JDIGITAL_MCU_SPI_3V3|3.3 V MCU|PB13|SPI Clock|
|15|GND|GND|Power|-|Ground|
|16|AREF|JDIGITAL_AREF_MCU_3V3|Analog|-|Analogvoltage reference|
|17|SDA|JDIGITAL_MCU_I2C_3V3|3.3 V MCU|PH12|I2C Data (I2C4 / I3C1)|
|18|SCL|JDIGITAL_MCU_I2C_3V3|3.3 V MCU|PH11|I2C Clock (I2C4 / I3C1)|



📝 **Note:** All JDIGITAL lines are 3.3 V MCU logic. Most pins are 5 V-tolerant as inputs in digital mode. AREF is an analog voltage reference input for the MCU's ADC. It is routed through an onboard analog switch (U28, SGM3157YC6/TR) and is only active when MCU pin PI8 is set HIGH. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**28 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.3 JSPI`** 

The JSPI header exposes a dedicated SPI bus for connecting peripherals such as SD card readers, display drivers or sensors. It also provides RESET and power. All signals are in the 3.3 V MCU domain. 

|**Pin**|**Designation**|**Net**|**Domain**|**MCU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|MISO|JSPI_MCU_SPI_3V3|3.3 V MCU|PF14|SPI MISO|
|2|+5V|+5V_LIMITED|Power|-|5 Vpower out|
|3|SCK|JSPI_MCU_SPI_3V3|3.3 V MCU|PC10|SPI Clock|
|4|MOSI|JSPI_MCU_SPI_3V3|3.3 V MCU|PC12|SPI MOSI|
|5|RESET|MCU_NRST|3.3 V MCU|NRST|MCU reset|
|6|GND|GND|Power|-|Ground|



⚠ **Note on power protection:** The 3.3 V and 5 V rails on JSPI and the UNO Shield headers are protected by dedicated load switches (MP5077GG-Z), each limited to **2.8 A** . These switches prevent connected peripherals from drawing excessive current and protect the board from backpowering. Do not attempt to bypass or disable these switches. 

#### **`9.4 Qwiic`** 

The Qwiic connector provides a 3.3 V I2C bus for plug-and-play connection to Modulino® nodes and compatible third-party sensors with no soldering required. The connector is polarized, with only a single orientation for connection. 

|**Pin**|**Designation**|**Net**|**Domain**|**MCU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|GND|GND|Power|-|Ground|
|2|VCC|+3V3_LIMITED|Power|-|3.3 V supplyfor devices|
|3|SDA|I2C3_SDA|3.3 V MCU|PC9|I2C Data|
|4|SCL|I2C3_SCL|3.3 V MCU|PA8|I2C Clock|



📝 **Note:** Qwiic connectors are expandable via chain form and multiple modules can be connected in series on the same I2C bus. The I2C bus is connected to the MCU. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**29 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.5 JCTL (MPU Remote Debug)`** 

The JCTL header is a 10-pin (2×5) connector that provides MPU UART console access, boot override control and power management signals. Arduino Bughopper is the recommended tool for interfacing with this header. Most active signal pins are ESD-protected via TVS diodes (pin 10 is not). Signal pins operate in mixed voltage domains, 1.8 V, 3.3 V and 7-24 V, refer to the pin table below. Pin 9 exposes the `SOM_VREG_MDPX3_1P8` rail directly; do not apply any external voltage to this pin. 

|**Pin**|**Designation**|**Net**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|GND|GND|Power|-|Ground|
|2|FORCED_USB_BOOT_N|FORCE_BOOT_3V3|3.3 V|-|3.3 V domain. Controls x2<br>NMOS driving<br>MD_FORCE_USB_BOOT_1V8<br>and<br>RTSS_FORCE_USB_BOOT_1V8.<br>Pull LOW to enter EDL mode<br>on next reboot|
|3|PMIC_POWER_EN|PMIC_POWER_EN|1.8 V<br>MPU|-|PMIC power enable|
|4|TX|UART_DBG_1V8|1.8 V<br>MPU|GPIO_43|MPU debug UART TX|
|5|GPIO|MD_GPIO_103|1.8 V<br>MPU|GPIO_103|General purpose GPIO|
|6|RX|UART_DBG_1V8|1.8 V<br>MPU|GPIO_44|MPU debug UART RX|
|7|GND|GND|Power|-|Ground|
|8|RESIN_N|RESIN_N|3.3 V|-|Open-drain, TVS protected.<br>Pull LOW for hot reboot<br>(voltage rails stayON)|
|9|+1V8 OUT|SOM_VREG_MDPX3_1P8|Power|-|MDPX3 domain 1.8 V direct,<br>do not applyexternal voltage|
|10|POWER_SWITCH_DISABLE_N|PWR_DISABLE|7-24 V<br>(up to 5<br>V max)|-|Not TVS protected. Pull LOW<br>for cold reboot (gates main<br>power)|



##### ⚠ **Read Before Connecting Anything to JCTL** 

Pin 9 exposes `SOM_VREG_MDPX3_1P8` (~1.8 V) directly, do not apply any external voltage to this pin. Pins operate in mixed voltage domains: pins 2 and 8 are 3.3 V domain, pins 4 and 6 (UART) are 1.8 V, pin 10 is the enable input for the main VIN power switch, with an internal voltage divider allowing direct connection to VIN, pull below 0.85 V to disable main power, keep above 1 V for normal operation, and do not exceed 5 V externally. Pin 10 is not TVS-protected. Applying incorrect voltages to any active JCTL pin can permanently damage the QCS8275 SoM. 

**The Arduino Bughopper is strongly recommended** for most debugging use cases, as it includes level translators and open-drain compatible output stages specifically designed for safe JCTL interfacing. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**30 / 62** 

```
Arduino® VENTUNO™ Q
```

If you choose to use a different USB-to-UART adapter or custom debug hardware instead, make sure that all signal lines are driven at the correct voltage for their respective domain, that pin 10 is never driven above 5 V, and that no backpower path exists to the `SOM_VREG_MDPX3_1P8` rail. 

##### 📝 **Boot control summary:** 

- **Hot reboot** (MPU only, voltage rails stay active): Pull pin 8 (RESIN_N) LOW via open-drain. **Cold reboot** (full power cycle, main power source gated): Pull pin 10 (POWER_SWITCH_DISABLE_N) LOW via open-drain. 

**EDL / Emergency Download mode** : Pull pin 2 (FORCED_USB_BOOT_N) LOW via open-drain, then trigger a reboot via pin 8 or pin 10. 

This connector is intended for development and debugging use. 

#### **`9.6 JHAT`** 

The JHAT header is a standard Raspberry Pi® compatible 40-pin header driven by the MPU (QCS8275) at **3.3 V** logic. It exposes I2C, SPI, UART, I2S and general-purpose GPIO signals from the MPU. Power pins supply 3.3 V and 5 V to attached HATs. 

All GPIO signals are level-translated from the MPU's 1.8 V domain to the 3.3 V HAT domain by four onboard bidirectional level translators, three 8-channel TXS0108ERKSR devices (U33_2, U33_3, U33_4) and one 4-channel TXS0104ERUTR device (U21), allowing direct compatibility with standard Raspberry Pi® HAT designs without additional level shifting. 

|**Pin**|**Designation**|**MPU Pin**|**Alt. Function**|**Domain**|**Notes**|
|---|---|---|---|---|---|
|1|+3V3 OUT|-|-|Power|3.3 V supplyout|
|2|+5V OUT|-|-|Power|5 V supplyout|
|3|GPIO 2 (SDA)|MD_GPIO_17|QUP0_SE0_I2C_SDA|3.3 V MPU|I2C1 Data|
|4|+5V OUT|-|-|Power|5 V supplyout|
|5|GPIO 3 (SCL)|MD_GPIO_18|QUP0_SE0_I2C_SCL|3.3 V MPU|I2C1 Clock|
|6|GND|-|-|Power|Ground|
|7|GPIO 4|MD_GPIO_83|GPCLK0|3.3 V MPU|General GPIO|
|8|GPIO 14 (TX)|MD_GPIO_86|QUP1_SE2_UART_TX|3.3 V MPU|UART0 TX|
|9|GND|-|-|Power|Ground|
|10|GPIO 15 (RX)|MD_GPIO_87|QUP1_SE2_UART_RX|3.3 V MPU|UART0 RX|
|11|GPIO 17|MD_GPIO_85|QUP1_SE2_UART_RFR|3.3 V MPU|UART RFR/RTS|
|12|GPIO 18 (CLK)|MD_GPIO_116|LPI_I2S1_SCK|3.3 V MPU|PCM Clock|
|13|GPIO 27|MD_GPIO_109|GPIO|3.3 V MPU|General GPIO|
|14|GND|-|-|Power|Ground|
|15|GPIO 22|MD_GPIO_90|GPIO|3.3 V MPU|General GPIO|
|16|GPIO 23|MD_GPIO_105|GPIO|3.3 V MPU|General GPIO|
|17|+3V3 OUT|-|-|Power|3.3 V supplyout|
|18|GPIO 24|MD_GPIO_106|GPIO|3.3 V MPU|General GPIO|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**31 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**MPU Pin**|**Alt. Function**|**Domain**|**Notes**|
|---|---|---|---|---|---|
|19|GPIO 10 (MOSI)|MD_GPIO_26|QUP0_SE3_SPI_MOSI|3.3 V MPU|SPI0 MOSI|
|20|GND|-|-|Power|Ground|
|21|GPIO 9 (MISO)|MD_GPIO_25|QUP0_SE3_SPI_MISO|3.3 V MPU|SPI0 MISO|
|22|GPIO 25|MD_GPIO_107|GPIO|3.3 V MPU|General GPIO|
|23|GPIO 11 (SCLK)|MD_GPIO_27|QUP0_SE3_SPI_SCK|3.3 V MPU|SPI0 Clock|
|24|GPIO 8 (CE0)|MD_GPIO_28|QUP0_SE3_SPI_CS|3.3 V MPU|SPI0 CE0|
|25|GND|-|-|Power|Ground|
|26|GPIO 7 (CE1)|MD_GPIO_88|GPIO|3.3 V MPU|SPI0 CE1|
|27|GPIO 0 (SDA)|MD_GPIO_19|QUP0_SE1_I2C_SDA|3.3 V MPU|I2C0 / EEPROM SDA|
|28|GPIO 1 (SCL)|MD_GPIO_20|QUP0_SE1_I2C_SCL|3.3 V MPU|I2C0 / EEPROM SCL|
|29|GPIO 5|MD_GPIO_89|GPIO|3.3 V MPU|General GPIO|
|30|GND|-|-|Power|Ground|
|31|GPIO 6|MD_GPIO_80|GPIO|3.3 V MPU|General GPIO|
|32|GPIO 12 (PWM0)|MD_GPIO_77|GPIO|3.3 V MPU|General GPIO|
|33|GPIO 13 (PWM1)|MD_GPIO_81|GPIO|3.3 V MPU|General GPIO|
|34|GND|-|-|Power|Ground|
|35|GPIO 19 (FS)|MD_GPIO_117|LPI_I2S1_WS|3.3 V MPU|PCM Frame Sync|
|36|GPIO 16|MD_GPIO_84|QUP1_SE2_UART_CTS|3.3 V MPU|UART CTS|
|37|GPIO 26|MD_GPIO_108|GPIO|3.3 V MPU|General GPIO|
|38|GPIO 20 (DIN)|MD_GPIO_118|LPI_I2S1_DATA0|3.3 V MPU|PCM Data In|
|39|GND|-|-|Power|Ground|
|40|GPIO 21 (DOUT)|MD_GPIO_119|LPI_I2S1_DATA1|3.3 V MPU|PCM Data Out|



📝 **Note:** Although the MPU GPIO signals are at 1.8 V internally, the onboard TXS0108ERKSR and TXS0104ERUTR level translators present them at 3.3 V on the JHAT connector, making it directly compatible with standard Raspberry Pi® HAT logic levels. Do not apply voltages above 3.3 V to any JHAT signal pin. Power pins (3.3 V and 5 V) are outputs from the board, please do not back-feed power through them from an attached HAT. 

📝 **Note:** JHAT UART pins 8, 10, 11, and 36 (TX, RX, RFR and CTS) share the same QUP1_SE2 UART as the onboard Wi-Fi®/Bluetooth® LE module. TX, RX and RFR are level-translated through U33_4 (TXS0108ERKSR), while CTS is translated separately through U21 (TXS0104ERUTR) along with GPIO 26, GPIO 20 (I2S_DATA0) and GPIO 21 (I2S_DATA1) on pins 37, 38 and 40. These pins are unavailable for external HAT use whenever Bluetooth is active. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**32 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.7 JMISC`** 

The JMISC header is a 60-pin high-density connector that combines the MCU PSSI parallel camera bus, MCU GPIO, MCU I2C, audio (microphone, headphone, mono speaker out, line out), MPU SoC SPI, MPU GPIO and MPU I2S signals. It is a mixed voltage header: **MCU signals are 3.3 V** , **MPU signals are 1.8 V** and the audio/mic pins are analog. 

|**Pin**|**Designation**|**Domain**|**MCU Pin**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|MCU_PSSI_D0|3.3 V MCU|PA9|-|PSSI data bit 0|
|2|MCU_TRACE_CLK|3.3 V MCU|PE2|-|MCU trace clock|
|3|MCU_PSSI_D1|3.3 V MCU|PC7|-|PSSI data bit 1|
|4|MCU_TRACE_D0|3.3 V MCU|PE3|-|MCU trace data 0|
|5|MCU_PSSI_D2|3.3 V MCU|PC8|-|PSSI data bit 2|
|6|MCU_TRACE_D1|3.3 V MCU|PE4|-|MCU trace data 1|
|7|MCU_PSSI_D3|3.3 V MCU|PE1|-|PSSI data bit 3|
|8|MCU_TRACE_D2|3.3 V MCU|PE5|-|MCU trace data 2|
|9|MCU_PSSI_D4|3.3 V MCU|PC11|-|PSSI data bit 4|
|10|MCU_TRACE_D3|3.3 V MCU|PE6|-|MCU trace data 3|
|11|MCU_PSSI_D5|3.3 V MCU|PD3|-|PSSI data bit 5|
|12|MCU_USART2_RX|3.3 V MCU|PE7|-|MCU USART2 RX|
|13|MCU_PSSI_D6|3.3 V MCU|PF4|-|PSSI data bit 6|
|14|MCU_USART2_TX|3.3 V MCU|PE8|-|MCU USART2 TX|
|15|MCU_PSSI_D7|3.3 V MCU|PI7|-|PSSI data bit 7|
|16|MCU_I2C_SCL|3.3 V MCU|PF1|-|MCU I2C2 clock|
|17|MCU_PSSI_PDCK|3.3 V MCU|PA6|-|PSSIpixel clock|
|18|MCU_I2C_SDA|3.3 V MCU|PF0|-|MCU I2C2 data|
|19|MCU_PSSI_RDY|3.3 V MCU|PI5|-|PSSI ready|
|20|MCU_GPIO_PA0|3.3 V MCU|PA0|-|MCU GPIO|
|21|MCU_PSSI_DE|3.3 V MCU|PH8|-|PSSI data enable|
|22|MCU_GPIO_PA1|3.3 V MCU|PA1|-|MCU GPIO|
|23|MCU_UART4_RX|3.3 V MCU|PA11|-|MCU UART4 RX|
|24|MCU_GPIO_PA2|3.3 V MCU|PA2|-|MCU GPIO|
|25|MCU_UART4_TX|3.3 V MCU|PA12|-|MCU UART4 TX|
|26|GND|Power|-|-|Ground|
|27|GND|Power|-|-|Ground|
|28|EAR_P|Analog|-|-|Speaker out P (mono)|
|29|MIC_INP|Analog|-|-|Microphone IN+|
|30|EAR_M|Analog|-|-|Speaker out M (mono)|
|31|MIC_INN|Analog|-|-|Microphone IN−|
|32|LINEOUT_P|Analog|-|-|Line out P|
|33|MIC_BIAS|Analog|-|-|Microphone bias|
|34|LINEOUT_M|Analog|-|-|Line out M|
|35|GND|Power|-|-|Ground|
|36|HPH_L|Analog|-|-|Headphone left|
|37|SOC_SPI_MISO|1.8 V MPU|-|GPIO_10|MPU SPI MISO (SE0)|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**33 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**Domain**|**MCU Pin**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|38|HPH_R|Analog|-|-|Headphone right|
|39|SOC_SPI_MOSI|1.8 V MPU|-|GPIO_11|MPU SPI MOSI (SE0)|
|40|HPH_REF|Analog|-|-|Headphone reference|
|41|SOC_SPI_SCK|1.8 V MPU|-|GPIO_12|MPU SPI clock (SE0)|
|42|HS_DET|Analog|-|-|Headset detect|
|43|SOC_SPI_CS0|1.8 V MPU|-|GPIO_13|MPU SPI chipselect 0 (SE0)|
|44|GND|Power|-|-|Ground|
|45|SOC_SPI_CS2|1.8 V MPU|-|GPIO_15|MPU SPI chipselect 2 (SE0)|
|46|SOC_MI2S_SCK|1.8 V MPU|-|GPIO_120|I2S clock|
|47|SOC_SPI_CS1|1.8 V MPU|-|GPIO_14|MPU SPI chipselect 1 (SE0)|
|48|SOC_MI2S_WS|1.8 V MPU|-|GPIO_121|I2S word select|
|49|SOC_GPIO_73|1.8 V MPU|-|GPIO_73|MPU SoC GPIO|
|50|SOC_MI2S_DATA0|1.8 V MPU|-|GPIO_122|I2S data 0|
|51|SOC_GPIO_74|1.8 V MPU|-|GPIO_74|MPU SoC GPIO|
|52|SOC_MI2S_DATA1|1.8 V MPU|-|GPIO_123|I2S data 1|
|53|+3V3 OUT|Power|-|-|3.3 V supplyout|
|54|+5V OUT|Power|-|-|5 V supplyout|
|55|+3V3 OUT|Power|-|-|3.3 V supplyout|
|56|+5V OUT|Power|-|-|5 V supplyout|
|57|SOM_VREG_MDPX3_1P8|Power|-|-|SOM 1.8 V rail|
|58|GND|Power|-|-|Ground|
|59|SOM_VCOIN / VBAT|RTC Backup|-|-|SOM and MCU RTC backupbatteryinput|
|60|NOT CONNECTED|-|-|-|-|



📝 **Note:** MCU pins are 3.3 V, MPU SoC pins are 1.8 V, audio/mic pins are analog. Do not mix voltage domains. SoC GPIO lines on JMISC are interface-dedicated and not general-purpose maker GPIO. 

📝 **Note:** JMISC pin 59 accepts an RTC backup battery up to 3.3 V to maintain the SOM and MCU real-time clocks when the board is otherwise unpowered. `SOM_VCOIN` (SOM RTC) and `VBAT` (MCU RTC) are two RTC backup battery inputs that are physically tied together at this single pin, rather than a shared power rail. Each connects through its own 0 Ω resistor to a common node, which is protected by a bidirectional TVS diode (Vr = 5.5 V) referenced to ground. The expected current draw is very low, and this pin does not supply power to keep the rest of the board on. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**34 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.8 JMEDIA`** 

The JMEDIA header is a 60-pin high-density connector that carries MIPI DSI (display), MIPI CSI0 and CSI1, camera clock signals and camera control I2C buses. All signals are in the **1.8 V MPU domain** . Power pins provide 3.3 V output and accept 7-24 V DC input. 

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|1|GND|Power|-|Ground|
|2|GND|Power|-|Ground|
|3|MIPI_DSI0_CLK_M|MIPI D-PHY|-|DSI clock −|
|4|MIPI_DSI0_L1_P|MIPI D-PHY|-|DSI lane 1 +|
|5|MIPI_DSI0_CLK_P|MIPI D-PHY|-|DSI clock +|
|6|MIPI_DSI0_L1_M|MIPI D-PHY|-|DSI lane 1 −|
|7|GND|Power|-|Ground|
|8|GND|Power|-|Ground|
|9|MIPI_DSI0_L2_M|MIPI D-PHY|-|DSI lane 2 −|
|10|MIPI_DSI0_L0_P|MIPI D-PHY|-|DSI lane 0 +|
|11|MIPI_DSI0_L2_P|MIPI D-PHY|-|DSI lane 2 +|
|12|MIPI_DSI0_L0_M|MIPI D-PHY|-|DSI lane 0 −|
|13|GND|Power|-|Ground|
|14|GND|Power|-|Ground|
|15|MIPI_DSI0_L3_M|MIPI D-PHY|-|DSI lane 3 −|
|16|SOC_CAM_MCLK0|1.8 V MPU|GPIO_67|Camera master clock 0|
|17|MIPI_DSI0_L3_P|MIPI D-PHY|-|DSI lane 3 +|
|18|SOC_CAM_MCLK1|1.8 V MPU|GPIO_68|Camera master clock 1|
|19|GND|Power|-|Ground|
|20|GND|Power|-|Ground|
|21|CSI0_LN0_M|MIPI D-PHY|-|CSI0 data lane 0 −|
|22|CCI_I2C2_SDA|1.8 V MPU|GPIO_59|Camera control I2C2 SDA|
|23|CSI0_LN0_P|MIPI D-PHY|-|CSI0 data lane 0 +|
|24|CCI_I2C2_SCL|1.8 V MPU|GPIO_60|Camera control I2C2 SCL|
|25|GND|Power|-|Ground|
|26|GND|Power|-|Ground|
|27|CSI0_LN1_M|MIPI D-PHY|-|CSI0 data lane 1 −|
|28|CSI1_LN3_P|MIPI D-PHY|-|CSI1 data lane 3 +|
|29|CSI0_LN1_P|MIPI D-PHY|-|CSI0 data lane 1 +|
|30|CSI1_LN3_M|MIPI D-PHY|-|CSI1 data lane 3 −|
|31|GND|Power|-|Ground|
|32|GND|Power|-|Ground|
|33|CSI0_CLK_M|MIPI D-PHY|-|CSI0 clock −|
|34|CSI1_LN2_P|MIPI D-PHY|-|CSI1 data lane 2 +|
|35|CSI0_CLK_P|MIPI D-PHY|-|CSI0 clock +|
|36|CSI1_LN2_M|MIPI D-PHY|-|CSI1 data lane 2 −|
|37|GND|Power|-|Ground|
|38|GND|Power|-|Ground|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**35 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|39|CSI0_LN2_M|MIPI D-PHY|-|CSI0 data lane 2 −|
|40|CSI1_CLK_P|MIPI D-PHY|-|CSI1 clock +|
|41|CSI0_LN2_P|MIPI D-PHY|-|CSI0 data lane 2 +|
|42|CSI1_CLK_M|MIPI D-PHY|-|CSI1 clock −|
|43|GND|Power|-|Ground|
|44|GND|Power|-|Ground|
|45|CSI0_LN3_M|MIPI D-PHY|-|CSI0 data lane 3 −|
|46|CSI1_LN1_P|MIPI D-PHY|-|CSI1 data lane 1 +|
|47|CSI0_LN3_P|MIPI D-PHY|-|CSI0 data lane 3 +|
|48|CSI1_LN1_M|MIPI D-PHY|-|CSI1 data lane 1 −|
|49|GND|Power|-|Ground|
|50|GND|Power|-|Ground|
|51|CCI_I2C0_SCL|1.8 V MPU|GPIO_58|Camera control I2C0 SCL|
|52|CSI1_LN0_P|MIPI D-PHY|-|CSI1 data lane 0 +|
|53|CCI_I2C0_SDA|1.8 V MPU|GPIO_57|Camera control I2C0 SDA|
|54|CSI1_LN0_M|MIPI D-PHY|-|CSI1 data lane 0 −|
|55|GND|Power|-|Ground|
|56|GND|Power|-|Ground|
|57|VIN IN|Power|-|7-24 V DC input (1.5 A max, PTCprotected)|
|58|+3V3 OUT|Power|-|3.3 V supplyout|
|59|VIN IN|Power|-|7-24 V DC input (1.5 A max, PTCprotected)|
|60|+3V3 OUT|Power|-|3.3 V supplyout|



📝 **Note:** The VIN pins on JMEDIA (pins 57 and 59) are the same net, protected by a 1.5 A PTC fuse (F3, MFMSMF150/24X) and a 24 V TVS diode. They can supply power to a carrier board but are not intended to power the entire VENTUNO Q board from an external source. 

📝 **Note:** MIPI CSI/DSI differential pairs are D-PHY signals and should not be used as general-purpose I/Os. All control signals (CCI_I2C, CAM_MCLK) are 1.8 V MPU domain. VIN on pins 57 and 59 is the DC input voltage power only. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**36 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.9 JOMEGA`** 

The JOMEGA header is a 100-pin high-density expansion connector that provides USB 3.0, CAN-FD, JTAG, MPU GPIO, SPI and UART debug and power management signals. Voltage domains are mixed: USB and some control signals drive at 3.3 V, while JTAG, SPI, and UART debug signals drive at 1.8 V in the MPU domain. 

|**Pin**|**Designation**|**Domain**|**MCU Pin**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|1|VIN|Power|-|-|7-24 V DC input|
|2|GND|Power|-|-|Ground|
|3|VIN|Power|-|-|7-24 V DC input|
|4|GND|Power|-|-|Ground|
|5|VIN|Power|-|-|7-24 V DC input|
|6|GND|Power|-|-|Ground|
|7|VIN|Power|-|-|7-24 V DC input|
|8|GND|Power|-|-|Ground|
|9|VIN|Power|-|-|7-24 V DC input|
|10|GND|Power|-|-|Ground|
|11|VIN|Power|-|-|7-24 V DC input|
|12|GND|Power|-|-|Ground|
|13|VIN|Power|-|-|7-24 V DC input|
|14|GND|Power|-|-|Ground|
|15|GND|Power|-|-|Ground|
|16|GND|Power|-|-|Ground|
|17|GND|Power|-|-|Ground|
|18|USB3.0_1_SS_TX_P|USB 3.0|-|-|USBport 1 SuperSpeed TX+|
|19|GND|Power|-|-|Ground|
|20|USB3.0_1_SS_TX_N|USB 3.0|-|-|USBport 1 SuperSpeed TX−|
|21|GND|Power|-|-|Ground|
|22|GND|Power|-|-|Ground|
|23|GND|Power|-|-|Ground|
|24|USB3.0_1_HS_D_P|USB 3.0|-|-|USBport 1 HighSpeed D+|
|25|GND|Power|-|-|Ground|
|26|USB3.0_1_HS_D_N|USB 3.0|-|-|USBport 1 HighSpeed D−|
|27|GND|Power|-|-|Ground|
|28|GND|Power|-|-|Ground|
|29|GND|Power|-|-|Ground|
|30|USB3.0_1_SS_RX_P|USB 3.0|-|-|USBport 1 SuperSpeed RX+|
|31|GND|Power|-|-|Ground|
|32|USB3.0_1_SS_RX_N|USB 3.0|-|-|USBport 1 SuperSpeed RX−|
|33|GND|Power|-|-|Ground|
|34|GND|Power|-|-|Ground|
|35|GND|Power|-|-|Ground|
|36|USB3.0_2_SS_TX_P|USB 3.0|-|-|USBport 2 SuperSpeed TX+|
|37|GND|Power|-|-|Ground|
|38|USB3.0_2_SS_TX_N|USB 3.0|-|-|USBport 2 SuperSpeed TX−|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**37 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**Domain**|**MCU Pin**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|39|IO0_3V3|3.3 V MCU|PC0|-|MCU GPIO|
|40|GND|Power|-|-|Ground|
|41|IO1_3V3|3.3 V MCU|PC1|-|MCU GPIO|
|42|USB3.0_2_HS_D_P|USB 3.0|-|-|USBport 2 HighSpeed D+|
|43|IO2_3V3|3.3 V MCU|PC2|-|MCU GPIO|
|44|USB3.0_2_HS_D_N|USB 3.0|-|-|USBport 2 HighSpeed D−|
|45|IO3_3V3|3.3 V MCU|PC3|-|MCU GPIO|
|46|GND|Power|-|-|Ground|
|47|IO4_3V3|3.3 V MCU|PD12|-|MCU GPIO|
|48|USB3.0_2_SS_RX_P|USB 3.0|-|-|USBport 2 SuperSpeed RX+|
|49|IO5_3V3|3.3 V MCU|PD13|-|MCU GPIO|
|50|USB3.0_2_SS_RX_N|USB 3.0|-|-|USBport 2 SuperSpeed RX−|
|51|IO6_3V3|3.3 V MCU|PD14|-|MCU GPIO|
|52|GND|Power|-|-|Ground|
|53|IO7_3V3|3.3 V MCU|PD15|-|MCU GPIO|
|54|USB3.0_1_PWRON_3V3|3.3 V|-|-|USBport 1power enable|
|55|IO8_3V3|3.3 V MCU|PI2|-|MCU GPIO<br>l|
|56|USB3.0_1_OVERCUR_3V3|3.3 V|-|-|USBport 1 overcurrent flag|
|57|MIC_INP|Analog|-|-|Microphone IN+|
|58|USB3.0_2_PWRON_3V3|3.3 V|-|-|USBport 2power enable|
|59|MIC_INN|Analog|-|-|Microphone IN−|
|60|USB3.0_2_OVERCUR_3V3|3.3 V|-|-|USBport 2 overcurrent flag|
|61|MIC_BIAS|Analog|-|-|Microphone bias|
|62|SPI_ICS_MISO|1.8 V MPU|-|GPIO_39|MPU SPI MISO (SPI_ICS_1V8)|
|63|TMS|1.8 V MPU|-|-|JTAG TMS (JTAG_1V8)|
|64|SPI_ICS_MOSI|1.8 V MPU|-|GPIO_40|MPU SPI MOSI|
|65|TDO|1.8 V MPU|-|-|JTAG TDO|
|66|SPI_ICS_SCK|1.8 V MPU|-|GPIO_37|MPU SPI clock|
|67|TDI|1.8 V MPU|-|-|JTAG TDI|
|68|SPI_ICS_CS|1.8 V MPU|-|GPIO_38|MPU SPI chipselect|
|69|TCK|1.8 V MPU|-|-|JTAG clock|
|70|PM_PS_HOLD_1V8|1.8 V MPU|-|-|MPUpower state hold|
|71|SRST_N|1.8 V MPU|-|-|JTAG system reset|
|72|FORCED_USB_BOOT_1V8|1.8 V MPU|-|GPIO_52|Force USB boot mode|
|73|TRST_N|1.8 V MPU|-|-|JTAG TAP reset|
|74|PWR_EN_N|1.8 V MPU|-|-|Power enable (active low)|
|75|GND|Power|-|-|Ground|
|76|USER_BUTTON|3.3 V|-|GPIO_79|User button input|
|77|SOM_VREG_S5S_SPX3_1P8|Power|-|-|SOM RTSS 1.8 V rail|
|78|PM_RESIN_N_3V3|3.3 V|-|-|MPU PMIC reset input|
|79|SOM_VREG_MDPX3_1P8|Power|-|-|SOM 1.8 V rail|
|80|RTSS_RESIN_N_1V8|1.8 V MPU|-|-|RTSS reset input|
|81|SOM_VREG_MDPX3_1P8|Power|-|-|SOM 1.8 V rail|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**38 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**Domain**|**MCU Pin**|**MPU Pin**|**Notes**|
|---|---|---|---|---|---|
|82|RTSS_PS_HOLD_SPX3_1P8_1V8|1.8 V MPU|-|-|RTSSpower state hold|
|83|UART_DBG_TX|1.8 V MPU|-|GPIO_71|MPU debugUART TX|
|84|GND|Power|-|-|Ground|
|85|UART_DBG_RX|1.8 V MPU|-|GPIO_72|MPU debugUART RX|
|86|CAN1_TX|3.3 V MCU|PD5|-|CAN-FD bus 1 TX (no PHY)|
|87|PWR_DISABLE_7-24V|System|-|-|Disables VINpowerpath|
|88|CAN1_RX|3.3 V MCU|PI9|-|CAN-FD bus 1 RX (no PHY)|
|89|FORCE_BOOT_3V3|3.3 V|-|-|Force boot override|
|90|GND|Power|-|-|Ground|
|91|+3V3 OUT|Power|-|-|3.3 V supplyout|
|92|CAN2_TX|3.3 V MCU|PA10|-|CAN-FD bus 2 TX (no PHY)|
|93|+3V3 OUT|Power|-|-|3.3 V supplyout|
|94|CAN2_RX|3.3 V MCU|PD9|-|CAN-FD bus 2 RX (no PHY)|
|95|+3V3 OUT|Power|-|-|3.3 V supplyout|
|96|GND|Power|-|-|Ground|
|97|+5V OUT|Power|-|-|5 V supplyout|
|98|CAN3_TX|3.3 V MCU|PF6|-|CAN-FD bus 3 TX (no PHY)|
|99|+5V OUT|Power|-|-|5 V supplyout|
|100|CAN3_RX|3.3 V MCU|PF7|-|CAN-FD bus 3 RX (no PHY)|



📝 **Note:** JTAG and SPI ICS signals are 1.8 V MPU domain. Please do not apply 3.3 V logic directly. CAN FD buses on JOMEGA have no physical PHY layer, an external CAN transceiver is required. VIN pins are power input only. 

#### **`9.10 MIPI CSI Camera Connectors (J3_1, J3_2, J3_3)`** 

VENTUNO Q provides three independent MIPI CSI camera connectors (J3_1, J3_2, J3_3), each a 22-pin FPC connector (TF31-22S-0.5SH, 0.5 mm pitch). Each supports 4-lane MIPI CSI-2 cameras. Control signals (I2C, GPIO) operate at **3.3 V** for both the enable GPIO on pin 17 and the I2C buses on pins 20–21. The I2C signals are level-translated to 1.8 V internally before reaching the SoM `CCI_I2C` bus. MIPI differential pairs are D-PHY and should not be used as GPIO. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**39 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`9.10.1 J3_1 - Camera 2`** 

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|1|GND|Power|-|Ground|
|2|LN0_M|MIPI D-PHY|-|CSI2 data lane 0 −|
|3|LN0_P|MIPI D-PHY|-|CSI2 data lane 0 +|
|4|GND|Power|-|Ground|
|5|LN1_M|MIPI D-PHY|-|CSI2 data lane 1 −|
|6|LN1_P|MIPI D-PHY|-|CSI2 data lane 1 +|
|7|GND|Power|-|Ground|
|8|CLK_M|MIPI D-PHY|-|CSI2 clock lane −|
|9|CLK_P|MIPI D-PHY|-|CSI2 clock lane +|
|10|GND|Power|-|Ground|
|11|LN2_M|MIPI D-PHY|-|CSI2 data lane 2 −|
|12|LN2_P|MIPI D-PHY|-|CSI2 data lane 2 +|
|13|GND|Power|-|Ground|
|14|LN3_M|MIPI D-PHY|-|CSI2 data lane 3 −|
|15|LN3_P|MIPI D-PHY|-|CSI2 data lane 3 +|
|16|GND|Power|-|Ground|
|17|GPIO_PIN17_3V3|3.3 V|GPIO_82|Camera GPIO|
|18|NOT CONNECTED|-|-|-|
|19|GND|Power|-|Ground|
|20|SCL|3.3 V|GPIO_62|Camera I2C clock (CCI_I2C4, level-translated to 1.8 V)|
|21|SDA|3.3 V|GPIO_61|Camera I2C data (CCI_I2C4, level-translated to 1.8 V)|
|22|+3V3|Power|-|3.3 V supplyfor camera module|



#### **`9.10.2 J3_2 - Camera 0`** 

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|1|GND|Power|-|Ground|
|2|LN0_M|MIPI D-PHY|-|CSI0 data lane 0 −|
|3|LN0_P|MIPI D-PHY|-|CSI0 data lane 0 +|
|4|GND|Power|-|Ground|
|5|LN1_M|MIPI D-PHY|-|CSI0 data lane 1 −|
|6|LN1_P|MIPI D-PHY|-|CSI0 data lane 1 +|
|7|GND|Power|-|Ground|
|8|CLK_M|MIPI D-PHY|-|CSI0 clock lane −|
|9|CLK_P|MIPI D-PHY|-|CSI0 clock lane +|
|10|GND|Power|-|Ground|
|11|LN2_M|MIPI D-PHY|-|CSI0 data lane 2 −|
|12|LN2_P|MIPI D-PHY|-|CSI0 data lane 2 +|
|13|GND|Power|-|Ground|
|14|LN3_M|MIPI D-PHY|-|CSI0 data lane 3 −|
|15|LN3_P|MIPI D-PHY|-|CSI0 data lane 3 +|
|16|GND|Power|-|Ground|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**40 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|17|GPIO_PIN17_3V3|3.3 V|GPIO_64|Camera GPIO|
|18|NOT CONNECTED|-|-|-|
|19|GND|Power|-|Ground|
|20|SCL|3.3 V|GPIO_58|Camera I2C clock (CCI_I2C0, level-translated to 1.8 V)|
|21|SDA|3.3 V|GPIO_57|Camera I2C data (CCI_I2C0, level-translated to 1.8 V)|
|22|+3V3|Power|-|3.3 V supplyfor camera module|



#### **`9.10.3 J3_3 - Camera 1`** 

|**Pin**|**Designation**|**Domain**|**MPU Pin**|**Notes**|
|---|---|---|---|---|
|1|GND|Power|-|Ground|
|2|LN0_M|MIPI D-PHY|-|CSI1 data lane 0 −|
|3|LN0_P|MIPI D-PHY|-|CSI1 data lane 0 +|
|4|GND|Power|-|Ground|
|5|LN1_M|MIPI D-PHY|-|CSI1 data lane 1 −|
|6|LN1_P|MIPI D-PHY|-|CSI1 data lane 1 +|
|7|GND|Power|-|Ground|
|8|CLK_M|MIPI D-PHY|-|CSI1 clock lane −|
|9|CLK_P|MIPI D-PHY|-|CSI1 clock lane +|
|10|GND|Power|-|Ground|
|11|LN2_M|MIPI D-PHY|-|CSI1 data lane 2 −|
|12|LN2_P|MIPI D-PHY|-|CSI1 data lane 2 +|
|13|GND|Power|-|Ground|
|14|LN3_M|MIPI D-PHY|-|CSI1 data lane 3 −|
|15|LN3_P|MIPI D-PHY|-|CSI1 data lane 3 +|
|16|GND|Power|-|Ground|
|17|GPIO_PIN17_3V3|3.3 V|GPIO_75|Camera GPIO|
|18|NOT CONNECTED|-|-|-|
|19|GND|Power|-|Ground|
|20|SCL|3.3 V|GPIO_60|Camera I2C clock (CCI_I2C2, level-translated to 1.8 V)|
|21|SDA|3.3 V|GPIO_59|Camera I2C data (CCI_I2C2, level-translated to 1.8 V)|
|22|+3V3|Power|-|3.3 V supplyfor camera module|



📝 **Note:** MIPI D-PHY differential lanes are not general-purpose I/O. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**41 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`10 High-Speed Peripherals`** 

#### **`10.1 Networking`** 

Tri-band Wi-Fi® 6 (2.4/5/6 GHz) and Bluetooth® 5.3 via the NFA725B integrated module. Wired connectivity via 2.5 Gbps RJ45 Ethernet (QCA-8081 PHY). 

#### **`10.2 Storage`** 

Expandable NVMe Gen 4 storage via M.2 2230 Key M connector (MDT580M01001), connected directly to the QCS8275 SOM via a 4-lane PCIe Gen 4 interface. The M.2 slot is non-bootable per the QCS8275 specification. Slot power is independently switched via an MP5077GG-Z load switch controlled by the MPU. 

The PI7C9X2G304EV PCIe Gen 2 packet switch on the board is dedicated to the USB 3.0 xHCI host controller (TUSB7340RKMR) and the Wi-Fi® module (NFA725B). 

📝 **Note:** The MPU gates the M.2 slot power. If the MPU has not completed boot or the power gate has not been enabled, an installed NVMe drive will not receive power and will not be enumerated. It is expected behavior during early boot. 

#### **`10.3 USB-C`** 

The USB-C connector supports host/device role switching, power role switching, DisplayPort Alt-Mode output and USB Power Delivery negotiation up to 20 V via the CYPD6129-52LQXI PD controller. The SuperSpeed differential pairs on the USB-C connector are shared between USB 3.0 SuperSpeed data and DisplayPort Alt-Mode via the onboard USB eDP MUX (TMUXHS4446RETT). 

**When DisplayPort Alt-Mode is active** , the SuperSpeed lanes are reallocated to DisplayPort. USB data is then limited to USB 2.0 speeds (HighSpeed, 480 Mbps) on the HS_D+/D− pair only. Full USB 3.0 SuperSpeed data is only available when DisplayPort Alt-Mode is not active. 

The CYPD6129 monitors both VBUS and VIN to determine the board's power state and negotiates PD profiles accordingly. The Fault LED (red, GPIO9/P4.1 on CYPD6129) indicates fault conditions. Key power scenarios are summarised below: 

|**Scenario**|**Expected Outcome**|
|---|---|
|VIN connected, USB not connected|System powered by VIN, PD controller in battery<br>mode|
|VIN connected, USB connected|System powered by VIN, PD negotiation and data<br>role allowed|
|VIN not connected, USB-C to USB-C|System powered by VBUS, PD negotiation starts,<br>targets 20 V @ 3 A<br>f|
|VIN not connected, USB-C to USB-A|PD detects non-PD source, system off, Fault LED<br>blinking|
|VIN not connected, USB-C to USB-A -> VIN connected on<br>the fly|PD recognises VIN, ungates VIN, keeps VBUS gated|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**42 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Scenario**|**Expected Outcome**|
|---|---|
|VIN not connected, USB-C to USB-C (power negotiated) -><br>l|System powered by VBUS, VIN gated, Fault LED<br>f|
|VIN connected on the fly|shows differentpattern|



📝 **Note:** The CYPD6129 is programmed to require a PD voltage profile above 5 V before enabling the main power path. Connecting via a standard USB-C to USB-A cable, or a USB-C port that only supplies 5 V without PD negotiation, will not power the board and will cause the Fault LED to blink. Always use a USB-C PDcapable supply that supports 9 V, 15 V or 20 V for reliable USB-C powered operation. 

The CYPD6129 remains always powered via a dedicated buck converter (LMR51440SDRRR, U26) supplied from any connected power source, allowing it to monitor and negotiate power independently before enabling the main board power path. 

#### **`10.4 USB Type-A`** 

Both USB 3.0 Type-A ports are independently protected by dedicated load switches (MP5077GG-Z). Each port's VBUS is hard-limited to 1.71 A by the ILIM resistor network. Power enable for each port is managed by the TUSB7340RKMR. 

|**Parameter**|**Value**|
|---|---|
|VBUS voltage|5 V|
|Max currentperport|1.71 A (ILIM-set,perport)|
|Protection|MP5077GG-Z load switch|
|Enable control|TUSB7340RKMR|



📝 **Note:** The 1.71 A per-port current limit is set in hardware and cannot be overridden in software. Do not attempt to bypass the load switch. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**43 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`10.5 Display`** 

The board provides the following display outputs: 

- **HDMI** via the dedicated HDMI connector, driven by the onboard ADV7535 DSI-to-HDMI bridge. The ADV7535 uses the MIPI DSI lines from the SoM. When HDMI is active, the MIPI-DSI lines on the JMEDIA header are unavailable. 

- **DisplayPort Alt Mode** via the USB-C connector through the onboard USB eDP MUX (TMUXHS4446RETT). **MIPI DSI on JMEDIA** available when HDMI output is not active (requires DSI overlay configuration). 

```
10.6 Camera
```

VENTUNO Q supports camera input through three onboard MIPI CSI connectors (J3_1, J3_2, J3_3) and through the JMEDIA carrier header. 

##### **VENTUNO Q standalone (default):** 

All three onboard CSI connectors (J3_1, J3_2, J3_3) are available simultaneously for camera input. This is a cameraonly configuration and MIPI DSI is not active by default. Display output is available via the HDMI connector or USB-C DisplayPort Alt Mode. 

📝 **Note:** The Arducam IMX577 Mini Camera Module (SKU B0488) is compatible with VENTUNO Q via its onboard MIPI CSI connectors. Refer to the VENTUNO Q User Manual for testing and setup instructions. 

##### **VENTUNO Q with a compatible carrier board:** 

A carrier board attached to JMEDIA can enable a MIPI DSI display alongside the onboard cameras. If the carrier's DSI overlay is enabled, Camera 0 (J3_2) is not available, since it shares the CCI_I2C0 bus (GPIO_57/58) with the JMEDIA header. Cameras 1 (J3_3) and 2 (J3_1) remain available. 

📝 **Note:** Camera availability when a carrier board is attached depends on the specific carrier's configuration. Refer to the carrier board's own documentation for details. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**44 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`11 Device Operation`** 

#### **`11.1 Getting Started - Arduino App Lab`** 

Arduino App Lab [1] is a unified editor that builds and runs projects across both processors of VENTUNO Q. It combines embedded (sketch) programming, Linux development and edge AI in a single environment. 

A project is an **App** that can include: 

A Python® program that runs on the Linux system (Qualcomm Dragonwing™ IQ8) 

- An Arduino sketch that runs on the microcontroller (STM32H5F5) 

- Optional **Bricks** (pre-packaged services such as AI models, web servers or API clients) that are deployed alongside the App and run on the Linux system. 

Apps use **Bridge** to exchange data between the Linux side and the microcontroller. 

##### **Three Setups. One Experience.** 



<!-- Start of picture text -->
WB rower suppiy 12-267/ 24<br>a!<br>(<br>vos B= ;<br>BS!<br>GeEpnaoanooc q ~<br>PT ITTITTIT<br>TA<br>MennoTTT TTT TTT TTsea| vncJ fee reer sty sae<br><!-- End of picture text -->

- **Single-Board Computer Mode:** Arduino App Lab runs directly on VENTUNO Q. Plug in a monitor via HDMI (or USB-C), a keyboard, and a mouse for an all-in-one development environment. No PC needed. 

- **PC Hosted Mode:** Connect VENTUNO Q to your computer via USB-C or network and run Arduino App Lab on your PC. 

- **Networked Mode:** VENTUNO Q runs headless with no display, keyboard or mouse. Access the board remotely over Wi-Fi® or Ethernet. 

📝 **Note:** In **PC Hosted** mode, a USB data connection is required for first-time setup. Afterward, you can use the **Network** target over LAN (SSH). 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**45 / 62** 

```
Arduino® VENTUNO™ Q
```

In **Single-Board Computer** mode, no USB data link is needed, power the board and use the **Network** target once it joins your network. USB peripherals (keyboard, mouse, USB camera, microphone) can be connected directly to the onboard USB-A ports. When DisplayPort Alt-Mode is active on the USB-C port, USB data speed is reduced. 

For full setup instructions, initial configuration and first-use guidance, refer to the VENTUNO Q User Manual. 

📝 **Note:** If powering via USB-C for the first time, the Fault LED may blink when connected to a computer or non-PD USB-C port. The board requires a PD-capable supply of at least 9 V to start. For full-performance operation including AI inference, connected peripherals and attached HATs, a supply of 12 V or higher is recommended via USB-C PD (up to 20 V) or the barrel jack or screw terminal (7-24 V). Refer to the Input Power section for voltage and current limits per source. 

📝 **Note:** First boot takes 20-30 seconds while Linux starts. The LED matrix displays a boot animation when the MCU bootloader is loaded and a valid sketch is running. Wait for it to finish before interacting with the board. If the animation does not appear, please refer to the VENTUNO Q User Manual for more details. 

#### **`11.2 Bricks`** 

Bricks are pre-packaged building blocks in Arduino App Lab, including AI models, web services, sensor integrations, databases and user interfaces, that deploy alongside your App on the Linux side without requiring you to write the underlying infrastructure. For a full guide on selecting and using Bricks, refer to the VENTUNO Q User Manual. 

📝 **Note:** While an App is bound and running, USB interfaces may be occupied by the system. To use external CLI tools over USB, stop the App or disconnect the board. 

#### **`11.3 Buttons & Boot Modes`** 

VENTUNO Q includes two onboard buttons: a **vertical pushbutton** and a **user button** . 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**46 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
Vertical hs<br>Pushbutton >< lityAe : ss<br>SN {ye % Vy<br>Rees”~ tT i,<br>ow eS be: Ue)<br>Yaa fate<br>* Ta leis,<br>: on SS<br>Fin A 64 SS “<br>Ue. ©. Te S8 ae ¥<br>aaseencecarss (Qe<br><!-- End of picture text -->

#### **`11.4 Vertical Pushbutton`** 

The vertical pushbutton is connected to MCU GPIO PK13. It can be used to interact with and shut down the board. 

- **Single press (Single-Board Computer mode):** Triggers a shutdown dialog on screen. The user can confirm to power off immediately, or cancel to dismiss and continue normal operation. If no interaction is made, the board powers off automatically after 60 seconds. 

- **Long press (10+ seconds, SSH / ADB mode):** Shuts down the system completely. The board will remain off until power is disconnected and reconnected. 

📝 **Note:** A long-press shutdown stops the Linux environment completely and will interrupt any running Apps. Save work and make sure external processes are safely stopped where applicable. The board boots automatically when power is supplied, and pressing the pushbutton is not required for a normal boot. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**47 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`11.5 User Button`** 



<!-- Start of picture text -->
a SAC<br>a” Wa alte.<br>oll Way Mp<br>oa ote.<br>4 » a~ {7 14.<br>¢ es Ot US<br>KP AI Ma<br>Wig ©tt ek Ss<br>SAsticssssssem NT?<br>User Button ea atenatasan i) eS<br>SS 1 ee<br>“ia”ET a, ae> A<br>So cae ay<br>ae RS ss > eh<br>« ee rf<br>RS a. ua<br><!-- End of picture text -->

The user button is connected to the MPU (GPIO_79) and is available as a general-purpose input. It can be read from Linux applications and scripts using standard GPIO interfaces. For usage examples, refer to the VENTUNO Q User Manual. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**48 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`12 Mechanical Information`** 

The board measures 160 mm × 100 mm. The total height without the SoM heatsink and fan is 25.8 mm. The 40-pin JHAT header follows the standard Raspberry Pi® HAT mechanical specification, allowing physical compatibility with compliant HAT accessories. 



<!-- Start of picture text -->
15.74 mm<br>8.5 mm 2.04 mm 35.02 mm<br>9.78 mm<br>100 mm<br>9.41 mm 2.35 mm<br>10.72 mm 18.59 mm 34.52 mm<br>11.1 mm 22.81 mm 28 mm 27.27 mm<br>16.37 mm<br>3.33 mm<br>34 mm 10.02 mm<br>57.5 mm 46.86 mm<br>160 mm<br>3.09 mm 27.85 mm<br>4x R1.85 mm<br>12.14 mm<br>15.69 mm<br>14.28 mm<br>3.33 m m 6x R1.6 mm<br>22.05 mm<br>23.02 mm<br>25.25 mm<br>42.63 mm<br>8.6 mm<br>5.15 mm 14.57 mm<br>8.67 mm 26.37 mm 9.78 mm<br>11.16 mm<br><!-- End of picture text -->

The UNO Shield headers keep the standard Arduino UNO footprint spacing, allowing direct mechanical and electrical compatibility with the UNO Shield ecosystem. 

The board features three sets of holes serving different mechanical purposes: 

- **4× M2.5 standoffs** (5 mm height, soldered to the board) for heatsink mounting, located at 9.78 mm from the right edge and at 10.02 mm and 42.63 mm from the top edge. 

- **4× 3.2 mm** corner mounting holes for installation in enclosures, on panels or onto custom carrier boards and accessories. 

- **2× 3.2 mm** HAT mounting holes following the standard Raspberry Pi® HAT mechanical specification, compatible with M3 standoffs for attaching HAT accessories. 

- **1× M2 standoff** (4 mm height) for securing an M.2 2230 NVMe storage card in the M.2 slot. 

VENTUNO Q ships with 4× M3 hex standoffs and 4× M3 nuts, included in a separate bag. In ESD-sensitive 

environments, attach one standoff and nut to each of the four corner mounting holes to raise the board off the working surface and increase clearance. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**49 / 62** 

```
Arduino® VENTUNO™ Q
```

|**Item**|**Dimension**|
|---|---|
|M3 Hex Standoff|Hex length 20 mm, thread length 6 mm, thread diameter 3 mm|
|M3 Nut|Height 2.4 mm, hex across flats 5.6 mm, inner diameter 3 mm|





<!-- Start of picture text -->
S sv<br>elit tN —<br>Se oe wy i<br>9d<br><!-- End of picture text -->

#### **`12.1 SoM Heatsink & Thermal Design`** 

The Qualcomm® Dragonwing™ IQ8 (QCS8275) SoM requires active cooling for sustained operation at full performance. The SoM footprint on the board measures **57.5 mm × 57.5 mm** , centered at **14.26 mm** from the left edge and **14.73 mm** from the bottom edge, with a horizontal offset of **8.95 mm** and a vertical offset of **8.55 mm** to the SoM active area. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**50 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
SST be,<br>8)<br>Be lis. ey SS 4aSs<br>ie iS aN Ye<br>g a S<br>SS; WW,ae<br><!-- End of picture text -->

The four M2.5 standoffs define the mounting pattern for the included heatsink and fan assembly, positioned symmetrically around the SoM footprint to provide even clamping force across the SoM lid. 

Under worst-case conditions with MPU, NPU and GPU running simultaneously at full performance, the board can draw approximately 25 W or more. The included active cooling solution is optimized for this thermal load. Make sure the fan remains operational during sustained high-performance workloads. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**51 / 62** 

```
Arduino® VENTUNO™ Q
```



<!-- Start of picture text -->
8.55 mm<br>14.26 mm 20.69 mm 4 mm 30.5 mm<br>4.25 mm<br>57.5 mm<br>R1.5 mm 43.13 mm<br>10.62 mm<br>14.73 mm 57.5 mm 4x R1.85 mm 6.6 mm 3.5 mm<br>4 mm 8.95 mm<br>1.5 mm<br><!-- End of picture text -->

📝 **Note:** Operating the board under heavy AI or compute workloads without adequate cooling may trigger thermal throttling of the QCS8275 SoM, reducing performance. Always verify thermal headroom for your target use case and enclosure environment. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**52 / 62** 

```
Arduino® VENTUNO™ Q
```

# **`Safety Information`** 

Maintain a minimum separation distance of 20 cm between the device and the user during operation. The 5 GHz and 6GHz frequency band may be subject to operational restrictions depending on the country of use. 

##### **Bulgarian (BG):** 

Поддържайте минимално разстояние от 20 см между устройството и потребителя по време на работа. Честотните ленти 5 GHz и 6 GHz можете да подлежат на ограничения за експлоатация в зависимост от държавата, в която се използва устройството. 

##### **Croatian (HR):** 

Održavajte minimalnu udaljenost od 20 cm između uređaja i korisnika tijekom rada. Frekvencijski pojas od 5 GHz i 6 GHz može podlijegati ograničenjima ovisno o zemlji uporabe. 

##### **Czech (CS):** 

Udržujte minimální vzdálenost 20 cm mezi zařízením a uživatelem během provozu. Pásmo 5 GHz a 6 GHz může podléhat provozním omezením v závislosti na zemi použití. 

##### **Danish (DA):** 

Oprethold en minimumsafstand på 20 cm mellem enheden og brugeren under drift. 5 GHz og 6 GHz-båndet kan være underlagt driftsmæssige begrænsninger afhængigt af brugslandet. 

##### **Dutch (NL):** 

Houd tijdens gebruik een minimale afstand van 20 cm tussen het apparaat en de gebruiker aan. De 5GHz en 6 GHzband kan onderhevig zijn aan gebruiksbeperkingen afhankelijk van het land van gebruik. 

##### **Estonian (ET):** 

Hoidke seadme ja kasutaja vahel töötamise ajal vähemalt 20 cm kaugust. 5 GHz ja 6 GHz sagedusribale võivad kehtida kasutuspiirangud sõltuvalt kasutusriigist. 

##### **Finnish (FI):** 

Pidä laitteen ja käyttäjän välillä vähintään 20 cm etäisyys käytön aikana. 5 GHz:n ja 6 GHz:n taajuusalueilla voi olla käyttörajoituksia käyttömaasta riippuen. 

##### **French (FR):** 

Maintenez une distance minimale de 20 cm entre l’appareil et l’utilisateur pendant son fonctionnement. Les bandes de fréquences 5 GHz et 6 GHz peuvent être soumises à des restrictions d'utilisation selon le pays où tu t'en sers. 

##### **German (DE):** 

Halten Sie während des Betriebs einen Mindestabstand von 20 cm zwischen dem Gerät und dem Benutzer ein. Für die Frequenzen 5 GHz und 6 GHz können je nach Einsatzland Nutzungsbeschränkungen unterliegen. 

##### **Greek (EL):** 

Διατηρείτε ελάχιστη απόσταση 20 cm μεταξύ της συσκευής και του χρήστη κατά τη λειτουργία. Οι ζώνες συχνοτήτων των 5 GHz και 6 GHz ενδέχεται να υπόκεινται σε περιορισμούς λειτουργίας, ανάλογα με τη χώρα 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**53 / 62** 

```
Arduino® VENTUNO™ Q
```

##### χρήσης. 

##### **Hungarian (HU):** 

A működés során tartson legalább 20 cm távolságot az eszköz és a felhasználó között. Az 5 GHz-es és 6 GHz-es frekvenciasáv használatára a országonként különböző üzemeltetési korlátozások vonatkozhatnak. 

##### **Irish (GA):** 

Coinnigh ar a laghad fad 20 cm idir an gléas agus an t-úsáideoir le linn úsáide. D'fhéadfadh go mbeadh srianuimh oibríochtúla i bhfeidhm ar an mbanda minicíochta 5 GHz agus 6 GHz ag brath ar an tír ina n-úsáidtear é. 

##### **Italian (IT):** 

Mantenere una distanza minima di 20 cm tra il dispositivo e l’utente durante il funzionamento. Le bande di frequenza a 5 GHz e 6GHz possono essere soggette a restrizioni operative a seconda del paese. 

##### **Latvian (LV):** 

Uzturiet vismaz 20 cm attālumu starp ierīci un lietotāju darbības laikā. 5 GHz un 6 GHz frekvenču joslā var tikt piemēroti ekspluatācijas ierobežojumi atkarībā no izmantošanas valsts. 

##### **Lithuanian (LT):** 

Naudojimo metu laikykite bent 20 cm atstumą tarp įrenginio ir naudotojo. 5 GHz ir 6 GHz dažnių juostose gali būti taikomi naudojimo apribojimai, priklausomai nuo šalies, kurioje naudojamas įrenginys. 

##### **Maltese (MT):** 

Żomm distanza minima ta’ 20 cm bejn l-apparat u l-utent waqt l-użu. Il-medda tal-frekwenza 5 GHz u 6 GHz tista’ tkun soġġetta għal restrizzjonijiet skont il-pajjiż. 

##### **Polish (PL):** 

Podczas pracy zachowaj minimalną odległość 20 cm między urządzeniem a użytkownikiem. Pasma częstotliwości 5 GHz i 6 GHz mogą podlegać ograniczeniom eksploatacyjnym w zależności od kraju, w którym są używane. 

##### **Portuguese (PT):** 

Mantenha uma distância mínima de 20 cm entre o dispositivo e o utilizador durante o funcionamento. As bandas de frequência de 5 GHz e 6 GHz podem estar sujeitas a restrições de utilização dependendo do país. 

##### **Romanian (RO):** 

Mențineți o distanță minimă de 20 cm între dispozitiv și utilizator în timpul funcționării. Banda de frecvență de 5 GHz și 6 GHz poate face obiectul unor restricții în funcție de țara de utilizare. 

##### **Slovak (SK):** 

Počas prevádzky dodržiavajte minimálnu vzdialenosť 20 cm medzi zariadením a používateľom. Pásmo frekvencií 5 GHz a 6 GHz môže podliehať prevádzkovým obmedzeniam v závislosti od krajiny, v ktorej sa zariadenie používa. 

##### **Slovenian (SL):** 

Med delovanjem ohranjajte najmanj 20 cm razdalje med napravo in uporabnikom. Frekvenčni pasovi 5 GHz in 6 GHz so lahko predmet omejitev uporabe, odvisno od države uporabe. 

##### **Spanish (ES):** 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**54 / 62** 

```
Arduino® VENTUNO™ Q
```

Mantenga una distancia mínima de 20 cm entre el dispositivo y el usuario durante su funcionamiento. Las bandas de frecuencia de 5 GHz y 6 GHz pueden estar sujetas a restricciones según el país de uso. 

##### **Swedish (SV):** 

Håll ett minsta avstånd på 20 cm mellan enheten och användaren under drift. 5 GHz- och 6 GHz-frekvensbanden kan vara föremål för driftsbegränsningar beroende på användningsland. 

## **`13 ESD Warning`** 

This product is a development board that contains ESD-sensitive components. Appropriate anti-static precautions should be taken when handling the device. Avoid touching exposed connectors, pins, or circuitry. Where a heatsink is installed, handle the board by the heatsink to minimise the risk of electrostatic discharge damage. Improper handling or exposure to electrostatic discharge may result in permanent damage to the product. 

## **`14 Antenna Use and Compliance`** 

This product is approved to operate with the built-in (internal) antenna only 

The internal antenna is part of the certified module configuration and must be used for normal operation RF connectors may be present for development or testing purposes only 

   - Use of an external antenna is not part of the approved configuration External antenna use requires additional regulatory assessment before use 

- **`14.1 Warning - External Antenna Use`** 

   - Connecting an external antenna may result in non-compliance with regulatory requirements This includes the module approval associated with FCC ID J9C-QCNFA725 Use of an external antenna may change RF output power Use of an external antenna may change frequency behavior 

   - Use of an external antenna may change radiation characteristics These changes may cause the product to exceed allowed regulatory limits Use of an external antenna may invalidate device approval Use of an external antenna may void the authorization to operate the device Unauthorized changes, including antenna modifications, may void regulatory approvals 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**55 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`14.2 Requirements for Integrators`** 

End products must use the internal antenna to maintain regulatory compliance 

- If an external antenna is used, the integrator must perform a full regulatory assessment 

- If an external antenna is used, the integrator must obtain required certifications for the final product 

- Any antenna used must meet the approved gain, radiation pattern, and performance characteristics Approved antenna characteristics are defined in the applicable regulatory documentation, including the Qualcomm module label guide 

#### **`14.3 Operation in the 6 GHz Band`** 

Operation in the 6 GHz band is only permitted with the approved internal antenna configuration If an external antenna is used, 6 GHz operation must be disabled 

If an external antenna is used, the product must not transmit in the 6 GHz band 

Operation outside the approved configuration may violate regional regulations 

#### **`14.4 Responsibility`** 

- The manufacturer or integrator is responsible for ensuring the final product complies with all applicable regulatory requirements 

Changes to the antenna system or RF design may require additional testing and certification 

# **`Certifications`** 

## **`15 RED / UK`** 

|**CE**|**Europe - EU Declaration of Conformity**|
|---|---|
|Česky [Czech]|Arduino S.r.l tímto prohlašuje, že tento Radiolan je ve shodě se základními požadavky a<br>dalšímipříslušnými ustanoveními směrnice 2014/53/EU.|
|Dansk [Danish]|Undertegnede Arduino S.r.l erklærer herved, at følgende udstyr Radiolan overholder de<br>væsentlige krav ogøvrige relevante krav i direktiv 2014/53/EU.|
|Deutsch<br>[German]|Hiermit erklärt Arduino S.r.l dass sich das Gerät Radiolan in Übereinstimmung mit den<br>grundlegenden Anforderungen und den übrigen einschlägigen Bestimmungen der Richtlinie<br>2014/53/EU befindet.|
|Eesti [Estonian]|Käesolevaga kinnitab Arduino S.r.l seadme Radiolan vastavust direktiivi 2014/53/EU<br>põhinõueteleja nimetatud direktiivist tulenevatele teistele asjakohastele sätetele.|
|English|Hereby, Arduino S.r.l, declares that this Radiolan is in compliance with the essential<br>requirements and other relevantprovisions of Directive 2014/53/EU.|
|Español<br>[Spanish]|Por medio de la presente Arduino S.r.l declara que el Radiolan cumple con los requisitos<br>esencialesycualesquiera otras disposiciones aplicables o exigibles de la Directiva 2014/53/EU.|
|Ελληνική [Greek]|ΜΕ ΤΗΝ ΠΑΡΟΥΣΑ Arduino S.r.l ΔΗΛΩΝΕΙ ΟΤΙ Radiolan ΣΥΜΜΟΡΦΩΝΕΤΑΙ ΠΡΟΣ ΤΙΣ<br>ΟΥΣΙΩΔΕΙΣ ΑΠΑΙΤΗΣΕΙΣ ΚΑΙ ΤΙΣ ΛΟΙΠΕΣ ΣΧΕΤΙΚΕΣ ΔΙΑΤΑΞΕΙΣ ΤΗΣ ΟΔΗΓΙΑΣ 2014/53/EU.|
|Français [French]|Par la présente Arduino S.r.l déclare que l'appareil Radiolan est conforme aux exigences<br>essentielles et aux autres dispositionspertinentes de la directive 2014/53/EU.|
|Íslenska<br>[Icelandic]|Hér með lýsir Arduino S.r.l yfir því að Radiolan er í samræmi við grunnkröfur og aðrar kröfur,<br>semgerðar eru í tilskipun 2014/53/EU.|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**56 / 62** 

```
Arduino® VENTUNO™ Q
```

|**CE**|**Europe - EU Declaration of Conformity**|
|---|---|
|Italiano [Italian]|Con la presente Arduino S.r.l dichiara che questo Radiolan è conforme ai requisiti essenziali<br>ed alle altre disposizionipertinenti stabilite dalla direttiva 2014/53/EU.|
|Latviski [Latvian]|Ar šo Arduino S.r.l deklarē, ka Radiolan atbilst Direktīvas 2014/53/EU būtiskajām prasībām un<br>citiem ar to saistītajiem noteikumiem.|
|Lietuvių<br>[Lithuanian]|Šiuo Arduino S.r.l deklaruoja, kad šis Radiolan atitinka esminius reikalavimus ir kitas<br>2014/53/EU Direktyvos nuostatas.|
|Malti [Maltese]|Hawnhekk, Arduino S.r.l, jiddikjara li dan Radiolan jikkonforma mal-ħtiġijiet essenzjali u ma<br>provvedimenti oħrajn relevanti li hemm fid-Dirrettiva 2014/53/EU.|
|Magyar<br>[Hungarian]|Alulírott, Arduino S.r.l nyilatkozom, hogy a Radiolan megfelel a vonatkozó alapvetõ<br>követelményeknek és az 2014/53/EU irányelv egyéb elõírásainak.|
|Nederlands<br>[Dutch]|Hierbij verklaart Arduino S.r.l dat het toestel Radiolan in overeenstemming is met de<br>essentiële eisen en de andere relevante bepalingen van richtlijn 2014/53/EU.|
|Norsk<br>[Norwegian]|Arduino S.r.l erklærer herved at utstyret Radiolan er i samsvar med de grunnleggende krav og<br>øvrige relevante krav i direktiv 2014/53/EU.|
|Polski [Polish]|Niniejszym Arduino S.r.l oświadcza, że Radiolan jest zgodny z zasadniczymi wymogami oraz<br>pozostałymi stosownymipostanowieniami Dyrektywy2014/53/EU.|
|Português<br>[Portuguese]|Arduino S.r.l declara que este Radiolan está conforme com os requisitos essenciais e outras<br>disposições da Directiva 2014/53/EU.|
|Slovensko<br>[Slovenian]|Arduino S.r.l izjavlja, da je ta Radiolan v skladu z bistvenimi zahtevami in ostalimi relevantnimi<br>določili direktive 2014/53/EU.|
|Slovensky<br>[Slovak]|Arduino S.r.l týmto vyhlasuje, že Radiolan spĺňa základné požiadavky a všetky príslušné<br>ustanovenia Smernice 2014/53/EU.|
|Suomi [Finnish]|Arduino S.r.l vakuuttaa täten että Radiolan tyyppinen laite on direktiivin 2014/53/EU<br>oleellisten vaatimustenja sitä koskevien direktiivin muiden ehtojen mukainen.|
|Svenska<br>[Swedish]|Härmed intygar Arduino S.r.l att denna Radiolan står I överensstämmelse med de väsentliga<br>egenskapskrav och övriga relevanta bestämmelser som framgår av direktiv 2014/53/EU.|
|**UK**|**United Kingdom - UKCA Declaration of Conformity**|
|United Kingdom|Hereby, Arduino S.r.l, declares that this Radiolan is in compliance with the essential<br>requirements and other relevantprovisions of The Radio Equipment Regulations 2017.|



Requirements in: 

Belgium (BE), Bulgaria (BG), Czech Republic (CZ), Denmark (DK), Germany (DE), Iceland (IS), Estonia (EE), Ireland (IE), Greece (EL), Spain (ES), France (FR), Croatia (HR), Italy (IT), Cyprus (CY), Latvia (LV), Liechtenstein (LI), Lithuania (LT), Luxembourg (LU), Hungary (HU), Malta (MT), Netherlands (NL), Norway (NO), Austria (AT), Poland (PL), Portugal (PT), Romania (RO), Slovenia (SI), Slovakia (SK), Turkey (TR), Finland (FI), Sweden (SE), Switzerland (CH), United Kingdom (North Irland) (UK(NI)), and United Kingdom (UK). 

Operations in the 5.15-5.35GHz band are restricted to indoor usage only. 

For Low power indoor (LPI use): Operations in the 5955 - 6415MHz are restricted to indoor usage only. 

This equipment should be installed and operated with a minimum distance of 20 cm between the radiator and your body. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**57 / 62** 

```
Arduino® VENTUNO™ Q
```

#### **`15.1 Radio Equipment Information (RED Compliance)`** 

This radio equipment operates in the following frequency bands and with the maximum radio-frequency power indicated below: 

|**Radio Technology**|**Frequency Band**|**Maximum Transmit Power**|
|---|---|---|
|Bluetooth® EDR|2400 - 2483.5 MHz|18.31 dBm|
|Bluetooth® LE|2400 - 2483.5 MHz|9.97 dBm|
|Wi-Fi® 2.4 GHz|2400 - 2483.5 MHz|19.91 dBm EIRP|
|Wi-Fi® 5 GHz|5150 - 5350 MHz|22.92 dBm EIRP|
|Wi-Fi® 5 GHz|5470 - 5725 MHz|22.97 dBm EIRP|
|Wi-Fi® 5 GHz|5725 - 5850 MHz|13.84 dBm EIRP|
|Wi-Fi® 6 GHz (LPI client)|5945 - 6425 MHz|22.83 dBm EIRP|
|Wi-Fi® 6 GHz (VLP)|5945 - 6425 MHz|13.77 dBm EIRP|



In accordance with EU regulations (RED Directive 2014/53/EU), the use of the 5 GHz band may be subject to national restrictions. 

## **`16 UKCA Declaration of Conformity`** 

Arduino S.r.l. hereby declares that this product is in compliance with the essential requirements and other relevant provisions of the applicable UK regulations. A copy of the UK Declaration of Conformity is available at: https://docs.arduino.cc/certifications 

## **`17 FCC`** 

Contains FCC ID: J9C-QCNFA725 

##### **FCC Compliance Information** 

This device complies with Part 15 of the FCC Rules. Operation is subject to the following two conditions: (1) this device may not cause harmful interference, and (2) this device must accept any interference received, including interference that may cause undesired operation. 

This product does not contain any user serviceable components. Any unauthorized product changes or modifications will invalidate warranty and all applicable regulatory certifications and approvals, including authority to operate this device. 

##### **FCC Part 15 Digital Emissions Compliance** 

We Arduino S.r.l. - Via Andrea Appiani 25, 20900 Monza (Italy), declare under our sole responsibility that the product Arduino® VENTUNO Q complies with Part 15 of the FCC Rules. Operation is subject to the following two conditions: (1) this device may not cause harmful interference, and (2) this device must accept any interference received, including interference that may cause undesired operation. 

**WARNING:** This equipment has been tested and found to comply with the limits for a Class B digital device, pursuant to Part 15 of the FCC Rules. These limits are designed to provide reasonable protection against harmful 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**58 / 62** 

```
Arduino® VENTUNO™ Q
```

interference in a residential installation. This equipment generates and radiates radio frequency energy and, if not installed and used in accordance with the instructions, may cause harmful interference to radio communications. 

However, there is no guarantee that interference will not occur in a particular installation. If this equipment does cause harmful interference to radio or television reception, which can be determined by turning the equipment off and on, the user is encouraged to try to correct the interference by one or more of the following measures: 

- Reorient or relocate the receiving antenna. 

- Increase the separation between the equipment and receiver. 

- Connect the equipment into an outlet on a circuit different from the one the receiver is connected to. Consult the dealer or an experienced radio/TV technician for help. 

The user may find the following booklet prepared by the Federal Communications Commission helpful: 

##### **The Interference Handbook** 

This booklet is available from the U.S. Government Printing Office, Washington, D.C. 20402. Stock No.004-00000345-4. 

##### **Radiation Exposure Statement** 

1. This transmitter must not be co-located or operating in conjunction with any other antenna or transmitter. 

2. This equipment complies with RF radiation exposure limits set forth for an uncontrolled environment. This equipment should be installed and operated, keeping the radiator at least 20cm or more away from the person's body. 

##### **FCC 6 GHz Statement** 

a. The operation of this device is prohibited on oil platforms and aircraft, except that operation of this device in 5.925-6.425 GHz is permitted in large aircraft while flying above 10,000 feet. 

b. Installation on outdoor fixed infrastructure is prohibited. 

c. Controlling or communications with unmanned aircraft systems, including drones, is prohibited. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**59 / 62** 

```
Arduino® VENTUNO™ Q
```

## **`18 ISED`** 

##### Contains IC: 2723A-QCNFA725 

##### _English:_ 

This device complies with Canadian RSS-247. This device complies with Industry Canada license-exempt RSS standard(s). Operation is subject to the following two conditions: (1) this device may not cause interference, and (2) this device must accept any interference, including interference that may cause undesired operation of the device. 

##### _French:_ 

Ce dispositif est conforme à la norme CNR-247 d'Industrie Canada applicable aux appareils radio exempts de licence. Son fonctionnement est sujet aux deux conditions suivantes: (1) le dispositif ne doit pas produire de brouillage préjudiciable, et (2) ce dispositif doit accepter tout brouillage reçu, y compris un brouillage susceptible de provoquer un fonctionnement indésirable. 

##### _English:_ 

##### Caution: 

(i) the device for operation in the band 5150-5250 MHz is only for indoor use to reduce the potential for harmful interference to co-channel mobile satellite systems; 

(ii) Users should also be advised that high-power radars are allocated as primary users (i.e. priority users) of the bands 5250-5350 MHz and 5650-5850 MHz and that these radars could cause interference and/or damage to LELAN devices. 

##### _French:_ 

Avertissement : 

Le guide d'utilisation des dispositifs pour réseaux locaux doit inclure des instructions précises sur les restrictions susmentionnées, notamment : 

(i) les dispositifs fonctionnant dans la bande 5 150-5 250 MHz sont réservés uniquement pour une utilisation à l'intérieur afin de réduire les risques de brouillage préjudiciable aux systèmes de satellites mobiles utilisant les mêmes canaux ; 

(ii) Les radars à haute puissance sont désignés comme utilisateurs principaux (c'est-à-dire utilisateurs prioritaires) des bandes de fréquences 5250-5350 MHz et 5650-5850 MHz. Ces radars peuvent causer des interférences et/ou endommager les dispositifs LE-LAN. 

**Note:** For 5GHz and/or when co-located with 5 GHz transmitters, the following statements should be provided in the user information. 

##### **Radiation Exposure Statement** 

1. To comply with the Canadian RF exposure compliance requirements, this device and its antenna must not be co-located or operating in conjunction with any other antenna or transmitter. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**60 / 62** 

```
Arduino® VENTUNO™ Q
```

2. To comply with RSS 102 RF exposure compliance requirements, this equipment should be installed and operated, keeping the radiator at least 20cm or more away from the person's body. 

##### **Déclaration d'exposition aux rayonnements** 

1. Pour se conformer aux exigences de conformité RF canadienne l'exposition, cet appareil et son antenne ne doivent pas être co-localisés ou fonctionnant en conjonction avec une autre antenne ou transmetteur. 

2. Pour se conformer aux exigences de conformité CNR 102 RF exposition, cet équipement doit être installé et utilisé en maintenant le radiateur à au moins 20cm ou plus du corps de la personne. 

##### **6 GHz General statement** 

_English:_ 

Devices shall not be used for control of or communications with unmanned aircraft systems. Devices shall not be used on oil platforms. Devices shall not be used on aircraft, except for the low-power indoor access points, indoor subordinate devices, low-power client devices, and very low-power devices operating in the 5925-6425 MHz band, that may be used on large aircraft as defined in the Canadian Aviation Regulations, while flying above 3,048 metres (10,000 feet). 

##### _French :_ 

Les dispositifs ne doivent pas être utilisés pour commander des systèmes d'aéronef sans pilote ni pour communiquer avec de tels systèmes; Les dispositifs ne doivent pas être utilisés sur les plateformes de forage pétrolier; Les dispositifs ne doivent pas être utilisés dans les aéronefs, à l'exception des points d'accès intérieurs de faible puissance, des dispositifs subordonnés intérieurs, des dispositifs clients de faible puissance et des dispositifs de très faible puissance fonctionnant dans la bande de 5 925 à 6 425 MHz, qui peuvent être utilisés dans les gros aéronefs tel qu'il est défini dans le Règlement de l'aviation canadien, et ce, lorsqu'ils volent à une altitude supérieure à 3 048 mètres (10 000 pieds). 

## **`19 Trademarks`** 

The terms HDMI, HDMI High-Definition Multimedia Interface, HDMI trade dress and the HDMI Logos are trademarks or registered trademarks of HDMI Licensing Administrator, Inc. 

Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**61 / 62** 

```
Arduino® VENTUNO™ Q
```

# **`Company Information`** 

|**Company name**|**Arduino S.r.l.**|
|---|---|
|Address|Via Andrea Appiani 25, 20900 Monza (Italy)|



# **`Documentation Reference`** 

|**No.**|**Reference**|**Link**|
|---|---|---|
|1|Arduino AppLab|https://www.arduino.cc/en/software|
|2|VENTUNO Q Documentation|https://docs.arduino.cc/hardware/ventuno-q/|
|3|Project Hub|https://projecthub.arduino.cc/|
|4|LibraryReference|https://docs.arduino.cc/libraries/|
|5|Arduino Store|https://store.arduino.cc/|



# **`Document Revision History`** 

|**Date**|**Revision**|**Changes**|
|---|---|---|
|25/08/2026|1|First release|
|28/08/2026|2|Updated Certifications|
|31/08/2026|3|Adding6 GHz to SafetyInformation|
|29/09/2026|4|Updatingvalues for inputs|



Modified: 06/10/2026 

Arduino® VENTUNO™ Q 

**62 / 62** 

