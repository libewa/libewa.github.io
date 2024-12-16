---
layout: post
title: Why I use Bone (and how I did it)
date:
tags: typing code ipad
---
Typing is part of our everyday lives. Coding involves text, and if you're not using MSPaintIDE, you probably use a keyboard to enter text. And if the code gets longer, you might see your fingers strained. A few months ago, I someway heard of the Neo layout, which is designed to ease typing in both German and English, and also has more layers containing a lot of exotic symbols such as ⊥ (orthogonal to), ⊂ (subset of), ♀♂⚥ (the gender symbols), and the normal and zero width non-breaking spaces. Every one of the six layers also has three deadkeys, and there is a Compose system (on Windows and Linux), allowing you to set basically every Latin-based character.

It is, however, quite different from QWERTY (or QWERTZ, a version of QWERTY enshittyfied for German typewriters), so it requires a bit of learning, and my method, which I can definitely recommend: Go to a coding camp or hackathon, and write your code with that new layout.

Setting it up on different systems required a varying amount of effort, ranging from Windows (installing a keyboard driver and copying an EXE to `shell:startup`) to iPad (looking up every single character to create a custom layout in a paid app).

## Windows setup
For Windows setup, I just followed the official [kbdneo] installation instructions, downloading the Bone versions of both kbdneo and ReNeo.

## Linux setup
While Neo and Bone are included as keyboard layouts, Neo variants other than Neo2 are hidden away. After a lot of research and giving up, I found that it is simply ... `de bone`. And so I entered that into my Hyprland config, and I saw that it was good.

## iOS setup
iOS does not support Neo out of the box like Linux does, nor does it support layout drop-ins like macOS or Windows do. (If you can call copying DLLs to System32 and SysWOW64 and installing a registry patch a drop-in)

[kbdneo]: https://neo-layout.org/Einrichtung/kbdneo