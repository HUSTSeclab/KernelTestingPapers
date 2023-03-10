# Papers about Kernel Security Testing

## Kernel Static Testing

### Latest Static Testing Technique

* 2001-OSR: [Bugs as Deviant Behavior: A General Approach to Inferring Errors in Systems Code](https://apps.dtic.mil/sti/pdfs/ADA419584.pdf)
* 2019-FSE：[Detecting Concurrency Memory Corruption Vulnerabilities](https://dl.acm.org/doi/10.1145/3338906.3338927) — 【[tool-CONVUL](https://github.com/mryancai/ConVul)】

### Detecting UB Bugs in Kernel

* 2021-NDSS: [KUBO: Precise and Scalable Detection of User-triggerable Undefined Behavior Bugs in OS Kernel](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1B-5_24461_paper.pdf)
* 2019-USENIX-ATC：[Effective Static Analysis of Concurrency Use-After-Free Bugs in Linux Device Drivers](https://www.usenix.org/conference/atc19/presentation/bai) — 【[note](https://securitygossip.com/blog/2019/11/22/effective-static-analysis-of-concurrency-use-after-free-bugs-in-linux-device-drivers/)】

### Detecting Logical Bugs in Kernel

* 2020-CCS: [Exaggerated Error Handling Hurts! An In-Depth Study and Context-Aware Detection](https://www-users.cs.umn.edu/~kjlu/papers/eecatch.pdf)
* 2019-USENIX：[PeX: A Permission Check Analysis Framework for Linux Kernel](https://www.usenix.org/conference/usenixsecurity19/presentation/zhang-tong)
* 2018-S&P：[DEADLINE-Precise and Scalable Detection of Double-Fetch Bugs in OS Kernels](http://www-users.cs.umn.edu/~kjlu/papers/deadline.pdf) — 【[note](https://www.jianshu.com/p/e4084b2c7c16)】【[note2](https://www.jianshu.com/p/7e2f15547f1e)】【[note3](https://www.inforsec.org/wp/?p=2550)】【[tool-DEADLINE](https://github.com/sslab-gatech/deadline)】

### Research Trends of Kernel Static Testing

* 2020-TOCS：[Effective Detection of Sleep-in-atomic-context Bugs in the Linux Kernel](https://dl.acm.org/doi/pdf/10.1145/3381990)
* 2019-ASPLOS: [DCNS: Automated Detection Of Conservative Non-Sleep Defects in the Linux Kernel](https://hal.inria.fr/hal-02389543/document)

* 2019-USENIX：[Detecting Missing-Check Bugs via Semantic- and Context-Aware Criticalness and Constraints Inferences](https://www.usenix.org/conference/usenixsecurity19/presentation/lu) — 【[tool-CRIX](https://github.com/umnsec/crix)】


* 2018-USENIX-ATC：[DSAC: Effective Static Analysis of Sleep-in-Atomic-Context Bugs in Kernel Modules](https://www.usenix.org/system/files/conference/atc18/atc18-bai.pdf)
* 2018-NDSS：[K-Miner: Uncovering Memory Corruption in Linux](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_05A-1_Gens_paper.pdf) — 【[note](https://mp.weixin.qq.com/s/3N3rmAyZEbZpiBvxnjWVvA)】【[note2](https://blog.csdn.net/u012332816/article/details/79795643)】【[tool-K-Miner](https://github.com/ssl-tud/k-miner)】

* 2018-CCS：[Check It Again- Detecting Lacking-Recheck Bugs in OS Kernels ](https://www-users.cs.umn.edu/~kjlu/papers/lrsan.pdf)— 【[note](https://www.jianshu.com/p/2f8df6082b1d)】【[note2](https://securitygossip.com/blog/2018/11/27/check-it-again-detecting-lacking-recheck-bugs-in-os-kernels/)】【[tool-LRSan](https://github.com/kengiter/lrsan)】
* 2017-USENIX：[How Double-Fetch Situations turn into DoubleFetch](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang.pdf) — 【[note](http://www.inforsec.org/wp/?p=2049)】【[tool](https://github.com/wpengfei/double_fetch_cocci)】
* 2017-USENIX：[DR. CHECKER- A Soundy Analysis for Linux Kernel Drivers](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-machiry.pdf) — 【[tool-dr_checker](https://github.com/ucsb-seclab/dr_checker)】
* 2017-USENIX：[Digtool- A Virtualization-Based Framework for Detecting Kernel Vulnerabilities-usenix](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-pan.pdf) — 【[note](https://www.jianshu.com/p/3cc85231657d)】【[note2](https://mp.weixin.qq.com/s/RFWqx0LXWuHcJNbb8lrjFA)】【[note3](http://yama0xff.com/2019/02/15/Digtool-A-Virtualization-Based-Framework-for-Detecting-Kernel-Vulnerabilities/)】【[note4](https://securitygossip.com/blog/2018/10/09/digtool-a-virtualization-based-framework-for-detecting-kernel-vulnerabilities/)】
* 2017-EUROSYS：[DangSan - Scalable Use-after-free Detection](https://doi.org/10.1145/3064176.3064211) — 【[tool-dangsan](https://github.com/vusec/dangsan)】
* 2016-USENIX：[APISan: Sanitizing API Usages through Semantic Cross-Checking](https://pdfs.semanticscholar.org/29c2/42b2b73c376a61344877d5488f33e066ecc8.pdf?_ga=2.254762891.2010008061.1593351615-150437918.1586869794) — 【[tool-apisan](https://github.com/sslab-gatech/apisan)】
* 2016-USENIX：[UniSan-Proactive Kernel Memory Initialization to Eliminate Data Leakages](https://dl.acm.org/doi/pdf/10.1145/2976749.2978366) — 【[note](http://www.inforsec.org/wp/?p=1416)】【[tool-unisan](https://github.com/sslab-gatech/unisan)】
* 2015-SOSP：[Cross-checking semantic correctness: The case of finding file system bugs](https://lifeasageek.github.io/papers/min-juxta.pdf) — 【[tool-JUXTA](https://github.com/sslab-gatech/juxta)】
* 2014-USENIX：[Static Analysis of Variability in System Software - The 90, 000 #ifdefs Issue](https://www.usenix.org/conference/atc14/technical-sessions/presentation/tartler)
* 2013-DSN: [Hector: Detecting resource-release omission faults in error-handling code for systems software](https://hal.inria.fr/hal-00918079/document)
* 2013-WCRE: [Who Allocated My Memory? Detecting Custom Memory Allocators in C Binaries](https://www.cs.vu.nl/~herbertb/papers/membrush_wcre13.pdf)
* 2012-OSDI：[Improving integer security for systems with KINT](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/wang)
* 2008-EUROSYS: [Documenting and automating collateral evolutions in linux device drivers](https://www.researchgate.net/profile/Yoann_Padioleau/publication/221351679_Towards_Documenting_and_Automating_Collateral_Evolutions_in_Linux_Device_Drivers/links/00b7d5255a2ef57876000000/Towards-Documenting-and-Automating-Collateral-Evolutions-in-Linux-Device-Drivers.pdf)
* 2007-ICSE: [Pathsensitive inference of function precedence protocols](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=2660&context=cstech)
* 2005-ESEC/FSE: [Context- and Path-sensitive Memory Leak Detection](http://groups.csail.mit.edu/pag/OLD/parg/xie05leak.pdf)

#### Kernel Fuzzing
|Type|Date|Paper|
|------|------|------|
|SYSCALL|||
||SOSP 2021|HEALER: Relation Learning Guided Kernel Fuzzing|
||CCS 2021|SyzGen: Automated Generation of Syscall Specification of Closed-Source macOS Drivers|
||NDSS 2020|HFL: Hybrid Fuzzing on the Linux Kernel|
||EuroSec 2020|X-AFL: A Kernel fuzzer combining passive and active fuzzing|
||USENIX 2018|MoonShine: Optimizing OS fuzzer seed selection with trace distillation|
|INPUT|||
||NDSS 2022|EMS : History-Driven Mutation for Coverage-based Fuzzing|
||USENIX 2021|SYZVEGAS : Beating Kernel Fuzzing Odds with Reinforcement Learning|
|DRIVER & FILESYSTEM|||
||NDSS 2022|Semantic-Informed Driver Fuzzing Without Both the Hardware Devices and the Emulators|
||USENIX 2020|USBFuzz: A framework for fuzzing USB drivers by device emulation|
||SP 2020|Ex-vivo dynamic analysis framework for android device drivers|
||ACM Transactions on Storage 2020|Finding Bugs in File Systems with an Extensible Fuzzing Framework|
||SP 2020|KRACE : Data Race Fuzzing for Kernel File Systems|
||SP 2019|Fuzzing File Systems via Two-Dimensional Input Space Exploration|
||SOSP 2019|Finding semantic bugs in file systems with an extensible fuzzing framework|
||CCS 17|Difuze: Interface aware fuzzing for kernel drivers|
|PERFORMANCE|||
||CCS 2021|Hardware Support to Improve Fuzzing Performance and Precision|
||USENIX 2021|Undo Workarounds for Kernel Bugs|
||USENIX 2020|Agamotto : Accelerating Kernel Driver Fuzzing with Lightweight Virtual Machine Checkpoints|
||USENIX 2017|KAFL: Hardware-assisted feedback fuzzing for OS kernels|
|STATE|||
||CCS 2021|HyperFuzzer: An Efficient Hybrid Fuzzer for Virtual CPUs|
||SP 2019|Razzer: Finding kernel race bugs through fuzzing|
||WOOT 2019|Unicorefuzz: On the viability of emulation for kernelspace fuzzing|
|OTHER|||
||USENIX 2022|SyzScope: Revealing High-Risk Security Impacts of Fuzzer-Exposed Bugs in Linux kernel|

## References

[1] https://github.com/ZJU-SEC/Readings/blob/main/README.md
