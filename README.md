# Windows-11-VitrtualBox-Guide
A quick tutorial on how to get a VM for Windows 11 up and running on Oracle's Virtual Box
# Introduction
Hey! Welcome to my first GitHub Project, today I'm going to be showing you how to install and set up a Windows 11 Virtual Machine(VM) with Oracle's VirtualBox

# Requirements before we start
- 4 Cores
- 8 GB Ram
- 80 GB Storage
- Intel VT-x or AMD-V enabled in your system's BIOS settings

# Getting Started
- First and foremost, you'll want to [Install the Window's 11 Disk Image (ISO)](https://www.microsoft.com/en-us/software-download/windows11)
- To do this, click the link attached and scroll down until you see the option to ***Download Windows 11 Disk Image (ISO) for x64 devices.***
- You are then going to want to click on *Select Dowmload* and choose *Download Windows 11 Disk Image (ISO) for x64 devices* from the drop down.
- Next, scroll down and hit *Confirm.* Choose the language you would like Windows to run in (I'm doing English) and press *Confirm.* You're then going to hit the *64-Bit Download* button.
- While that's downloading, go ahead and open up **Oracle's VirtualBox** and get it set up.
<img width="1557" height="941" alt="image" src="https://github.com/user-attachments/assets/5f281cce-ea87-47a5-83b7-08f4ce040dbc" />


# Setting Up VirtualBox
- Press the **New** button on the top left with the blue sun looking shape.
- Go ahead and name the VM whatever you'd like, choose where you'd like the VM's folder to reside, and when the ISO is complete, select it under the **ISO Image** section.
- Underneath the **Set up unattended guest OS installation** menu, to the left side where it says **User Name and Password,** Create your username and a secure password you're going to remember.
- Directly across in the **OS Installation Options,** skip the Product Key (We won't have one as we don't need to activate Windows) and go straight to naming it under the **Host Name** and **Domain Name** sections. Once finished you should have something that looks like what's pictured below. Hit **Finish**.
<img width="781" height="555" alt="image" src="https://github.com/user-attachments/assets/476b28c6-8c54-4cd6-9fe6-14d42952b271" />

# The Boot Up
- Once you hit **Finish,** VirtualBox will start to set up. Let it install Windows 11, ***DO NOT press/do anything until it is through.***
