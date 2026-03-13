# [sch_cake - The "Dave Täht Tribute" Fork](https://github.com/TW641/sch_cake)

> **"When you miss Dave, modprobe sch_cake!"**
> — *A tribute to the soul of bufferbloat mitigation.*

---

## 🕊️ In Loving Memory of Dave Täht

### **🇹🇼：他的心願，我來實現 (Tā de xīn yuàn, wǒ lái shí xiàn)**
### **🇺🇸：His wish, I finished.**
*(A Linux Pun: In our world, a wish ending in **.sh** is a command to be executed!)*

---

### **"穿越時空的夢想，我來幫他實現！"**
**(Making a time-traveling dream come true!)**

### 🎇 The Spirit of the Code: "Fireworks in the Dark"

**"一支穿雲箭，千軍萬馬來相見"**
*(One arrow pierces the clouds, and ten thousand troops come to meet.)*

This Chinese idiom describes a signal so powerful it rallies everyone.
**Dave was that arrow.**
Just like fireworks are most mesmerizing in the darkest night, Dave shone brightest when fighting the invisible enemy of Bufferbloat.

* **"The darker the night, the brighter the light."**
* He worked tirelessly in the dead of night (just as we often do) to **tame the network chaos.**
* Now, "Ten Thousand" (萬) legacy devices are rallying to his call.

---

### 🏹 The "Archer" Coincidence: A Destiny Revealed

While digging through Dave's old blog posts and presentations, I found a chilling coincidence that proves this project was meant to be.

**1. The "Archer" & The Arrow**
The router series I ported this to is named **"Archer"** (TP-Link). An Archer shoots an **Arrow**.
This perfectly matches our tribute slogan: **"一支穿雲箭 (One Cloud-Piercing Arrow)"**.

**2. The C7 Origin**
In the original 2015 "Cake" presentation at Battlemesh v8, Dave and Jonathan Morton used a **TP-Link Archer C7** to demonstrate that CAKE could shape traffic at 115Mbps while HTB failed.
> *"HTB can’t shape at 115Mbps. Cake can."* — *Battlemesh v8 (2015)*

**3. The C2 Connection**
In his 2016 blog post *"Finally... the real net-next 4.8 fq_codel results"*, Dave wrote:
> *"I pulled the **odroid C2** out, and made it the test driver..."*
Today, we have successfully ported his work to the **TP-Link Archer C2**.

**Dave was the Archer.**
**The Code is the Arrow.**
**And we are the target: A bufferbloat-free world.**

