# DI_7001_MINI_8G_A1 RCE
## Overview
Manufacturer's website:[http://www.dlink.com.cn](http://www.dlink.com.cn)
Firmware download website:[https://www.dlink.com.cn/techsupport/ProductInfo.aspx?m=DI-7001MINI-8G](https://www.dlink.com.cn/techsupport/ProductInfo.aspx?m=DI-7001MINI-8G)
## Affected version
A1-19.09.19A1
## Vulnerability details 
An investigation of the main program revealed that the `flag` parameter in `msp_info` is vulnerable, allowing arbitrary code execution.
![Snipaste_2025-02-02_23-26-41](vx_images/377335883510827.png)
**Attempting command injection resulted in a successful attack leveraging the vulnerability.**
![](vx_images/247747641261233.png)
