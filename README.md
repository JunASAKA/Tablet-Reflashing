## 处于非正常状态的Lenovo Tab 4 8 REL（具体型号为TB-8X04F）的平板电脑安装并运行原厂安卓（Android Nougat）操作系统所需文件和方法与步骤记录。  
  
　　**本人坚决贯彻GNU自由软件运动精神，本人的目标同[GNU](https://www.gnu.org/)及[FSF](https://www.fsf.org/)一样，“我们的目标是创建一个用户能在任何计算机上使用自由软件完成一切的世界，一个绝无第二人而是用户自己完全掌控其个人电脑的世界。”  
　　鉴于此，本人认为，在用户拥有计算机物权的前提下，在不侵犯他人权益的前提下，用户应能够自由、自主地使用、管理、支配计算机的任何部分；能够自由、自主地定制、二次开发自己的设备，而不应受到限制。既如此，一定的对设备在非正常状态下的修复能力与紧急处理能力是必要的。但现阶段由于各对市场占有、利润盈收、知识产权等保护的要求，以致设备自身封闭、技术资料少之又少，实是与广大研究者、劳动者之意志相悖。故对本课题进行研究，并完全开放研究成果，以便于诸位对计算机的研究与在操作失误紧急状况下进行的修复与纠正；为自由软件运动尽一份力，为计算机界的发展进步尽一份力。  
　　但注意，在诸位实践此项目时，须保证您拥有设备的物权，或得到物权所有者的许可，且不可以此损害他人权益，否则造成的任何损失与影响本人概不负责。且您对此项目的实践与否本人概不干涉，完全由您自己决定，与本人无关。**  
  　　
   本项目所述方法仅适用于Windows x86、Windows x64平台；经试验对于Linux平台，有更灵活的解决方案。详情请看[Android-OperSys-Kits仓库](https://github.com/JunASAKA/Android-OperSys-Kits/)。  
  

文件列表
* （folder）固件：固件文件，全部下载后置诸同一目录下，解压缩其中后缀为zip者。
* LICENSE：开源许可：GNU GPL v3
* README.md：本说明文件
* QPST_2.7.496.zip：适用于高通骁龙处理器的固件烧录程式
* 高通芯片手机通用手机驱动 V1.0.79.zip：如其名，驱动程式
* 方法步骤.mp4：安装方法步骤说明视频  
  

***WARNING***  
　　本视频及文章仅以研究性学习记录为性质，以开拓思路与研究计算机原理为目的；如任何人因模仿、学习、实践此视频或文章内容造成的损失，后果自行承担。  

　　另，本视频及文章所用到的软件、操作系统、应用程式等的知识产权归属其来源人或公司（高通无线通信技术有限公司、联想集团、Google Inc.、Android Open Source Project）。  

　　另，本视频及文章所涉及的操作方法与步骤完全由个人研究所得，此方法步骤完全开源（与公有），任何人（通过本视频或文章习得此方法者）均不可将其用于商业用途；否则造成的任何损失由其自行承担。  

注：  
　　由于各计算机的操作系统版本不同、环境不同等原因，原文所述安装驱动程式的方式可能不适用于所有计算机。比如出现“安全策略不允许”、烧录时卡在一开始等情况，这些问题有一个通用的解决方案，即卸载已安装的出现问题的Qualcomm QDLoader 9008驱动程式（如果先前安装过而不好用），使用Windows系统的“禁用驱动程式签名强制”模式再次安装，不出意外，这样就能够正常运作。


**@浅香ジュン 中国标准时间2020年08月19日**
