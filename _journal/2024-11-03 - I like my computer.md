---
published: true
subtitle: 
date: 2024-11-03
tags: tech, computer, linux, windows
---

#  2024-11-03: - I like my computer

![I love my puter, all my friends are inside it](/images/ilovemyputer.png)

## Trial and Error

A few weeks ago I installed Linux on my computer.
While there were a few good reasons, like it being supposedly better for working with Godot (which I decided to make Project Remiworld in, after RPGMaker has turned out to be more of a burden than a crutch) ultimately it was just spontaneous and on a whim.

This was not the first time, as over the years I must have tried it out at least 3 times in total. So far I had tried out Linux Mint (Debian Editon)[^1] multiple times, failed on plain Arch because I couldn't get my Sound to work among other things, failed to install Gentoo because I didn't have LAN, had constant *krashes* on KDE Neon after using it for almost a month(!), etc etc.
Every time I ended up going back to Windows. Especially the releases of modified versions  of it, that rip out Microsofts Telemetry and whatever janky, broken garbage their outsourced indian "engineers" manage to cobble together, starting with the [Ameliorated Windows Project](https://ameliorated.io/) up to my favorite [RevisionOS](https://revi.cc/)[^2] - which I still install on any friends or relatives PC whenever I have to play tech support for them.

[^1]: I liked [Linux Mint](https://abriefhistory.org/?p=774), but I have a dislike for Ubuntu, so I chose the Debian Version. Unfortunately a lot of packages are out of date, which also ironically makes it especially hard for a beginner to follow guides and such.

[^2]: They don't offer an .ISO anymore - only the post-install playbook-script.
	Luckily I still have the latest .ISO they published.

## I use Arch, btw.

So I was contemplating to switch to Linux, when a friend of mine told me about [EndeavourOS](https://endeavouros.com/), which is basically just Arch without the hassle of going through an Install script myself + having various things already set up and configured. I am not some /g/tard that wants to spend all day working *on* their computer, instead of using their computer for work.

So I eventually went ahead and just installed it.
I got convinced to give KDE Plasma another try, which EndeavourOS offers during the install. Something about better performance by using Wayland(which my beloved XFCE doesn't support yet) in games and stuff. 
Although I stopped playing those because they were quite the time sink, in a day, that already never seems to have enough time for everything I want to do.

As I was using it for a while, not really caring much for taking on the beast of customizing anything yet, things started to get a little on my nerves.

## KDE sucks

While overall it worked, and surprisingly there were no trademark KDE *krashes*, little things were bugging me or did in fact not work. Discord screensharing is an example. 
Eventually the frustration pent up; I didn't even like looking at Plasma. The KDE design philosophy wastes way too much space and is honestly quite ugly. I could have fixed that by theming and customizing myself for hours, but that wouldn't have fixed any of the other issues.

## No human wants to read manuals

So I dared to do something risky. First I installed XFCE. And then upon booting it up I immediately decided *"Yeah. I am going to remove all this **Krap**."* So I spent a good 2 hours in despair, ripping out the HRT-fueled nervous system of my OS, wrestling with a billion packages that are in a dependency circle and for some reason include OS-critical software like *libblock* and *udisks2* probably breaking things I haven't even discovered yet.
This made my password manager for (ungoogled)chromium entirely broken, because apparently that is linked to my KDE keyring. It took quite a while to figure that out. 
What took even longer was fixing my Login manager, because I accidentally managed to break it, so I could not log in anymore, after I installed gtk-mini-greeter for lightdm.

What I didn't mention yet, was that the only reason I was able to do all this, was thanks to ChatGPT.

While it isn't perfect, and sometimes makes up solutions using commands or configs that don't even exist, most of the time it is a splendid troubleshooter and instructor, that saves you the time and sanity of going through horrible, either verbose or entirely incomprehensible manuals yourself. This is invaluable.

Where it couldn't help me however, was my fuckup with the mini greeter. Even AI couldn't fathom someone being so stupid, not to read the warning that tells you to add your username to the config right after installing. Oops.

## My beloved Mouse

So there I am. Back on XFCE. A beautiful desktop Environment from the start. It's fast and it just works. Even my Discord screenshare works now. Perfect.

![Xfce Logo](/images/xfce.svg)
*I am fond of the mouse logo. You may know that I have pet rats and also used to have mice.*

But since I somewhat know and remember how to customize XFCE, I kind of get the itch to do so. 
So I go look at themes, and to my delight, I see that someone made an improved Version of the Windows95-style Chicago95 theme, called [Redmond97](https://github.com/matthewmx86/Redmond97). Old tech just has SOVL. I don't care what you think.

![Win95 PC](/images/win95pc.png)
*A typical PC before the 2000s. Mogs all modern, soulless, sleek, minimalist globohomo designs into oblivion.*

Then I change some color schemes, customize my panels, get a nice wallpaper and adjust it's hue to match the DE, and there we have it. A beautiful Computer that brings me joy to use, by aesthetics alone. I think this is very important. It helps motivating you into work, if said work requires your computer. It is also important to look at beautiful things often - I will write about this some other time.

> "holy fuck that looks disgusting" - immediate response upon sharing a screenshot of my desktop on discord

To conclude this entry, I want to share my wallpaper with you. Maybe you enjoy it as much as I do.

![red remco wallpaper](/images/redremcobg.png)