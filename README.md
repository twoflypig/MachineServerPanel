# MachineServerPanel
This repository is about the control panel for multiple servers for deep learning experiments
Nowadays, experiments about deep learning often needs to be runned on multiple servers and multiply GPUs, for example, hyper parameter searching.  It's a more common method to sovle it by using bash manually. However it have several drawbacks:

- lack of one control panel, sometimes it's confused to run multiple bashs
- lack of managing the results of every experiments
- lack of visualizing the metrics together and managing them 

As far as I know, there exits some tools like visdom(facebook) and jupyter. So can we build a client to server system, which is user friendly, and easy to manage experiments ?
An idea is stated as above, any ideas and suggestions are weclomed!

I will first look into these tools to check if it can meet the requirements. (visdom, jupyer)

After having a glance at jupyter notebook, I find it will be much eaiser to write an extension for jupyter notebook to meet my requirements. My reasons are as follows:
- Jupyter can connect to remote kernel via ssh, which can naturally construct a client and server system, what we need to do is to write code for storing models and code, doing visualization.
- Jupyter can also run on local mode, which means you can manage your projects via jupyter.
- We can save a lot of work start from jupyter.

# My working plan
- Write a extension for Jupyter, to make it worked on local mode. I think this still need a long time. I will do a demo as quick as possible
- Extend local mode to remote mode, making it work for client-server system.


# Related Projects
[omniboard](https://github.com/vivekratnavel/omniboard)
