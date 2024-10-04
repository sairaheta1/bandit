# Bandit Notes
---
## Intro
These are my personal notes as I complete the game Bandit over at [OverTheWire](overthewire.org).

### Login Script
Since the command `su` to switch users won't work on the connected server, I created a short script `bandit.ssh` to speed-up the process of logging in. 

The password to each level is stored in a file and it's copied to the clipboard automatically when running the script, so that you can simply paste it when prompted. Likewise, when finishing a level, you can choose to store the password for the next level or not, by pasting when prompted.

### Commands Cheatsheet
My cheatsheet for commands (excluding some obvious ones such as ls, cd, etc.) can be found in `cmds.md`

---
### Level 1
