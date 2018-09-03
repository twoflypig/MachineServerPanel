# MachineServerPanel
This repository is about the control panel for multiply servers for deep learning experiments
Nowadays, experiments about deep learning often needs to be runned on multiply servers and multiply GPUs, for example, hyper parameter searching.  It's a more common method to sovle it by using bash manually. However it have several drawbacks:

- lack of one control panel, sometimes it's confused to run multiply bashs
- lack of managing the results of every experiments
- lack of Visualizing the metrics together and managing them 

As far as I know, there exits some tools like visdom(facebook) and jupyter. So can we build a client to server system, which is user friendly, and easy to manage experiments ?
An idea is stated as above, any ideas and suggestions are weclomed!

I will first look into these tools to check if it can meet the requirements. (visdom, jupyer)




# Chinese Version
在深度学习跑实验的时候,通常使用多个服务器同时跑多个卡,比较粗暴的做法是人工在不同的bash下运行不同参数的实验。但是其缺点是:
- 缺乏一个统一控制界面,多bash比较耗费精力
- 每个模型的保存缺乏统一的管理
- 需要可视化各种参数以及配置,增加日志功能等等

所以我的想法是,能不能建立一个多client到server的控制体系,在server中发布任务(或者也是手动执行bash那样),有一个友好的界面,举例如visdom,jupyter。


能否基于上面两个做一个验证呢？
现在只是一个想法,如果大家见到类似的工具或者好的替代方法,也可以交流下,谢谢~
