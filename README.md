# awesome-vm-escape [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of writeups, exploits, and resources related to virtual machine escape and container breakout.

Contributions are welcome — feel free to open an issue or pull request.

In [computer security](https://en.wikipedia.org/wiki/Computer_security), **virtual machine escape** is the process of breaking out of a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine) and interacting with the host [operating system](https://en.wikipedia.org/wiki/Operating_system).

## Table of Contents

- [VMware / ESXi / Fusion](#vmware--esxi--fusion)
- [VirtualBox](#virtualbox)
- [QEMU](#qemu)
- [Parallels Desktop](#parallels-desktop)
- [Hyper-V](#hyper-v)
- [Docker / Container](#docker--container)
- [Xen](#xen)
- [CTFs](#ctfs)
- [Misc](#misc)

---

## VMware / ESXi / Fusion

* [VMware Escape Exploit - CVE-2017-4901](https://github.com/unamer/vmware_escape)
* [利用一个堆溢出漏洞实现 VMware 逃逸 - CVE-2017-4901](https://zhuanlan.zhihu.com/p/27733895?utm_medium=social&utm_source=wechat_timeline&from=timeline&isappinstalled=1)
* [A Bunch of Red Pills: VMware Escapes (Keen Lab)](https://keenlab.tencent.com/en/2018/04/23/A-bunch-of-Red-Pills-VMware-Escapes/)
* [The Great Escapes of VMware: A Retrospective Case Study of G2H Escape Vulnerabilities (Black Hat EU 2017)](https://www.blackhat.com/docs/eu-17/materials/eu-17-Mandal-The-Great-Escapes-Of-Vmware-A-Retrospective-Case-Study-Of-Vmware-G2H-Escape-Vulnerabilities.pdf)
* [VMware Exploitation - Resource List](https://github.com/xairy/vmware-exploitation)
* [QEMU-KVM 和 ESXi 虚拟机逃逸实例分享 - 360 Vulcan Team](https://tech.sina.com.cn/roll/2020-08-17/doc-iivhvpwy1449744.shtml)
* [CVE-2022-31705: GeekPwn 2022 VMware EHCI OOB](https://github.com/s0duku/cve-2022-31705)
* [Bugs of Yore: A Bug Hunting Journey on VMware's Hypervisor (Black Hat USA 2024)](https://i.blackhat.com/BH-US-24/Presentations/US24-Sialveras-Bugs-Of-Yore-Wednesday.pdf)
* [On the Clock: Escaping VMware Workstation at Pwn2Own Berlin 2025 - PVSCSI Heap Overflow (Synacktiv)](https://www.synacktiv.com/en/publications/on-the-clock-escaping-vmware-workstation-at-pwn2own-berlin-2025)
* [The Great VM Escape - ESXicape: CVE-2025-22224/22225/22226 Exploit Chain (Huntress)](https://www.huntress.com/blog/esxi-vm-escape-exploit)

## VirtualBox

### Background

* [VirtualBox Technical Background](https://www.virtualbox.org/manual/ch10.html)

### Writeup and Exploit

* [VirtualBox E1000 Guest-to-Host Escape](https://github.com/MorteNoir1/virtualbox_e1000_0day)
* [Oracle VirtualBox < 5.1.30 / < 5.2-rc1 - Guest to Host Escape](https://www.exploit-db.com/exploits/43878/)
* [VirtualBox 5.2.6.r120293 - VM Escape](https://www.exploit-db.com/exploits/45372/)
* [Thinking Outside the VirtualBox - Pwn2Own 2018 漏洞分析](https://github.com/phoenhex/files/blob/master/slides/thinking_outside_the_virtualbox.pdf)
* [Escaping VirtualBox 6.1](https://secret.club/2021/01/14/vbox-escape.html)
* [Analysis of VirtualBox CVE-2023-21987 and CVE-2023-21991 - VGA & TPM OOB (Pwn2Own 2023)](https://qriousec.github.io/post/vbox-pwn2own-2023/)
* [CVE-2024-21115: An Oracle VirtualBox LPE Used to Win Pwn2Own (ZDI)](https://www.thezdi.com/blog/2024/5/9/cve-2024-21115-an-oracle-virtualbox-lpe-used-to-win-pwn2own)

## QEMU

* [VM Escape - QEMU Case Study (Phrack)](http://www.phrack.org/papers/vm-escape-qemu-case-study.html)
* [QEMU Escape Analysis - CVE-2015-7504 and CVE-2015-7512](https://www.anquanke.com/post/id/197638)
* [QEMU Escape Exploits Collection](https://github.com/dangokyo/QEMU_ESCAPE)
* [CVE-2020-14364 QEMU 逃逸漏洞分析](https://mp.weixin.qq.com/s/MQyczZXRfOsIQewNf7cfXw)
* [QEMU-KVM 和 ESXi 虚拟机逃逸实例分享 - 360 Vulcan Team](https://tech.sina.com.cn/roll/2020-08-17/doc-iivhvpwy1449744.shtml)
* [Resurrecting Zombies: DMA Reentrancy in QEMU (HITB 2023)](https://conference.hitb.org/hitbsecconf2023ams/session/resurrecting-zombies-leveraging-advanced-techniques-of-dma-reentrancy-to-escape-qemu/)
* [From virtio-snd 0-Day to Hypervisor Escape: Exploiting QEMU with an Uncontrolled Heap Overflow (OtterSec)](https://osec.io/blog/2026-03-17-virtio-snd-qemu-hypervisor-escape/) | [Exploit](https://github.com/otter-sec/qemu-escape)

## Parallels Desktop

* [Advanced Exploitation of Simple Bugs - A Parallels Desktop Case Study (Pwn2Own 2021)](https://zerodayengineering.com/research/slides/ZDE2021_AdvancedEasyPwn2Own2021.pdf)
* [CVE-2023-27326: Parallels Desktop Toolgate Vulnerability](https://github.com/Impalabs/CVE-2023-27326)

## Hyper-V

* [Awesome Hyper-V Exploitation - Resource List](https://github.com/shogunlab/awesome-hyper-v-exploitation)
* [CVE-2023-36427: Windows Hyper-V Elevation of Privilege Vulnerability](https://github.com/tandasat/CVE-2023-36427)
* [CVE-2025-21333: Hyper-V NT Kernel Integration VSP Heap Overflow - SYSTEM Privilege Escalation](https://technijian.com/cyber-security/vulnerabilities/critical-windows-hyper-v-nt-kernel-vulnerability-allows-system-privilege-escalation-poc-released/)
* [CVE-2025-48822: Hyper-V DDA (Discrete Device Assignment) OOB Read - Local Code Execution](https://zeropath.com/blog/windows-hyperv-dda-cve-2025-48822)

## Docker / Container

### Background

* [Vulnerability Exploitation in Docker Container Environments (Black Hat EU 2015)](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments.pdf)
* [Docker Escape Technology (CanSecWest 2016)](https://www.slideshare.net/slideshow/csw2016-wang-dockerescapetechnology/60387867)

### Writeup and Exploit

* [Docker 容器逃逸案例分析](https://yq.aliyun.com/articles/57803?utm_source=qq)
* [Escaping Docker Container Using waitid - CVE-2017-5123](https://www.twistlock.com/labs-blog/escaping-docker-container-using-waitid-cve-2017-5123/)
* [Leaky Vessels: CVE-2024-21626 runc Container Breakout (Snyk)](https://snyk.io/blog/cve-2024-21626-runc-process-cwd-container-breakout/) | [Wiz Deep Dive](https://www.wiz.io/blog/leaky-vessels-container-escape-vulnerabilities) | [Static Detector](https://github.com/snyk/leaky-vessels-static-detector)
* [runc Container Breakout via Mount Race Conditions - CVE-2025-31133/52565/52881 (CNCF)](https://www.cncf.io/blog/2025/11/28/runc-container-breakout-vulnerabilities-a-technical-overview/) | [Sysdig Analysis](https://www.sysdig.com/blog/runc-container-escape-vulnerabilities) | [runc Advisory](https://github.com/opencontainers/runc/security/advisories/GHSA-9493-h29p-rfm2)
* [NVIDIAScape: CVE-2025-23266 Three-Line Container Escape in NVIDIA Container Toolkit (Wiz)](https://www.wiz.io/blog/nvidia-ai-vulnerability-cve-2025-23266-nvidiascape)
* [NVIDIA Container Toolkit CVE-2024-0132 Container Escape Deep Dive (Wiz)](https://www.wiz.io/blog/nvidia-ai-vulnerability-deep-dive-cve-2024-0132)

### Tools

* [CDK - Zero Dependency Container Penetration Toolkit](https://github.com/cdk-team/CDK)

## Xen

* [Xen Hypervisor VM Escape (HITB 2016)](http://conference.hitb.org/hitbsecconf2016ams/wp-content/uploads/2015/11/D2T2-Shangcong-Luan-Xen-Hypervisor-VM-Escape.pdf)

## CTFs

* [RealWorld CTF - state-of-the-art_vm](https://xz.aliyun.com/t/2513)
* [HITB 2017 - babyqemu](https://kitctf.de/writeups/hitb2017/babyqemu)
* [0CTF 2017 - QEMU Escape](https://blog.eadom.net/writeups/qemu-escape-vm-escape-from-0ctf-2017-finals-writeup/)
* [48 小时逃逸 VirtualBox 虚拟机 - 记一次 CTF 中的 0day 之旅](https://zhuanlan.zhihu.com/p/58910752)
* [RWCTF 3rd - BoxEscape (VirtualBox 6.1)](https://github.com/Sauercloud/RWCTF21-VirtualBox-61-escape)

## Misc

* [Google Group: vmkernelnewbies](https://groups.google.com/forum/#!forum/vmkernelnewbies)
