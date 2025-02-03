# DI_7001_MINI_5G RCE
## Overview
Manufacturer's website:[网址](http://www.dlink.com.cn)
Firmware download website:[ ](https://www.dlink.com.cn/techsupport/ProductInfo.aspx?m=DI-7001MINI-5G)
## Affected version
19.10.31A1
## Vulnerability details
 **The analysis of the main program uncovered a code execution vulnerability in the `flag` parameter of `msp_info`, which can be exploited to run arbitrary commands.**  
 ![](vx_images/295267129177969.png)

![](vx_images/295266248842880.png)
**A command injection attack was carried out, exploiting the vulnerability to run unauthorized commands.**
![Snipaste_2025-02-02_00-50-05](vx_images/496586200665991.png)