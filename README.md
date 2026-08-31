<!--lint ignore awesome-license-->

<div align="center">
	<img width="500" height="350" src="iot_awesome_logo.svg" alt="Awesome">
  <br />
</div>

# Awesome Embedded and IoT Security with stars

> A curated list of awesome resources about embedded and IoT security. The list contains software and hardware tools, books, research papers and more.

Botnets like [Mirai](https://en.wikipedia.org/wiki/Mirai_\(malware\)) have proven that there is a need for more security in embedded and IoT devices. This list shall help beginners and experts to find helpful resources on the topic.\
If you are a beginner, you should have a look at the <ins>*Books*</ins> and <ins>*Case Studies*</ins> sections.\
If you want to start right away with your own analysis, you should give the <ins>*Analysis Frameworks*</ins> a try.
They are easy to use and you do not need to be an expert to get first meaningful results.

> Items marked with :euro: are comercial products.

## Contents

* [Software Tools](#software-tools)
  * [Analysis Frameworks](#analysis-frameworks)
  * [Analysis Tools](#analysis-tools)
  * [Extraction Tools](#extraction-tools)
  * [Support Tools](#support-tools)
  * [Misc Tools](#misc-tools)
* [Hardware Tools](#hardware-tools)
  * [Bluetooth BLE Tools](#bluetooth-ble-tools)
  * [ZigBee Tools](#zigbee-tools)
  * [SDR Tools](#sdr-tools)
  * [RFID NFC Tools](#rfid-nfc-tools)
* [Books](#books)
* [Research Papers](#research-papers)
* [Case Studies](#case-studies)
* [Free Training](#free-training)
* [Websites](#websites)
  * [Blogs](#blogs)
  * [Tutorials and Technical Background](#tutorials-and-technical-background)
  * [YouTube Channels](#youtube-channels)
* [Conferences](#conferences)
* [Contribute](#contribute)
* [License](#license)

## Software Tools

Software tools for analyzing embedded/IoT devices and firmware.

### Analysis Frameworks

* [Routersploit](https://github.com/threat9/routersploit) ⭐ 13,234 | 🐛 97 | 🌐 Python | 📅 2026-05-05 - Framework dedicated to exploit embedded devices.
* [PRET](https://github.com/RUB-NDS/PRET) ⭐ 4,303 | 🐛 73 | 🌐 Python | 📅 2024-08-02 - Printer Exploitation Toolkit.
* [HomePWN](https://github.com/ElevenPaths/HomePWN) ⭐ 930 | 🐛 5 | 🌐 Python | 📅 2022-12-27 - Swiss Army Knife for Pentesting of IoT Devices.
* [Killerbee](https://github.com/riverloopsec/killerbee) ⭐ 848 | 🐛 31 | 🌐 C | 📅 2023-09-12 - Framework for Testing & Auditing ZigBee and IEEE 802.15.4 Networks.
* [HAL – The Hardware Analyzer](https://github.com/emsec/hal) ⭐ 822 | 🐛 19 | 🌐 C++ | 📅 2026-08-28 - A comprehensive reverse engineering and manipulation framework for gate-level netlists.
* [FwAnalyzer](https://github.com/cruise-automation/fwanalyzer) ⭐ 517 | 🐛 3 | 🌐 Go | 📅 2023-10-08 - Analyze security of firmware based on customized rules. Intended as additional step in DevSecOps, similar to CI.
* [EXPLIoT](https://gitlab.com/expliot_framework/expliot) - Pentest framework like Metasploit but specialized for IoT.
* [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) - Full-featured static analysis framework including extraction of firmware, analysis utilizing different plug-ins and comparison of different firmware versions.
  * [Improving your firmware security analysis process with FACT](https://passthesalt.ubicast.tv/videos/improving-your-firmware-security-analysis-process-with-fact/) - Conference talk about FACT :tv:.
* [IoTSecFuzz](https://gitlab.com/invuls/iot-projects/iotsecfuzz) - Framework for automatisation of IoT layers security analysis: hardware, software and communication.

### Analysis Tools

* [Radare2](https://github.com/radare/radare2) ⭐ 24,692 | 🐛 823 | 🌐 C | 📅 2026-08-31 - Software Reverse Engineering framework, also handles popular formats and arbitrary binaries, has an extensive command line toolset.
* [Binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,296 | 🐛 93 | 🌐 Rust | 📅 2026-08-11 - Searches a binary for "interesting" stuff, as well as extracts arbitrary files.
* [emba](https://github.com/e-m-b-a/emba) ⭐ 3,619 | 🐛 19 | 🌐 Shell | 📅 2026-08-31 - Analyze Linux-based firmware of embedded devices.
* [Firmadyne](https://github.com/firmadyne/firmadyne) ⭐ 2,104 | 🐛 107 | 🌐 Shell | 📅 2024-07-21 - Tries to emulate and pentest a firmware.
* [cwe\_checker](https://github.com/fkie-cad/cwe_checker) ⭐ 1,353 | 🐛 29 | 🌐 Rust | 📅 2026-08-20 - Finds vulnerable patterns in binary executables - ELF support for x86, ARM, and MIPS, experimental bare-metal support.
* [Firmwalker](https://github.com/craigz28/firmwalker) ⭐ 1,225 | 🐛 5 | 🌐 Shell | 📅 2023-08-29 - Searches extracted firmware images for interesting files and information.
* [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) ⭐ 476 | 🐛 9 | 🌐 Python | 📅 2020-09-17 - Discovering vulnerabilities in firmware through concolic analysis and function clustering.
* [Trommel](https://github.com/CERTCC/trommel) ⚠️ Archived - Searches extracted firmware images for interesting files and information.
* [Ghidra](https://ghidra-sre.org/) - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.

### Extraction Tools

* [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) ⭐ 1,000 | 🐛 62 | 🌐 C | 📅 2026-02-17 - Extraction tools for several container formats.
* [FACT Extractor](https://github.com/fkie-cad/fact_extractor) ⭐ 90 | 🐛 45 | 🌐 Python | 📅 2026-08-25 - Detects container format automatically and executes the corresponding extraction tool.
* [The SRecord package](http://srecord.sourceforge.net/) - Collection of tools for manipulating EPROM files (can convert lots of binary formats).

### Support Tools

* [JTAGenum](https://github.com/cyphunk/JTAGenum) ⭐ 799 | 🐛 14 | 🌐 C++ | 📅 2023-10-30 - Add JTAG capabilities to an Arduino.
* [OpenOCD](http://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing.

### Misc Tools

* [flashrom](https://github.com/flashrom/flashrom) ⭐ 1,171 | 🐛 80 | 🌐 C | 📅 2026-08-31 - Tool for detecting, reading, writing, verifying and erasing flash chips.
* [Cotopaxi](https://github.com/Samsung/cotopaxi) ⭐ 362 | 🐛 1 | 🌐 Python | 📅 2024-05-31 - Set of tools for security testing of Internet of Things devices using specific network IoT protocols.
* [dumpflash](https://github.com/ohjeongwook/dumpflash) ⭐ 321 | 🐛 21 | 🌐 Python | 📅 2022-03-17 - Low-level NAND Flash dump and parsing utility.
* [Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic) ⭐ 237 | 🐛 8 | 🌐 Python | 📅 2021-04-11 - Decrypt Samsung SSD firmware updates.

## Hardware Tools

* [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like [UART](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) and [JTAG](https://en.wikipedia.org/wiki/JTAG).
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
* [Shikra](https://int3.cc/products/the-shikra) - Detects and interacts with hardware debug ports like UART and JTAG. Among other protocols.
* [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) - Detects JTAG Pinouts fast.
* [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols :euro:.
* [Ikalogic](https://www.ikalogic.com/pages/logic-analyzer-sp-series-sp209) - Alternative to Saleae logic analyzers :euro:.
* [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/) - Open source multi-tool hardware similar to the BusPirate but with NFC capabilities.
* [ChipWhisperer](https://newae.com/chipwhisperer/) - Detects Glitch/Side-channel attacks.
* [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) ⭐ 2,203 | 🐛 81 | 🌐 Python | 📅 2026-08-31 - Tool for exploring and debugging different digital interfaces.
* [J-Link](https://www.segger.com/products/debug-probes/j-link/models/model-overview/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores :euro:.

### Bluetooth BLE Tools

* [UberTooth One](https://greatscottgadgets.com/ubertoothone/) - Open source 2.4 GHz wireless development platform suitable for Bluetooth experimentation.
* [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - Easy to use Bluetooth Low Energy sniffer.

### ZigBee Tools

* [ApiMote](http://apimote.com) - ZigBee security research hardware for learning about and evaluating the security of IEEE 802.15.4/ZigBee systems. Killerbee compatible.
* Atmel RZUSBstick - Discontinued product. Lucky if you have one! - Tool for development, debugging and demonstration of a wide range of low power wireless applications including IEEE 802.15.4, 6LoWPAN, and ZigBee networks. Killerbee compatible.
* [Freakduino](https://freaklabsstore.com/index.php?main_page=product_info\&cPath=22\&products_id=219\&zenid=fpmu2kuuk4abjf6aurt3bjnfk4) - Low Cost Battery Operated Wireless Arduino Board that can be turned into a IEEE 802.15.4 protocol sniffer.

### SDR Tools

* [RTL-SDR](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) - Cheapest SDR for beginners. It is a computer based radio scanner for receiving live radio signals frequencies from 500 kHz up to 1.75 GHz.
* [HackRF One](https://greatscottgadgets.com/hackrf/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz (half-duplex).
* [YardStick One](https://greatscottgadgets.com/yardstickone/) - Half-duplex sub-1 GHz wireless transceiver.
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 100 KHz to 3.8 GHz (full-duplex).
* [BladeRF 2.0](https://www.nuand.com/bladerf-2-0-micro/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 47 MHz to 6 GHz (full-duplex).
* [USRP B Series](https://www.ettus.com/product-categories/usrp-bus-series/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 70 MHz to 6 GHz (full-duplex).

### RFID NFC Tools

* [Proxmark 3 RDV4](https://www.proxmark.com/) - Powerful general purpose RFID tool. From Low Frequency (125kHz) to High Frequency (13.56MHz) tags.
* [ChamaleonMini](http://chameleontiny.com/) - Programmable, portable tool for NFC security analysis.
* [HydraNFC](https://hydrabus.com/hydranfc-1-0-specifications/) - Powerful 13.56MHz RFID / NFC platform. Read / write / crack / sniff / emulate.

## Books

* 2019, Yago Hansen: [The Hacker's Hardware Toolkit: The best collection of hardware gadgets for Red Team hackers, Pentesters and security researchers](https://github.com/yadox666/The-Hackers-Hardware-Toolkit/blob/master/TheHackersHardwareToolkit.pdf) ⭐ 2,176 | 🐛 5 | 📅 2020-09-07
* 2018, Mark Carney: [Pentesting Hardware - A Practical Handbook (DRAFT)](https://github.com/unprovable/PentestHardware) ⭐ 506 | 🐛 2 | 📅 2019-05-29
* 2020, Fotios Chantzis, Evangel Deirme, Ioannis Stais, Paulino Calderon, Beau Woods: [Practical IoT Hacking](https://www.amazon.com/Fotios-Chantzis-ebook/dp/B085BVVSN6/)
* 2020, Jasper van Woudenberg, Colin O'Flynn: [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks](https://nostarch.com/hardwarehacking)
* 2019, Aditya Gupta: [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)
* 2018, Mark Swarup Tehranipoor: [Hardware Security: A Hands-on Learning Approach](https://www.elsevier.com/books/hardware-security/bhunia/978-0-12-812477-2)
* 2018, Qing Yang, Lin Huang [Inside Radio: An Attack and Defense Guide](https://link.springer.com/book/10.1007/978-981-10-8447-8)
* 2017, Aditya Gupta, Aaron Guzman: [IoT Penetration Testing Cookbook](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)
* 2017, Andrew Huang: [The Hardware Hacker: Adventures in Making and Breaking Hardware](https://nostarch.com/hardwarehackerpaperback)
* 2016, Craig Smith: [The Car Hacker's Handbook: A Guide for the Penetration Tester](https://nostarch.com/carhacking)
* 2015, Keng Tiong Ng: [The Art of PCB Reverse Engineering](https://visio-for-engineers.blogspot.com/p/order.html)
* 2015, Nitesh Dhanjan: [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](https://shop.oreilly.com/product/0636920033547.do)
* 2015, Joshua Wright , Johnny Cache: [Hacking Wireless Exposed](https://www.mhprofessional.com/9780071827638-usa-hacking-exposed-wireless-third-edition-group)
* 2014, Debdeep Mukhopadhyay: [Hardware Security: Design, Threats, and Safeguards](https://www.taylorfrancis.com/books/9780429066900)
* 2014, Jack Ganssle: [The Firmware Handbook (Embedded Technology)](https://www.elsevier.com/books/the-firmware-handbook/ganssle/978-0-7506-7606-9)
* 2013, Andrew Huang: [Hacking the XBOX](https://nostarch.com/xboxfree)

## Research Papers

<!--lint ignore match-punctuation-->

* 2020, Oser et al: [SAFER: Development and Evaluation of an IoT Device Risk Assessment Framework in a Multinational Organization](https://dl.acm.org/doi/abs/10.1145/3414173)
* 2019, Agarwal et al: [Detecting IoT Devices and How They Put Large Heterogeneous Networks at Security Risk](https://www.mdpi.com/1424-8220/19/19/4107)
* 2019, Almakhdhub et al: [BenchIoT: A Security Benchmark for the Internet of Things](https://nebelwelt.net/publications/files/19DSN.pdf)
* 2019, Alrawi et al: [SoK: Security Evaluation of Home-Based IoT Deployments](https://alrawi.github.io/static/papers/alrawi_sok_sp19.pdf)
* 2019, Abbasi et al: [Challenges in Designing Exploit Mitigations for Deeply Embedded Systems](https://ieeexplore.ieee.org/abstract/document/8806725)
* 2019, Song et al: [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf)
* 2018, Muench et al: [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
* 2017, O'Meara et al: [Embedded Device Vulnerability Analysis Case Study Using Trommel](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=509271)
* 2017, Jacob et al: [How to Break Secure Boot on FPGA SoCs through Malicious Hardware](https://eprint.iacr.org/2017/625.pdf)
* 2017, Costin et al: [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
* 2016, Kammerstetter et al: [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](https://www.thinkmind.org/download.php?articleid=securware_2016_2_10_30082)
* 2016, Chen et al: [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
* 2016, Costin et al: [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
* 2015, Shoshitaishvili et al:[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://www.ndss-symposium.org/wp-content/uploads/2017/09/11_1_2.pdf)
* 2015, Papp et al: [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
* 2014, Zaddach et al: [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems' Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
* 2014, Alimi et al: [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
* 2014, Costin et al: [A Large-Scale Analysis of the Security of Embedded Firmwares](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
* 2013, Davidson et al: [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

## Case Studies

<!--lint ignore no-repeat-punctuation-->

* [Binary Hardening in IoT products](https://cyber-itl.org/2019/08/26/iot-data-writeup.html)
* [Cracking Linksys “Encryption”](http://www.devttys0.com/2014/02/cracking-linksys-crypto/)
* [Deadly Sins Of Development](https://youtu.be/nXyglaY9N9w) - Conference talk presenting several real world examples on real bad implementations :tv:.
* [Dumping firmware from a device's SPI flash with a buspirate](https://www.iotpentest.com/2019/06/dumping-firmware-from-device-using.html)
* [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
* [Hacking the PS4](https://cturt.github.io/ps4.html) - Introduction to PS4's security.
* [IoT Security@CERN](https://doi.org/10.5281/zenodo.1035034)
* [Multiple vulnerabilities found in the D-link DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
* [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
* [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)
* [Reversing Firmware With Radare](https://www.bored-nerds.com/reversing/radare/automotive/2019/07/07/reversing-firmware-with-radare.html)
* [Reversing the Huawei HG533](http://jcjc-dev.com/2016/04/08/reversing-huawei-router-1-find-uart/)

## Free Training

* [IoTGoat](https://github.com/scriptingxss/IoTGoat) ⭐ 183 | 🐛 1 | 🌐 C | 📅 2020-03-29 - IoTGoat is a deliberately insecure firmware based on OpenWrt.
* [Hardware Hacking 101](https://github.com/rdomanski/hardware_hacking/tree/master/my_talks/Hardware_Hacking_101) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2019-03-28 - Workshop @ BSides Munich 2019.
* [CSAW Embedded Security Challenge 2019](https://github.com/TrustworthyComputing/csaw_esc_2019) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2019-11-24 - CSAW 2019 Embedded Security Challenge (ESC).
* [Rhme-2016](https://github.com/Riscure/Rhme-2016) ⭐ 4 | 🐛 0 | 📅 2024-08-28 - Riscure Hack me 2 is a low level hardware CTF challenge.
* [Rhme-2015](https://github.com/Riscure/RHme-2015) ⭐ 0 | 🐛 0 | 📅 2024-08-25 - First riscure Hack me hardware CTF challenge.
* [Rhme-2017/2018](https://github.com/Riscure/Rhme-2017) ⭐ 0 | 🐛 0 | 📅 2024-08-28 - Riscure Hack Me 3 embedded hardware CTF 2017-2018.
* [Embedded Security CTF](https://microcorruption.com) - Microcorruption: Embedded Security CTF.

## Websites

* [Hacking Printers Wiki](http://hacking-printers.net/wiki/index.php/Main_Page) - All things printer.
* [OWASP Embedded Application Security Project](https://owasp.org/www-project-embedded-application-security/) - Development best practices and list of hardware and software tools.
* [OWASP Internet of Things Project](https://owasp.org/www-project-internet-of-things/) - IoT common vulnerabilities and attack surfaces.
* [Router Passwords](https://192-168-1-1ip.mobi/default-router-passwords-list/) - Default login credential database sorted by manufacturer.
* [Siliconpr0n](https://siliconpr0n.org/) - A Wiki/Archive of all things IC reversing.

### Blogs

<!--lint ignore no-repeat-punctuation-->

* [RTL-SDR](https://www.rtl-sdr.com/)
* [/dev/ttyS0's Embedded Device Hacking](http://www.devttys0.com/blog/)
* [Exploiteers](https://www.exploitee.rs/)
* [Hackaday](https://hackaday.com)
* [jcjc's Hack The World](https://jcjc-dev.com/)
* [Quarkslab](https://blog.quarkslab.com/)
* [wrong baud](https://wrongbaud.github.io/)
* [Firmware Security](https://firmwaresecurity.com/)
* [PenTestPartners](https://www.pentestpartners.com/internet-of-things/)
* [Attify](https://blog.attify.com/)
* [Patayu](https://payatu.com/blog)
* [GracefulSecurity - Hardware tag](https://gracefulsecurity.com/category/hardware/)
* [Black Hills - Hardware Hacking tag](https://www.blackhillsinfosec.com/tag/hardware-hacking/)

### Tutorials and Technical Background

* [Azeria Lab](https://azeria-labs.com/) - Miscellaneous ARM related Tutorials.
* [JTAG Explained](https://blog.senr.io/blog/jtag-explained#) - A walkthrough covering UART and JTAG bypassing a protected login shell.
* [Reverse Engineering Serial Ports](http://www.devttys0.com/2012/11/reverse-engineering-serial-ports/) - Detailed tutorial about how to spot debug pads on a PCB.
* [UART explained](https://www.mikroe.com/blog/uart-serial-communication) - An in depth explanation of the UART protocol.

### YouTube Channels

* [Flashback Team](https://www.youtube.com/c/FlashbackTeam) - A duo of hackers explaining their step by step approach to finding and exploiting vulnerabilities in embedded devices.
* [StackSmashing](https://www.youtube.com/c/stacksmashing) - Reverse engineering and hardware hacking of embedded devices.

## Conferences

Conferences focused on embedded and/or IoT security.

* [Hardwear.io](https://hardwear.io/)
  * EU, The Hague, September.
  * USA, Santa Clara, June.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Fraunhofer FKIE has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._
