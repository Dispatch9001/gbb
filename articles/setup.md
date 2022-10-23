---
layout: post
title: Seting up your PC
author: Sam
date: 10/22
---

Now that you have a PC, you need to start seting it up and making it yours.

## Update!!!!

The first thing to do with any device (after you sign in and connect to WiFi) is to update. You will need to apply both system and application updates. Thanks to recent developments in Windows, both are now really easy.

For system updates, you just neeed to go to settings and scroll down to Windows Update. In the update menu, scan for updates and then download/apply all of them. Until your computer is updated, it is still very vunerable to old security threats like viruses that you would otherwise be protected from.

For app updates, you can go to the Microsoft store and update all. For other apps, CTTs WinUtil (which I talk about a lot in later paragraphs) includes an app update button.

## Debloat the system.

If you bought a prebuilt PC or a laptop, you were likely sold a device with a lot of bloatware. Bloatware is a type of app that is preinstalled on your system that you will likely never use. Bloat slows down your computer, and likely invades your privacy. There are two types of bloat that we will remove today: Manufacturer bloat and Microsoft bloat.

### Removing Manufacturer Bloat

The two main ways of removing manufacturer bloat are reinstalling Windows, and bulk uninstalling the apps. I recommend completly reinstalling Windows, because it is the only way to be completly sure all the bloat is gone. PCMag made a [great guide](https://www.pcmag.com/how-to/factory-reset-windows-10). **Make sure you remove everything**.

If you don't want to reinstall, you can install [BCUninstaller](https://www.bcuninstaller.com/), and go through every app. If you don't think you want/need it, uninstall it. Be careful, do not uninstall a system app. To be safe, make sure to click "Create Restore Point" in the uninstall menu.
![Create Restore Point](/images/bcu.png)
After uninstalling, make sure you scan for leftovers.
![Scan for leftovers](/images/bc2.png)

### Removing Microsoft Bloat

After a manufacuter debloat (or on a custom PC), there are still bloat apps left. These are Microsofts bloat apps, and they are a bit trickier to remove.

First thing to do, remove all the pins from the start menu that you didnt add (I am looking at you, Candy Crush and Netflix). Then open up BCUninstaller and do the steps from removing manufacterer bloat. If you already did this in the manufacturer bloat, there is no need to repeat.

After that, there are still the annoying Microsoft background services. I use CTT WinUtil to remove them. To do that you:

1. Open a Powershell window as administraitor. You can do this by clicking the windows button, searching powershell, and clicking "Run as Administraiter".
![Run Powershell as Administraitor](/images/powershell.png)
2. Paste in the command `irm christitus.com/win | iex` and click enter.
![Paste the command](/images/ps2.png)
3. In the window that appears, navigate to the "Tweaks" tab
![CTT WinUtil](/images/ctt.png)
4. Click the recommended suggestions for laptop or desktop (depending on what you have)
5. If you want to use 7-zip in Windows 11, enable classic right click menu
6. If you want to uninstall Cortana or Edge, tick the respective boxes. **WARNING**: You should not uninstall Edge unless you are an advanced user. Many newer apps use Edge Webview as an alternative to electron, meaning that a rapidly growing number of apps will not work on your system at all. Proceed with caution.
7. Click "Run Tweaks"

Edge is a little more annoying to avoid. If you have installed a different browser and never want to see Edge again, there is a good app for you. [MS Edge Redirect](https://github.com/rcmaehl/MSEdgeRedirect) is an app which does exactly what you would imagine. Whenever your computer goes to start Edge (for example, the web search inside Windows Search which ignores your default browser), it will stop edge from starting, and open the URL in your default browser. It works with Edge uninstalled (with the uninstaller inside WinUtil), but it prefers Edge still being installed. It also has a bunch of nice quality of life features, like redirecting bing searches to a search engine of your choice. Unlike completly uninstalling Edge, it still lets Edge Webview apps work.
![MS Edge Redirect](/images/edgy.png)

## Getting/Updating apps

Until Winget, I would have given you a massive list of links for programs to install on your computer. Thankfully, those days are now over.

Run steps 1 and 2 from the Removing Microsoft Bloat section to start WinUtil.

On the first tab, you have a menu where you can install a bunch of common apps. From here you can install any apps you want use. If you don't know what you want, I suggest you get a browser (I chose Firefox), Discord, the Epic Games Store, Steam, all of the .NET Desktop runtimes, the 64 bit Visual C++, VLC, ImageGlass (an alternative image viewer with support for more image formats), ONLYOffice (A free Microsoft 365 alternative) and 7-zip. 7-zip doesn't work well with Windows 11 (unless you did the right click menu tweak explained in the removing microsoft bloat section). There is an alternative called Nanazip. You can get Nanazip either through the Microsoft store, or the command `winget install M2Team.NanaZip`. 

![Selections](/images/winutil.png)

If there are any apps you want that are not in WinUtil, there are three more ways to get them.

- Advanced users can use Winget directly in the command line, It is pretty easy once you get the hang of it.
![Installing Chrome in Winget](/images/winget.png)
- There are a multitude of Winget front ends to make it easy to use. I personally recommend [WingetUI](https://github.com/martinet101/WingetUI) (It's a desktop app with a great updater for your apps and [scoop](https://scoop.sh/) support) or [Winstall](https://winstall.app/) (A website with a much nicer UI, but it still requires you to copy and paste commands into the command prompt and is a bit buggy).
![UI](/images/ui.png)
- You can do it "the old fashioned way" of going to the website and downloading this. When doing this please be smart. Do not download the apps from unofficial websites, and **do not click ads that look like a download button**.
![Chrome](/images/chrome.png)
