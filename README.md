
# awesome-vm-escape [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Sharing some useful archives about vm and qemu escape exploit.

I want to collect what I can find. Also be welcome to provide me with issues.

In [computer security](https://en.wikipedia.org/wiki/Computer_security), **virtual machine escape** is the process of breaking out of a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine) and interacting with the host [operating system](https://en.wikipedia.org/wiki/Operating_system).

## VMware && Esxi && Funsion

### Writeup and Exploit

* [VMware Escape Exploit - CVE-2017-4901](https://github.com/unamer/vmware_escape)
* [利用一个堆溢出漏洞实现VMware逃逸-CVE-2017-4901](https://zhuanlan.zhihu.com/p/27733895?utm_medium=social&utm_source=wechat_timeline&from=timeline&isappinstalled=1)
* [A-bunch-of-Red-Pills-VMware-Escapes](https://keenlab.tencent.com/en/2018/04/23/A-bunch-of-Red-Pills-VMware-Escapes/)
* [eu-17-Mandal-The-Great-Escapes-Of-Vmware-A-Retrospective-Case-Study-Of-Vmware-G2H-Escape-Vulnerabilities](https://www.blackhat.com/docs/eu-17/materials/eu-17-Mandal-The-Great-Escapes-Of-Vmware-A-Retrospective-Case-Study-Of-Vmware-G2H-Escape-Vulnerabilities.pdf)
* [Vmware-exploit GitHub repositor](https://github.com/xairy/vmware-exploitation)
* [qemu-kvm和ESXi虚拟机逃逸实例分享](https://s0.ssl.qhres.com/static/afe66384eb42feff.pdf)
* [CVE-2022-31705 Geekpwn 2022 Vmware EHCI OOB](https://github.com/s0duku/cve-2022-31705)
* [On the clock: Escaping VMware Workstation at Pwn2Own Berlin 2025 - PVSCSI Heap Overflow](https://www.synacktiv.com/en/publications/on-the-clock-escaping-vmware-workstation-at-pwn2own-berlin-2025)
* [The Great VM Escape - ESXicape: CVE-2025-22224/22225/22226 Exploit Chain](https://www.huntress.com/blog/esxi-vm-escape-exploit)

## Virtualbox

### Basic

* [virtualbox technical background](https://www.virtualbox.org/manual/ch10.html)

### Writeup and Exploit

* [VirtualBox E1000 Guest-to-Host Escape](https://github.com/MorteNoir1/virtualbox_e1000_0day)
* [Oracle VirtualBox < 5.1.30 / < 5.2-rc1 - GUest to Host Escape](https://www.exploit-db.com/exploits/43878/)
* [VirtualBox 5.2.6.r120293 -VM Escape](https://www.exploit-db.com/exploits/45372/)
* [Pwn2Own 2018 Virtualbox 的漏洞分析及利用介绍：thinking_outside_the_virtualbox](https://github.com/phoenhex/files/blob/master/slides/thinking_outside_the_virtualbox.pdf)
* [Escaping VirtualBox 6.1](https://secret.club/2021/01/14/vbox-escape.html)

##  Qemu

### Writeup and Exploit

* [VM escape - QEMU Case Study](http://www.phrack.org/papers/vm-escape-qemu-case-study.html)
* [Qemu - Escape - analysis - CVE-2015-7504 and CVE-2015-7512](https://www.anquanke.com/post/id/83015)
* [Some Qemu escape exploit](https://github.com/dangokyo/QEMU_ESCAPE)
* [CVE-2020-14364 QEMU逃逸 漏洞分析 ](https://mp.weixin.qq.com/s/MQyczZXRfOsIQewNf7cfXw)
* [qemu-kvm和ESXi虚拟机逃逸实例分享](https://s0.ssl.qhres.com/static/afe66384eb42feff.pdf)
* [From virtio-snd 0-Day to Hypervisor Escape: Exploiting QEMU with an Uncontrolled Heap Overflow](https://osec.io/blog/2026-03-17-virtio-snd-qemu-hypervisor-escape/) | [Exploit](https://github.com/otter-sec/qemu-escape)
* [Resurrecting Zombies: DMA Reentrancy in QEMU (HITB 2023)](https://conference.hitb.org/hitbsecconf2023ams/session/resurrecting-zombies-leveraging-advanced-techniques-of-dma-reentrancy-to-escape-qemu/)

## Parallels Desktop

* [Advanced Exploitation ofSimple Bugs---A Parallels Desktop Case Study (Pwn2Own2021)](https://zerodayengineering.com/projects/slides/ZDE2021_AdvancedSimplePwn2Own2021.pdf)

* [CVE-2023-27326 Parallels Desktop Toolgate Vulnerability](https://github.com/Impalabs/CVE-2023-27326)

##  Hyper-V

* [awesome-hyper-v-exploitation](https://github.com/shogunlab/awesome-hyper-v-exploitation)
* [CVE-2023-36427 Windows Hyper-V Elevation of Privilege Vulnerability](https://github.com/tandasat/CVE-2023-36427)

## Docker

### Basic

* [eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments.pdf)
* [CSW2016-Docker-Escape-Techonology](https://cansecwest.com/slides/2016/CSW2016_Wang_DockerEscapeTechnology.pdf)


### Writeup and Exploit

* [Docker 容器逃逸案例分析](https://yq.aliyun.com/articles/57803?utm_source=qq)
* [escaping-docker-container-using-waitid-cve-2017-5123](https://www.twistlock.com/labs-blog/escaping-docker-container-using-waitid-cve-2017-5123/)

### Tools

[CDK - Zero Dependency Container Penetration Toolkit](https://github.com/cdk-team/CDK)

## Misc

* [google group vmkernelnewbies(has some good basic intro)](https://groups.google.com/forum/#!forum/vmkernelnewbies)
* [XEN D2T2-Shangcong-Luan-Xen-Hypervisor-VM-Escape](http://conference.hitb.org/hitbsecconf2016ams/wp-content/uploads/2015/11/D2T2-Shangcong-Luan-Xen-Hypervisor-VM-Escape.pdf)
* [vmware exploitation(list)](https://github.com/xairy/vmware-exploitation)

## CTFs

### Writeup and Exploit

* [realword ctf - state-of-the-art_vm](https://xz.aliyun.com/t/2513)
* [HITB 2017 - babyqemu](https://kitctf.de/writeups/hitb2017/babyqemu)
* [0CTF 2017 - QEMU EScape](https://blog.eadom.net/writeups/qemu-escape-vm-escape-from-0ctf-2017-finals-writeup/)
* [48小时逃逸Virtualbox虚拟机——记一次CTF中的0day之旅](https://zhuanlan.zhihu.com/p/58910752)
* [rwctf-3rd-BoxEscape](https://github.com/Sauercloud/RWCTF21-VirtualBox-61-escape)
