<a name="readme-top"></a>

<!-- PROJECT DETAILS -->
<div align="center">

  <h1 align="center">Battery Depletion Attack Through Packet Injection on IoT Thread Mesh Network</h1>

  <p align="center">
    A research demo by <strong>Poonam Yadav</strong>, <strong>Nirdesh Sagathia</strong> and <strong>Dan Wade</strong><br>
    performed in the <a href="https://systronlab.github.io"><strong>SYSTRON Lab</strong></a><br>
    based in the <a href="https://www.cs.york.ac.uk/"><strong>Department of Computer Science</strong></a> at the University of York
  </p>
  <p align="center">
    An overview of this work is also <a href="https://systronlab.github.io/publications/2024-battery-depletion-attack-through-packet-injection">published on the SYSTRON Lab website</a>. It was demonstrated at the <a href="https://www.comsnets.org/">2024 16th International Conference on COMmunication Systems & NETworkS (COMSNETS)</a>.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#abstract">Abstract</a>
    </li>
    <li>
      <a href="#poster">Poster</a>
    </li>
    <li>
      <a href="#paper">Paper</a>
    </li>
    <li>
      <a href="#demonstrations">Demonstrations</a>
    </li>
  </ol>
</details>



<!-- ABSTRACT -->
## Abstract

In the rapidly expanding landscape of Internet of Things (IoT) device manufacturing and deployment, concerns about security have become prominent. This demonstration involves practical attacks on a thread-mesh network within a controlled environment, exploiting vulnerabilities in various components of the Thread network stack. Our attack vectors successfully identified nearby Thread networks and devices by gathering 2-byte Personal Area Network ID (PAN ID) and device frequency information, serving as reconnaissance for potential additional attacks. The focus was on investigating susceptibility to replay attacks and packet injection into thread-mesh networks. Although the experiment attempted to capture thread packets to emulate an authorised sender, the cryptographic encryption and sequence numbers employed for integrity checks resulted in packet rejection by the network. Despite this, our successful injection of packets highlights the potential for battery depletion attacks.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- POSTER -->
## Poster

[View Poster](poster.pdf)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- PAPER  -->
## Paper

[View Paper (Published by IEEE)](https://doi.org/10.1109/COMSNETS59351.2024.10426916)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- VIDEO DEMONSTRATIONS -->
## Demonstrations

The following videos show each stage of the attack scenario. [View the full YouTube playlist](https://www.youtube.com/playlist?list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l)

### CMOS battery check

<a href="https://www.youtube.com/watch?v=POEPtGYoKYg&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=1&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/1-cmos-battery-check.png" alt="" width="300px">
<br><strong>View CMOS Battery Check Demo on YouTube</strong>
</a>

### Devices

<a href="https://www.youtube.com/watch?v=Ly6GsPM3DJU&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=2&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/2-devices.png" alt="" width="300px">
<br><strong>View Devices Demo on YouTube</strong>
</a>

### Thread Topology Monitor

<a href="https://www.youtube.com/watch?v=vMQx7olECTo&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=3&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/3-thread-topology-monitor.png" alt="" width="300px">
<br><strong>View Thread Topology Monitor Demo on YouTube</strong>
</a>

### Network Ping

<a href="https://www.youtube.com/watch?v=mhVGHQBENcc&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=5&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/4-network-ping.png" alt="" width="300px">
<br><strong>View Network Ping Demo on YouTube</strong>
</a>

### Network Scanning over 802.15.4

<a href="https://www.youtube.com/watch?v=kCLdcBcuMRw&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=7&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/5-network-scanning-1.png" alt="" width="300px">
<br><strong>View Network Scanning Demo on YouTube</strong>
</a><br><br>

<a href="https://www.youtube.com/watch?v=MWKB4IhKphw&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=6&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/6-network-scanning-2.png" alt="" width="300px">
<br><strong>View Network Scanning Demo (2) on YouTube</strong>
</a>

### Network Sniffer

<a href="https://www.youtube.com/watch?v=pcuHufHOLx4&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=8&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/7-network-sniffer.png" alt="" width="300px">
<br><strong>View Network Sniffer Demo on YouTube</strong>
</a>

### Wireshark Details and MLE

<a href="https://www.youtube.com/watch?v=-Bl25iEtFF8&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=9&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/8-wireshark-details-and-mle.png" alt="" width="300px">
<br><strong>View Wireshark Details and MLE Demo on YouTube</strong>
</a>

### Python Script

<a href="https://www.youtube.com/watch?v=t5fCfg9T1xY&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=10&pp=iAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/9-python-script.png" alt="" width="300px">
<br><strong>View Python Script Demo on YouTube</strong>
</a>

### Attack 1

<a href="https://www.youtube.com/watch?v=kUg6m1a79nY&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=11&pp=gAQBiAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/10-attack-1.png" alt="" width="300px">
<br><strong>View First Attack Demo on YouTube</strong>
</a>

### Attack 2

<a href="https://www.youtube.com/watch?v=uRAoX3eUTGU&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=12&pp=gAQBiAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/11-attack-2.png" alt="" width="300px">
<br><strong>View Second Attack Demo on YouTube</strong>
</a>

### Attack 3

<a href="https://www.youtube.com/watch?v=3JD_UhbPn20&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=13&pp=gAQBiAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/12-attack-3.png" alt="" width="300px">
<br><strong>View Third Attack Demo on YouTube</strong>
</a>

### Attack 4

<a href="https://www.youtube.com/watch?v=5ed5_Oiar2M&list=PLLdryWn5PKavOXsef-qLGpMRhmR3wfp8l&index=14&pp=gAQBiAQB">
<img src="https://systronlab.github.io/img/2024-threadbatteryattack/13-attack-4.png" alt="" width="300px">
<br><strong>View Fourth Attack Demo on YouTube</strong>
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>