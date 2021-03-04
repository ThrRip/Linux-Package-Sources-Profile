# Linux-Package-Sources-Profile

The Profile of Linux Software Package Sources - Arranged by ThrRip

## Introduction
This repo provided some useful profiles for Linux distros. Now you can get the package sources profiles with 12 location of mirror servers provided, and 3 Linux distros supported - directly, instead of edit by yourself.

## Usage
1. Check the 'Actions' page of this repository and enter into the entry of the latest workflow
2. Scroll down and you can see, there are so many files in the 'Artifacts' section
3. According to the region and OS where your PC or server is located, choose the one that is most suitable for you
4. Right-click it and copy its link, use `curl` or `wget` to download it to your target machine
5. If you are using Debian or Ubuntu, `mv` it to `/etc/apt/`. If you are using CentOS, `mv` it to `/etc/yum.repos.d/` and uncompress it with `unzip`
6. Run `apt update` for Debian or Ubuntu and `yum clean all && yum makecache` for CentOS
Enjoy!

## Author
ThrRip  
Website (Chinese only): [ThrRip's Personal Homepage](https://thrrip.space)
