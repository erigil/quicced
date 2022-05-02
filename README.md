# quicced
Menu-based post-installation script for FreeBSD systems.\
**quicced is in no way affiliated with, approved by, sponsored by, or related to the FreeBSD Project or FreeBSD Foundation**

**!!!WARNING!!!**\
quicced is still in *VERY* early alpha stages. Unexpected breaks, bugs, glitches, etc. may occur.\
Radeon and Intel graphics drivers are untested as I do not have a computer with that hardware readily availible. However they **SHOULD** work.

## About
What started out as a small script for me to quickly configure a FreeBSD system is now turning into a large project. quicced is a simple-to-use menu-based script that allows you to to intsall and configure various programs, drivers, etc. The evntual goal is to create something that will allow people to create "templates" after they finish running the script. These templates will be small scripts that contain all the options you selected so you can setup an identical system easily without having to go through the menus again.

## Features
- Install and configure graphics drivers
- Install Xorg, plus a selection of Desktop Environments and Window Managers
- Install OSS and audio mixers
- Install misc. software such as web browsers, office software, text editors, etc.
- Applies workarounds to various bugs
- Basic template system (Shell script that saves your choices so you can apply the same changes/configurations to another system.)

## About unstable Branch
New features, not fully tested.

## Planned Features
- NVIDIA drivers
- VirtualBox drivers
- Jail deployment
- Server software
- Additional DEs/WMs
- Kernel tuning

## Known Bugs
- KDE Plasma crashes in VirtualBox (KDE Plasma specific, but still useful info.)
- WPrefs fails to launch in Window Maker (Window Maker specific, but still useful info.) **Workaround: execute the following in the terminal to launch it**\
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