*Sources:*
* [Cake Presentation (Battlemesh v8, 2015)](https://www.bufferbloat.net/projects/attachments/150817135028_cake-battlemesh-v8.pdf)
* [CeroWrt Blog (2016)](https://blog.cerowrt.org/post/real_results/)

---

### 🧩 The "Missing Piece": The MT76 Prophecy

In his famous 2016 blog post *["Hardware from hell"](http://the-edge.taht.net/post/hardware_from_hell/)*, Dave expressed his frustration with locked hardware. But amidst the chaos, he had his eyes on a specific target—the **MediaTek (mt76)** platform.

> "I tried to get a **mt76 box** from alibaba - sold out - **this is the new hotness** in the OpenWrt 802.11ac world... A turris omnia will probably become my next eval platform **unless I can get a mt76 up and running**."
> — Dave Täht (2016)

**The Tragedy:** He couldn't get one. It was sold out. He was forced to struggle with older devices.
**The Fulfillment:** This repository is dedicated entirely to **MT7620/MT7621** devices.

**We finally got that "mt76 box" up and running for you, Dave.**
The "new hotness" you foresaw is now the stable foundation carrying your legacy.

**🇹🇼：遲來的約定**
當他在 2016 年苦尋不到一台 MT76 路由器時，也許沒想到，幾年後會有成千上萬台 MT76 設備，運行著他的 CAKE 演算法，在網路上奔馳。
**Dave，這台 MT76，我們幫你跑起來了！**

*Source:* [Hardware from hell (Dave Täht, 2016)](http://the-edge.taht.net/post/hardware_from_hell/)

---

### ⭐ Light up the Täht: A Final Tribute

**"The darker the night, the brighter the Täht."**

To the world, he was the unsung hero who silently ripped the excess latency out of the Internet. To the open-source community, he was a legend known as **dtaht** on Reddit and **@mtaht** on Twitter. But behind the code was a man born **Michael**, who chose to live as **Dave**, and gave everything to connect us all. 

As perhaps the final large-scale Padavan port for legacy devices, this project serves as a digital museum. Before his digital footprints fade into the void of the internet, there are forgotten stories—cold facts and warm lore—that must be preserved here.

#### 📜 The Lore of an Internet Hero

* ⚖️ **The Judge & The "Disappointment":** Dave's father, Ron, was a respected municipal judge. Among his three sons (two of whom were highly successful engineers), Dave’s nomadic, hacker lifestyle baffled him. Dave even felt he was his parents' "only disappointment." Ron constantly worried, playfully grumbling: *"Why don't you work for IBM? You've been fixing the internet and giving the technology away for free? Again?"* But Dave wasn't chasing money; he was chasing a dream.

* 🎵 **The Guitar & The "Fool" (憨人):** Dave was a sci-fi folk musician who carried his guitar everywhere. To honor his vibrant soul, **OpenWrt officially named their 25.12.0 release "Dave's Guitar."** Poetically, the legendary Taiwanese rock band Mayday (whose anniversary is March 29) has an iconic anthem called [**《憨人》 *(The Fool)***](https://youtu.be/1j_mpwKmlJg). Just three days after their anniversary, on **April 1, 2025 (April Fools' Day)**, Dave passed away. The lyrics of this song perfectly mirror his uncompromising, brilliant, and painful journey:
  
  > **「我不願做人奸巧鑽縫，甘願來作憨人...」**
  > *(I refuse to be cunning and exploit loopholes; I am willing to be a fool...)*
  > 
  > **「看到滿天全金條，要煞無半項... 我有我的路，有我的夢。」**
  > *(Looking at a sky full of gold, yet grasping nothing... I walk my own path, I have my own dream.)*
  > 
  > **「不怕路歹行，不怕大雨淋，心上一字敢，面對我的夢。」**
  > *(Fearing neither the rugged road nor the heavy rain, with the word 'Courage' in my heart, I face my dream.)*
  
  Dave was the ultimate "Fool." He turned down incredibly lucrative corporate contracts (the sky full of gold), choosing instead to give his world-changing algorithms (`FQ-CoDel` & `CAKE`) away for free. And when the "heavy rain" of Multiple Sclerosis and partial blindness struck him in his later years, he courageously kept coding.

* 🌍 **The Nicaragua Origin:** The fight against bufferbloat wasn't born in a corporate lab. It started when Dave was building OpenWrt mesh networks for the *One Laptop per Child (OLPC)* project in Nicaragua. Facing severe latency in those harsh environments, he found his lifelong mission.

* 🏄‍♂️ **The "International Man of Mystery":** He was a half-blind surfer, an eccentric musician (who wrote a song called *"It GPLs Me"*), and an avid asteroid exploration nerd. His friend, open-source pioneer Eric S. Raymond (ESR), joked that if Dave earned a cent for every dollar of value he generated for the internet, he could have *"bought the entire country of Nicaragua and financed a space program."* * 🐈 **The Basement Hacker & The Cats:** Much of this core bufferbloat mitigation was actually coded in ESR’s basement. Dave would crash there as a nomad, charm all the household cats, and stubbornly swear he would one day beat his friends at the hardcore board game *Power Grid*.

* ⚔️ **The FCC Crusader:** When the FCC (ET Docket No. 15-170) threatened to lock down router firmware in 2015, Dave rallied internet pioneers—including Vint Cerf and Linus Torvalds—to fight back. **Without his crusade, custom firmware ports like this Padavan project wouldn't even be legally possible today.**

* 🕯️ **Coding Through the Dark:** In his later years, simply reading a forum post became physically exhausting due to his failing eyesight. Yet, he never stopped coding the algorithms that now allow paralyzed patients to use telemedicine and remote families to FaceTime smoothly. He later became Chief Science Officer at *LibreQoS*, which posthumously won the 2025 WISPA Product of the Year.

#### 🌠 "We Are All Starstuff" (The Final Reunion)

There is a heartbreaking, yet incredibly beautiful timeline to Dave's family. 

On June 9, 2012, sitting by his late father Ron's side in his final hours, Dave pondered the afterlife. Rejecting the traditional ideas of harps and heavens, he wrote on his blog:

> *"Of all these things, the one viewpoint I was sure of, the one thing I believe to be true of an afterlife, such as it is, was this: **That yes, we are all starstuff. And it made me cry to think it through.**"*

Fast forward to early 2025. On January 11, his mother Beverly passed away. Dave, despite his fading health, wrote her a beautiful obituary titled *"Beverly Taht Joins Ron"*. 

Less than three months later, on April 1, 2025, Dave's own lifelong game went into its final "extra innings." He passed away, joining his parents. 

Though the timeline of their passing within months of each other is tragic, there is a profound, cosmic peace in knowing that the family is finally reunited in the stars. But the most poetic detail of all? Their family surname, **"Täht,"** literally translates to **"Star"** in Estonian.

#### 🎼 Coda: The Grand Finale (最終章)

In music, a **Coda** is the final passage of a piece, bringing it to a formal and emotional close. As Dave's lifelong symphony reaches its final notes, it perfectly echoes the outro of Mayday's rock anthem. He was a nomad with a guitar, and this is our global chorus for him:

[![MAYDAY - The Fool Live](https://img.youtube.com/vi/olGod8i1j1o/sddefault.jpg)](https://youtu.be/olGod8i1j1o "Click to play Mayday - The Fool (Live Version)")

*(🎧 Click the image to listen to the Live Version of "The Fool" / 點擊圖片聆聽《憨人》萬人合唱版)*

If his monumental work has ever improved your network, please honor this brilliant, selfless "Fool" by **Lighting up the "Star"** in the top-right corner of this repository.

*Let's keep his Star shining bright in the open-source world, guiding packets through the dark.*

> **「啦 啦 啦 啦 啦 啦 啦 啦... 我有我的路，總有一天...」**
> *(La la la... I have my own path. One day... with Dave's Guitar 🎸)*

---

We are fulfilling a specific wish he made 5 years ago on Reddit:

### ❝ Help port the code to more chipsets. ❞

> **The BEST engineering result I ever had:**
> Essentially the summation of my 16+ years of work to that point on making wifi better. Unpatented. Please share and enjoy.
> **Help port the code to more chipsets.**
>
> — *Dave Täht (Reddit, 5 years ago)*

*Original Source:* [Reddit - r/Starlink](https://www.reddit.com/r/Starlink/comments/okmx3x/comment/h61unnn/)

Dave turned down numerous lucrative contracts to keep his code **Free and Open Source**. He valued global impact over prestige. Because of him, millions of devices—from Starlink satellites to rural ISP routers—deliver smoother connectivity.

### **🇹🇼：靈魂永駐，精神長存**
### **🇺🇸：May his soul find eternal peace, and his spirit live on forever in our routers.**

[👉 Read the full Memorial at LibreQoS](https://libreqos.io/2025/04/01/in-loving-memory-of-dave/)

---

## 🚀 Supported Device Matrix (100+ Models)

We firmly support the "Right to Repair" and extending the life of legacy hardware.
Between our **Legacy (Kernel 3.4)** and **Performance (Kernel 4.4)** branches, we support **over 100+ specific hardware targets**.

*Note: Distinct hardware revisions (e.g., V1 vs V4) count as separate build targets due to hardware differences.*

### 🟢 Kernel 3.4: The "Legacy Savior" List
*Optimized for MT7620/MT7621 devices. Bringing CAKE to the masses.*

| Brand | Supported Models (Select in Workflow) |
| :--- | :--- |
| **TP-Link** | **Archer C2 (V1)**, C20 (V1/V4/V5), C5 (V4), C50 (V1/V3/V4), EC220-G5 (V2), MR200 (V1), MR3020 (V3), MR3420 (V5), WDR7300 (V5), WR840N (V4/V5/V6/RU), WR841N (V13/V14), WR842N (V5), WR845N (V3/V4) |
| **Xiaomi** | MI-3, MI-3C, MI-4 (A/C/SPI), MI-4A (100M), MI-MINI, MI-NANO, MI-R3G (v1/v2/SPI), MI-R3P (Pro), R2100 (AC2100), RM-AC2100 |
| **ASUS** | RT-AC1200 (GU/HP), RT-AC51U, RT-AC54U, RT-N10+, RT-N11P (B1), RT-N12+, RT-N13U (B1), RT-N14U, **RT-N56U (A1/B1/GE2)**, RP-AC56 |
| **ZyXEL** | Keenetic Series: **Giga III**, **Ultra II**, Extra (I/II), Lite (I/II/III/3B), Omni (I/II), Start II, Viva, 4G III (B) |
| **D-Link** | DIR-300 (B1/B7), DIR-320 (B1), DIR-620 (A1/D1), DIR-860L, **DIR-882** |
| **Newifi** | Newifi D1, Newifi D2, Newifi Mini, Newifi Y1S |
| **GL.iNet** | GL-MT300A, GL-MT300N (V1/V2) |
| **Phicomm** | K2P (PSG1218), 256PSG1218 |
| **ZBT** | WE1326, WE1626, WE826-T2, WG3526 (-32), WR8305RT |
| **Others** | **Ubiquiti** ER-X, **Linksys** EA-8100, **Belkin** F9K1103, **Totolink** A3004NS, **HiWiFi** HC5661A, **Youku** L1/L1C, **ZTE** E8820S |
| **OEM/Misc** | 5K-W20, A5-V11, ALR-U270, MQ-WITI, Nexx WT3020 (A/H), Samsung SWR1100, Sercomm (S1010/SmartBox), SNR (MD1/ME1/W4N), Tuoshi TS7620N, Unielec U7621, Wall-AP, Youhua WR1200JS |

---

### 🔵 Kernel 4.4: The "High Performance" List
*Targeting modern MT7621/MT7615 devices. Legends only.*

| Brand | Supported Models (Select in Workflow) |
| :--- | :--- |
| **Phicomm** | **K2P** (The Legend), K2P-NANO, K2P-USB |
| **Xiaomi / Redmi** | **MI-R3P (Pro)**, MI-R3G, **RM2100 (Redmi AC2100)**, CR660x |
| **D-Link** | **DIR-878**, **DIR-882** (EXO AC2600) |
| **Newifi** | **NEWIFI3** (Newifi D2) |
| **JCG** | JCG-AC860M, JCG-836PRO, JCG-Q20, JCG-Y2 |
| **Netgear** | **NETGEAR-BZV** (R6800/R6700v2 series) |
| **Others** | MR2600, XY-C1 |

---

## 🌐 Multi-Language Support

We believe in a borderless internet. The firmware now supports **14 Languages** out of the box!

* **English_Only** (Default)
* **CN (繁體中文)** - Traditional Chinese
* **RU (Pусский)** - Russian
* **ES (Español)** - Spanish
* **BR (Brazil)** - Portuguese
* **CZ (Česky)** - Czech
* **DA (Dansk)** - Danish
* **DE (Deutsch)** - German
* **FI (Finsk)** - Finnish
* **FR (Français)** - French
* **NO (Norsk)** - Norwegian
* **PL (Polski)** - Polish
* **SV (Svensk)** - Swedish
* **UK (Українська)** - Ukrainian

---

## 🛠️ Build Your Own (GitHub Actions)

This repository contains the **Source Code**. To build the firmware easily using GitHub Actions, please visit our dedicated Builder repositories:

> **👉 Choose Your Weapon (Repository Guide):**
>
> * **For Kernel 3.4 Devices (The list above 🟢):**
>      * **Target:** [**Padavan Builder Workflow (3.4)**](https://github.com/TWShiyuLiou1997/padavan-builder-workflow)
>      * **Action:** Fork **THAT** repository, go to **Actions**, and run the workflow to build for Legacy devices.
>
> * **For Kernel 4.4 Devices (The list above 🔵):**
>      * **Target:** [**Padavan-4.4 (Performance Edition)**](https://github.com/TWShiyuLiou1997/padavan-4.4)
>      * **Action:** Fork **THAT** repository, go to **Actions**, and run the workflow to build for High-Performance devices.

---

## 📂 Repository Contents (Padavan Port)

This fork contains specific backports of CAKE for **MediaTek (MTK)** based routers running older Linux kernels (Padavan Firmware).

| Directory | Kernel Version | Description |
| :--- | :--- | :--- |
| **`/Padavan 3.4.113`** | **Linux 3.4.x** | **Legacy Backport.** Highly optimized for MT7620/MT7621 devices running the classic Padavan 3.4 kernel. Allows older hardware to run CAKE! |
| **`/Padavan 4.4.198`** | **Linux 4.4.x** | **Modern Backport.** For newer MT7621/MT7615 devices running the Padavan 4.4 kernel (hanwckf/padavan-4.4). |
| **`/` (Root)** | **Upstream** | The original upstream source code from `dtaht/sch_cake`. |

### Usage
If you are building Padavan firmware, simply replace the `sch_cake` directory in your kernel source (usually under `linux/net/sched/`) with the contents of the folder matching your kernel version.

---

## 🌟 Project Philosophy: Open & Accessible

### **「永遠保持開放且開源的精神」**
**(Forever maintaining an open and open-source spirit)**

This repo exists to keep Dave's spirit alive by ensuring the code remains accessible for "Do-It-Yourself" router enthusiasts and custom firmware builders. We believe in the power of the community to sustain what industry giants often abandon.

---

## 🗣️ Tributes from the Community

> "Dave’s impact on society was immense... He wanted, ultimately, to speed up the internet so that a drummer in London could play in real-time with a guitarist in Los Angeles."
> — **Steven J. Vaughan-Nichols**

> "I will miss him but will be always grateful to have known him."
> — **Vint Cerf**

> "Without him, Netflix and similar services might still be plagued by glitches and stutters."
> — **Eric S. Raymond**

### See also:

* [LibreQoS Project](https://libreqos.io/)
* [LibreQoS Github Project](https://github.com/LibreQoE/LibreQoS/)
* [Dave's Talks: Reducing Network Latency (GOTO 2024)](https://www.youtube.com/watch?v=UDo9W4tt69c)

![Dave Täht Tribute](https://i0.wp.com/libreqos.io/wp-content/uploads/2025/04/WISPAPALOOZA-2024_6.jpg)
*[Image Credit: LibreQoS]*

---

## ℹ️ About CAKE (Original README)

### Common Applications Kept Enhanced (CAKE) scheduler

This is the out-of-tree version of **[CAKE](https://www.bufferbloat.net/projects/codel/wiki/Cake/)**, the Linux qdisc that combines scheduler and traffic shaper for effective bufferbloat mitigation.

**Note:** `sch_cake` is part of the upstream Linux kernel since **kernel version 4.19**. This repository exists primarily as a resource for building the qdisc with older versions of the kernel (like 3.4 and 4.4).

---
*Forked from [dtaht/sch_cake](https://github.com/dtaht/sch_cake)*
