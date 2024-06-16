---

title: "LoopBreaker: Disabling Interconnects to Mitigate Voltage-Based Attacks in Multi-Tenant FPGAs"

authors: "Hassan Nassar, Hanna AlZughbi, Dennis R. E. Gnad, Lars Bauer, Mehdi B. Tahoori, Jörg Henkel"

booktitle: "2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD)"

year: 2021

pages: "1-9"

keywords: "Cloud computing; Runtime; Voltage fluctuations; Fluctuations; Design automation; Force; Computer crashes"

doi: "10.1109/ICCAD51958.2021.9643485"

url: "https://doi.org/10.1109/ICCAD51958.2021.9643485"

---



## Abstract

<p style="text-align: justify;">

FPGAs are being offered in the cloud as accelerator resources that can be shared among multiple users (i.e. tenants). Recently, various approaches have shown that fault attacks launched from one tenant region to another are possible, leading to timing faults or crashes of the FPGA. It is, therefore, important that malicious tenants are limited in their ability to cause such security problems. So far, the existing countermeasures against such attacks check the configuration bitstreams before they are reconfigured. Such offline approaches have various practical limitations, e.g. they may force the tenants to unveil their design secrets. In this paper, we present LoopBreaker, a novel runtime solution that can disable the entire activity of a malicious tenant region, in order to rapidly stop a potential attack before it results in a crash (i.e. Denial-of-Service). We implemented and tested multiple attack types and found that realistic attacks demand at least 12–26 µs to be successful. A partial reconfiguration to overwrite the malicious tenant region demands 200 µs in our realworld implementation, which is too slow to prevent the attack from leading to a crash. Instead, our proposed LoopBreaker method only needs 1.5 µs to stop a malicious tenant, which makes it the first online approach that can successfully stop challenging voltage drop-based attacks from causing a crash.

</p>



## Citation



Hassan Nassar, Hanna AlZughbi, Dennis R. E. Gnad, Lars Bauer, Mehdi B. Tahoori, Jörg Henkel. **"LoopBreaker: Disabling Interconnects to Mitigate Voltage-Based Attacks in Multi-Tenant FPGAs."** In *2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD)*, 2021, pp. 1-9. DOI: [10.1109/ICCAD51958.2021.9643485](https://doi.org/10.1109/ICCAD51958.2021.9643485).