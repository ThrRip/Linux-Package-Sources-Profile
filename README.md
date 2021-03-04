# Linux-Package-Sources-Profile

The Profile of Linux Software Package Sources - Arranged by ThrRip

## Introduction
This repo provided some useful profiles for Linux distros. Now you can get the package sources profiles with 12 location of mirror servers provided, and 3 Linux distros supported - directly, instead of edit by yourself.

## Usage
### 'Releases' Method (Recommend)
1. Click [here](https://github.com/ThrRip/Linux-Package-Sources-Profile/releases/latest) to check the latest release of this repo
2. According to the region and OS where your PC or server is located, choose the one that is most suitable for you
3. Copy its link and use `curl` or `wget` or any downloader with GUI to download it
4. If you are using Debian or Ubuntu, `mv` it to `/etc/apt/`. If you are using CentOS, `mv` it to `/etc/yum.repos.d/`. Uncompress it with `unzip`
5. Run `apt update` for Debian or Ubuntu and `yum clean all && yum makecache` for CentOS
**_Enjoy!_**
### 'Actions' Method (GitHub login required)
1. Check the 'Actions' page of this repository and enter into the entry of the latest workflow
2. Scroll down and you can see, there are so many files in the 'Artifacts' section
3. According to the region and OS where your PC or server is located, choose the one that is most suitable for you
4. Download it, and if you are planning to use it on a server, then upload it to your target machine
5. If you are using Debian or Ubuntu, `mv` it to `/etc/apt/`. If you are using CentOS, `mv` it to `/etc/yum.repos.d/`. Uncompress it with `unzip`
6. Run `apt update` for Debian or Ubuntu and `yum clean all && yum makecache` for CentOS
**_Enjoy!_**

## Author
ThrRip  
Website (Chinese only): [ThrRip's Personal Homepage](https://thrrip.space)
