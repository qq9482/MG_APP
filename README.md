
#	MG-APP (Multi-GNSS-Automatic Precise Positioning software)

 Author:  **Gongwei Xiao**  

- QQ Group: **258113285**  
- E-mail: xiaogongwei10@163.com
- My Github: [https://github.com/xiaogongwei](https://github.com/xiaogongwei)  
- My Blog: [xiaogongwei10.blog.csdn.net](https://xiaogongwei10.blog.csdn.net/)   

 Version : 1.0  
 Date    : 26 Apr 2019  
 Download link (The GPS Toolbox): https://www.ngs.noaa.gov/gps-toolbox/    
 Old version (contains resources you may need): [https://github.com/XiaoGongWei/PPP](https://github.com/XiaoGongWei/PPP)   
 Qt online installers: [http://download.qt.io/archive/online_installers/](http://download.qt.io/archive/online_installers/ )   
 Qt install executable (in china): [http://mirrors.ustc.edu.cn/qtproject/official_releases/qt/](http://mirrors.ustc.edu.cn/qtproject/official_releases/qt/)   
Temporary link to Online MG-APP: https://13018096950.hskyun.com   

 **If you would like to join this repository, please contact us after registering with Github.**   
 **Please use `git clone` or `git pull` to keep MG-APP up to date.** 


![Main Window](https://github.com/XiaoGongWei/MG_APPS/blob/master/resources/OtherFiles/fig2.png)  

## English:

Aiming at the current multi-system combined multi-frequency observation data,  
the MG-APPS precise single-point positioning software is developed.  
Using C++ language based on cross-platform Qt framework, it has high cohesion  
 and low coupling characteristics. It provides a rich and friendly function   
library which is easy to transplant for secondary development. It can run in   
UNIX/Linux, Windows and other operating systems. MG-APPS can process GPS,   
GLONASS, BDS and Galileo system data by using the combination of deionospheric  
 PPP mode. MG-APPS can deal with static data and real dynamic observation data.   
A variety of commonly used tropospheric estimation models can be selected:   
UNB3m, Saastamoinen (GPT2), Hopfield (GPT2), to study the effects of different   
tropospheric models on PPP location (Hopfield 1971; Saastamoinen 1972; Leandro   
et al. 2007; Lagler et al. 2013). Various filtering methods can be selected to   
process data: Kalman filtering, Square Root Information Filter (SRIF), and the   
effect of different filtering methods is studied. It can be used to fuse   
multi-system data to study the precision effect of multi-system combination and  
 single-system model. Phase smoothing pseudorange is used in MG-APPS software,  
 which can improve the accuracy of pseudorange positioning. PPP mode based on   
precision products can be selected, and single Point Positioning (SPP) mode of   
broadcast ephemeris can also be selected. Automatic discrimination of   
observation data (Rinex 3.x and Rinex 2.x) and navigation ephemeris type (N file,  
 P file). Users do not need to care about the underlying data format. If the   
observation data lacks the necessary products for positioning, the software can   
automatically download the products for solution and also automatically batch   
processing observation data. In data processing, only the observation information  
 of two adjacent epochs is needed. According to the filtering algorithm, real-time   
data processing mode is adopted. Forward filtering can be used to study the   
convergence process of PPP, and reverse filtering can be used to provide precise   
coordinates and high resolution tropospheric products.  

 Have fun,  

  Xiaogongwei  


## RTPPP:  
We also developed RTMG-PPP based on MG-APP. Below is the main window and the result of processing 10 hours of GNSS observations.  

![Main Window RTPPP](https://github.com/XiaoGongWei/MG_APPS/blob/master/resources/OtherFiles/RTPPPmain.png)  
![Main Window Results](https://github.com/XiaoGongWei/MG_APPS/blob/master/resources/OtherFiles/ContrastRTPPP.png)  



 Appendix A:   

 MG-APP are distributed under the terms of the version 3 of the GNU General  
 Public License (GPLv3).  See the file COPYING.  
 Copyright (C) 2016-2020 XiaoGongWei   
 Special licenses for commercial and other applications which  
 are not willing to accept the GNU General Public License  
 are available by contacting the author.  

 


