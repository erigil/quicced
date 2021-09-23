# quicced
Menu-based post-installation script for FreeBSD \
**quicced is in no way affiliated, approved, sponsored, or related to the FreeBSD Project or FreeBSD Foundation**

**!!!WARNING!!!**\
quicced is still in *VERY* early alpha stages. Unexpected breaks, bugs, glitches, etc. may occur.

## About
What started out as a small script for me to quickly configure a FreeBSD system is now turning into a large project. It's mostly functional; with bugs of course.

## Features
- Install and configure graphics drivers
- Install Xorg, plus a selection of Desktop Environments and Window Managers
- Install OSS and audio mixers
- Install misc. software such as web browsers, office software, text editors, etc.

## Experimental Features
- Enable Linux Compatibility

## About Experimental Features
Experimental Features is a section in the main menu where features/options go if they aren't fully working.

## Planned Features
- NVIDIA drivers
- VirtualBox drivers
- Jail deployment
- Server software
- Template system

## Known Bugs
- KDE Plasma crashes in VirtualBox
- Linux Compatibility may cause issues if run more than once.
- WPrefs fails to launch in Window Maker **Workaround: execute the following in the terminal to launch it**
`/usr/local/GNUstep//Applications/WPrefs.app/WPrefs`

## Questions That Will Eventually Get Asked
Q: Why make yet another install script for FreeBSD?\
A: I wanted to make my own

Q: What sets this apart from the others?\
A: The eventual goal is to have the ability to create "templates" that you can run to automatically setup your system the way you want without having to go through the menu system again.

Q: Who is this for?\
A: People who already know how to setup FreeBSD and want a quick way of doing it

Q: I have a question about X\
A: If it's related to the program feel free to ask in the issues. If it's related to anything else, look elsewhere.
