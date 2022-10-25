---
layout: post
title: Getting games
author: Sam
date: 10/22
---

Okay, now you have a PC. It is set up to your liking. Now it is time to game.

## Steam

The best place to find and buy games for your PC is (big shocker) a game store. There are a bunch of game stores for Windows, but the most popular by far is Steam.

You can get Steam through all the utilities I mentioned in the PC setup article, e.g. WinUtil and Winget or [downloading the installer](https://cdn.akamai.steamstatic.com/client/installer/SteamSetup.exe). Steam has over 200 000 games!

Upon launching, Steam will great you with a sign-in page. If you do not already have an account, make one. 

![Steam Sign In](https://github.com/Dispatch9001/moonwalk/raw/master/images/steam.png)

I recommend you click Remember Me, otherwise you will need to sign in again every time you boot Steam. 

Steam gets regular sales, so if you are a bargain hunter, you can monitor Steam Sale dates to see when the best time to buy games is. In sales, new games will get 10-30% off, but older games can get some insane discounts like 75-90% off. I got Star Wars Battlefront 2 for $7.50, since it was on an 85% discount of its regular price ($50)! Some game specific Steam sales are random, but the big ones are for all games at set times of the year. PC Gamer has [an article](https://www.pcgamer.com/steam-sale-dates/) with all known future Steam sale dates. [gg.deals](https://gg.deals/deals/steam-deals/) has a list of all current Steam deals that is automatically updated.

## Other Stores

If you want to play older games, take a look at [gog.com](https://www.gog.com/). GOG is a great store full of new and old games, but they are known for working hard to keep older games working with new OSes (unlike Steam, who leave that to the game devs). They even have the original Mortal Kombat series and DOOM. GOG also stands out from Steam for distributing the game's DRM free, and with proper offline support.

If you want the Epic Games games like Fortnite or Fall Guys, you need to get the [Epic Games Launcher](https://store.epicgames.com/en-US/). It is arguably Steams main competitor, but it has a much smaller game library. Lucky, there is nothing stopping you from using both! The Epic Games launcher is available through WinUtil and Winget, or you can download the launchers' installer [here](https://launcher-public-service-prod06.ol.epicgames.com/launcher/api/installer/download/EpicGamesLauncherInstaller.msi).

The growing market of indie games has its own store too. [Itch.io](https://itch.io/) is that store, with hundreds of games from up-and-coming developers. Itch has desktop, browser and Android games. The browser games can be played in your browser (big surprise), but the desktop app lets you play both desktop and browser games in one place. In the desktop app, you can even play the browser games offline! Sadly, Itch.io is not on Winget yet, but you can still get it manually via [installer](https://itch.io/app/download?platform=windows).

The Microsoft store is not primarily a game store, but it still is home to many games. It includes some major titles like Minecraft and Roblox, but unfortunately, it is also filled with low effort, low-quality games. To see what I mean, see this list inside the Microsoft store for its "best-selling" games. It is already installed on all computers running Windows 8 or higher.

![daaaamn those are some crappy games](https://github.com/Dispatch9001/moonwalk/raw/master/images/slots.png)

## Minecraft

Minecraft is quite different to most other games, so I decided to give it its own section. Until recently, you had to buy Minecraft on PC through [the Minecraft website](https://www.minecraft.net/en-us), but now you can get both Java and Bedrock edition in the Microsoft store. They come together in one package for one price, so you do not have to chose between them anymore.

Bedrock VS Java is a controversial argument that I will not get into in this website, but to put it simply you can use Bedrock for easier cross-platform multiplayer, and Java for modding.

If you want to get into modding Java edition, you should get a custom launcher. Custom launchers make it easy to manage mods and modpacks. I recommend [GDLauncher](https://gdevs.io/) for beginners (it is easy to use) and [Prism Launcher](https://prismlauncher.org/) for more advanced users, as it has a lot of power features but requires significant technical knowledge to use. Both are available from Winget and installers on their respective websites.

You can safely get Minecraft mods, modpacks and other content from [Curseforge](https://www.curseforge.com/minecraft/mods) and [Modrinth](https://modrinth.com/). All these mods are virus scanned, and the websites have strong moderation teams. 

I actually develop a modpack for Prism Launcher (GDLauncher release coming soon) called Clarity, to improve game performance and add general quality of life improvements called Clarity. You can install it to Prism by using Add Instance > Import from zip > Pasting `https://github.com/IntoTheVoid-900/clarity/raw/main/Clarity-MultiMC.zip` into the box > OK. 

![Clarity](https://github.com/Dispatch9001/moonwalk/raw/master/images/clarity.png)
(A screenshot taken in my modpack with Classic Faithful and Complementary Shaders Reimagined)

## Emulation

> "I think the best games on PC are not even PC games" - TheMan, 2022

For many people, their favourite games on PC are emulated games from other devices. The retro console emulation community is massive, and it is fun to beat up mobile gamers with a keyboard and mouse. (***Disclaimer, I mean beating them in game using your PC peripherals as an advantage. I do not condone violence against mobile gamers***).

The [RetroArch](https://www.retroarch.com/) emulator lets you play games from almost any classic console. I am not going to make a deep dive guide on it here, but keep it in mind if you ever want to play retro games. Just a warning, it is illegal (although largely unenforced) to download game ROMs on the internet. The legal way to do it is to buy the old game cartridges and dump the files, but I do not think Nintendo or any other classic console maker is going to sue you for downloading one of their old games online. It is available through Winget, Steam, Itch.io or via the [installer on their website](https://www.retroarch.com/index.php?page=platforms).

![RetroArch](https://github.com/Dispatch9001/moonwalk/raw/master/images/arch.png)

[Bluestacks](https://www.bluestacks.com/) is an Android emulator for PC focused on gaming. It has great performance, and heaps of great features for gaming like key mapping, full-screen support and resizable windows. It is the best in its field by far, and I recommend it for playing mobile games on PC. Cool tip, you can buy Minecraft on Android for $10 and play it through Bluestacks instead of paying $40 for Minecraft PC. Among Us is also free on Android but paid on PC, so you can run the mobile version through Blustacks. Both games have keybindings set up out-of-the-box in Bluestacks. It is available through Winget and the installer on their website (which I cannot link due to the annoying nature of the link on their site).

<iframe width="100%" height="360"
src="https://piped.kavin.rocks/embed/TvMG6kPcOjk">
</iframe>

Some modern consoles can also be emulated. Most of them are in early beta, apart from the Nintendo Switch emulators. I am not going to go into much detail because they are a major legal grey area, but the most popular ones are [Yuzu](https://yuzu-emu.org/) and [Ryujinx](https://ryujinx.org/).
