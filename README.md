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

### ⭐ Light up the Dark: A Final Tribute

**"The darker the night, the brighter the light."**

Did you know? Dave's surname **"Täht"** literally means **"Star"** in Estonian.

If this project helps you, or if you simply want to honor his legacy, please **Light up the "Star"** in the top-right corner of this repository.

Let's keep his Star shining bright in the open-source world, guiding packets through the dark.

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
