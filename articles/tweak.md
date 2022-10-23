---
layout: post
title: Advanced Tweaks
author: Sam
date: 10/22
---

Here I am going to list some more powerful Windows tweaks for advanced users. If you are a beginner or just not very techy, this article will not be helpful for you.

## Cool apps/tools

- **[Powertoys](https://learn.microsoft.com/en-us/windows/powertoys/)**
Microsoft Powertoys is a suite of experimental tools for Windows power users. Powertoys includes so many useful tools, so I would spend a bit of time going through all of them finding what you want. You can get it through Winget or the Microsoft Store


- **[NVCleanstall](https://www.techpowerup.com/nvcleanstall/)**
NVCleanstall is an alterntive installer for NVIDIA graphics drivers. It lets you completly customise the drivers, removing the bloaty features and (slightly) improving performance
Guide:

<iframe width="100%" height="360"
src="https://piped.kavin.rocks/embed/watch?v=LR1XkjtylCM">
</iframe>

- **[ExplorerPatcher](https://github.com/valinet/ExplorerPatcher)**
I personally do not like the Windows 11 start menu. In 10, I had the tiles set up with all my apps, organised beautifully. Then when 11 came along I lost mÿ beautiful organisation to this embarrasment of a menu. 
![Windows 11 Start Menu](/images/trashstart.png)
Then I found ExplorerPatcher. ExplorerPatcher is an open source program for patching Windows 11 UI elements. It is built for people like me who are disatisfied with Windows 11. It gives options to control most Windows 11 UI changes, with the ability to revert some features back to 10, 7 or even XP!
![ExplorerPatcher](/images/ep.png)
Thanks to Explorer Patcher I can give my Windows laptop a Windows 10/11 hybrid UI, with a Windows 10 style start menu, connected to a Windows 11 taskbar, with a Windows 11 file explorer that uses Winodws 10 right click menus.
![Sicko Start](/images/sickostart.png)


- **[WSL](https://learn.microsoft.com/en-us/windows/wsl/)**
The Windows Subsystem for Linux is an essential tool for any developer. It lets you run full Linux shells inside Windows, which integrate into your Windows system. Most of this website was written in the [micro](https://micro-editor.github.io/) text editor inside Debian Linux through WSL. WSL can run Windows command prompt/powershell commands inside the Linux shell, which has let me fully replace the command prompt with Powershell. It is an amazing piece of software that I do recommend.
![My Setup](/images/deb.png)


- **[Scoop](https://scoop.sh/) and/or [Chocolatey](https://chocolatey.org/)**
Scoop and Chocolatey are both alternative package managers for Windows. They are both significantly older than Winget. In fact, Wingets earliest betas (OneGet) used Chocolatey's repositories. They both have different advantages and disadvantages, but they are compatible so you might as well have them both! 

Scoop installs apps in a portable format in a custom directory, meaning that the application does not touch any folders outside of its own. This is good, because it means that apps do not need administraighter to install. The only problems is that the apps are not automatically registered to Windows, meaning it is much harder to set a scoop app as your default browser or text editor. Scoop is great for simple command line tools though, like [gsudo](https://github.com/gerardog/gsudo#gsudomodule) (a recreation of Linux's `sudo` command for Windows).

Chocolatey needs full administraitor access every run, and installs apps in a more traditional method, but it still isn't the same.


I have hundreds more tools that I love, but this list would be one of the longest website articles of all time. These are my top 5 (in no particular order).

## Privacy

- **O&O Shutup10**
O&0 Shutup10 is a tool to remove a lot of Microsofts telementary and spyware from Windows. It is ran in WinUtils recommended tweaks for both laptops and desktops, so you should have it already running.
- **Arkenfox/Librewolf**
Arkenfox and Librewolf are both privacy and security focused Firefox tweaks. They are open source and majorly improve Firefox's security. Arkenfox is for very advanced users because it is completly DIY, while Librewolf is tweaked out of the box.
- **uBlock Origin**
uBlock Origin is an content blocker for Chrome and Firefox (and all their forks) which is so much more powerful than any other adblocker. It has so many advanced features for privacy, security and quality of life.

## [Windows 10 Ameliorated](https://ameliorated.info/#)

If you really want the most pure, private and performant Windows system you can get, try Windows 10 Ameliorated. It is a very advanced modification for Windows that completly cleans Windows on a different level to all the other debloating projects. It does come at a cost. Microsoft Store apps will not work, Windows Updates won't work, Windows Defender will not work, and a lot more will be changed. If none of that is a problem to you, and you have a lot of technical know-how then AME might be for you. I personally don't use it because I rely on a few MS store apps, but it is the ultimate Windows version for gamers.

**WARNING: Do not download the ISO. You need to build it yourself.**
