# Smartguard

##Introduction
This is a apk file for our TMC 2020 paper "A Framework for Personalized Location Privacy". In this work, we propose a general framework, termed SmartGuard, which comprehensively models the relationships between the current status of user's device, different privacy preserving mechanisms, relative parameters and the resource consumptions, and recommends personalized privacy preserving strategy for mobile users in LBSs.

##Implementation Details
In our implementation, we focusing on the tradeoffs between battery consumption, bandwidth consumption and privacy degree. We provide two PPMs(Privacy Preserving Mechanisms) for privacy preservation, Paillier-based and k-anonymity-based approaches, each of them has two parameters. We denote Paillier with 512 bits and 2048 bits key length, k-anonymity with k = 10, 30. 

As a result, based on the current state of the device and the privacy requirement, the apk give a reasonable PPM and parameter.

##Target platforms
* API level 16 or later

##ScreenShots
![Main Window](https://github.com/whyxxj/Smartguard/blob/master/Screenshots/mainlayout.png)
![Get recommendation](https://github.com/whyxxj/Smartguard/blob/master/Screenshots/recommendation.png)
