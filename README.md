# 42 NetPractice
*This project has been created as part of the 42 curriculum by wcapt*

## Overview
### Description

NetPractice is a hands-on networking training tool designed to help learners master fundamental networking concepts through interactive configuration challenges. The project simulates real-world network environments where users configure routers, switches, IP addresses, subnet masks, gateways, and routing rules across multiple levels of increasing complexity.

### Goal

The goal is to reinforce understanding of core networking principles — including TCP/IP addressing, OSI model layers, subnetting, routing, and device configuration — by applying them in practical, scenario-based exercises.

### Installation and Instructions

1. Download the folder on intra42.
```
net_practice.1.9.tgz
```
2. Navigate to the project directory to find a file `.sh`
```
run.sh
```
3. Run it. This launches the interactive environment to start the exercice.
```
Enter your 42_login
```
4. Start !!!
```
Now you can start to complet the 10 levels of the NetPractice project.
```

### How it works ?

There are 10 training levels available. Below is an example of how each level works:

For every level, a non-functional network diagram is displayed.

![preview](imgs/lvl_1.png)
![preview](imgs/lvl_10.png)

At the top of your screen, you’ll see one or more objectives that you must complete by adjusting the available network settings — such as IP addresses, subnet masks, gateways, or routing rules — until the network operates correctly.

![preview](imgs/goals.png)
![preview](imgs/logs.png)

You can use two main buttons during each level:

    [Check again] — to validate whether your current configuration meets the objectives.
    [Get my config] — to download your configuration file at any time. You will need this file for submission.

![preview](imgs/get_config.png)


Once you successfully complete a level, a new button will appear. Click it to advance to the next level.

![preview](imgs/next_lvl.png)

## ⚠️ Important

Before proceeding to the next level, always export your configuration using the [Get my config] button. Save the file and include it in your Git repository — you must submit 10 configuration files, one per level, at the root of your repo.


## References
- [gitbook.io](https://42-cursus.gitbook.io/guide/4-rank-04/netpractice) - A practical guide explaining the NetPractice project and networking concepts for 42 students.
- [medium.com](https://medium.com/@imyzf/netpractice-2d2b39b6cf0a) - A detailed article sharing insights and explanations about solving NetPractice exercises.
- [github.com](https://github.com/tblaase/Net_Practice) - A repository containing solutions and resources related to the Net_Practice project.
- [wikipedia.org](https://fr.wikipedia.org/wiki/Sous-r%C3%A9seau) - An overview explaining what a subnet is and how network segmentation works.
- [wikipedia.org](https://fr.wikipedia.org/wiki/Transmission_Control_Protocol) - A comprehensive explanation of the Transmission Control Protocol and how it ensures reliable communication.
- [netgear.com](https://kb.netgear.com/fr/232/Qu-est-ce-qu-un-switch-Une-introduction) - An introductory article explaining what a network switch is and how it functions.
- [fortinet.com](https://www.fortinet.com/fr/resources/cyberglossary/tcp-ip) - A cybersecurity-focused explanation of the TCP/IP model and its core principles.
- [virginmedia.com](https://www.virginmedia.com/the-edit/comparisons/modem-vs-router) - A comparison article explaining the difference between a modem and a router.
- [ionos.fr](https://www.ionos.fr/digitalguide/serveur/know-how/subnetting-comment-fonctionnent-les-sous-reseaux/) - A technical guide explaining subnetting and how subnetworks operate.
- [calculator.net](https://www.calculator.net/ip-subnet-calculator.html) - An interactive IP subnet calculator for quickly determining subnet ranges and details.
- [euria.infomaniak.com](https://euria.infomaniak.com/) - Infomaniak's AI, used to resolve misunderstandings at the subnet mask and IP range level.
