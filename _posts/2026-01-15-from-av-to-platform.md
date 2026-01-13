---
layout: post
title: "From AV Engineer to Platform Engineer - Week 2"
date: 2026-01-15
---

## Week 2 Progress Update

Week 2 was focused on building conistency and getting more comfortable working directly in Linux and GitHub. Rather than trying to move too fast my goal this week was to strengthen fundamentals and start forming better habits around documentation and experimentation. 

---

## What I Focused On

### Installing Ubuntu on Lenovo T440
This week, I installed Ubuntu on a Lenovo T440 laptop to create a dedicated Linux lab environment. The goal was to move beyond virtualized environments and work directly with Linux on bare hardware. 

The installation process requred troubleshooting several BIOS-related challenges, including:
- Switching between UEFI and Legacy boot modes
- Correctly configuring boot priority for USB devices
- Understanding how Secure Boot and legacy settings affect Linux installs

Working through these issues helped me better understand how firmware, bootloaders, and operating system installation interact at a lower level. 

---

### Linux Fundamentals (Hands-On)
After completing the installation, I spent time working directly in the Linux terminal to become more comfortable navigating and administering the system. 

### Practicing Core Linux Shell Commands

I focused on building comfort with basic Linux shell commands by working through real file and directory operations directly in the terminal. 

Rather than following a scripted tutorial, I intentionally experimented, made mistakes and corrected them to better understand how Linux responds to user input.

Commands I practiced included:

- 'ls' to list files and directories
- 'cd' to navigate between directories
- 'cp' to copy files between directories
- 'rm' to delete files
- 'cat to creat and view text files
- 'history' to review previously executed commands

Below are screenshots from my terminal session showing the file navigation, file creation, copying files, and deletion. 

**Creating and viewing a file with cat**

![Creating and viewing a file with cat](/assets/images/week2/cat%20file1%20.png)

**Troubleshooting directory navigation issues**

![Troubleshooting directory navigation issues](/assets/images/week2/cd%20troubleshooting.png)

**Fixing file copy issues with cd**

![Fixing file copy issues with cd](/assets/images/week2/cp%20fixed.png)

**File deletion using rm**

![File deletion using rm](/assets/images/week2/rm%20file.png)

The biggest improvement this week was feeling less "lost" in the terminal and more intentional with commands.

---

## Challenges This Week

The biggest challenge this week was troubleshooting the Ubuntu installation on older hardware.

Dealing with BIOS settings, boot modes, and USB detection required patience and methodical testing. While frustrating at times, it reinforced the importance of understanding system behavior rather than relying on step-by-step guides alone.

This experience highlighted how real-world systems often require investigation, experimentation, and presistence-skills that translate directly to infrastructure and platform engineering work.

When working with Linux shell commands, I frequently encountered errors such as attempting to copy or delete files from the wrong directory which resluted in messages like "No such file or directory." Working through these mistakes helped reinforce the importance of understanding reletive vs. absolute paths and being aware of the current working directory at all times.

---

## What I Learned

- Comfort in Linux comes from repetition, not memorization
- Linux error messages are often the fastest way to understand what went wrong if you slow down and read them carefully
- Git makes more sense when used consistently on a real project
- Clear documentation is a skill, not an afterthought
- Linux installation issues often stem from firmware and boot configuration, not the OS itself
- Troubleshooting requires isolating variables and testing one change at a time
- Hands-on setup builds confidence faster than tutorials alone
 
 ---
## Looking Ahead to Week 3

Next week, I plan to:
- Coninue strengthening Linux fundamentals
- Begin automating small tasks using shell scripts
- Start exporing container concepts at a high level

The focus will remain on learning by doing and documenting progress along the way. 

