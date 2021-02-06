---
title: Exploring Your Environment In Linux
layout: post
categories: Linux
tags:
- centos
- rhel
- environment
- environment variables
- en
---

Finding out your operating system's current state can be crucial. This state is determined via *environment variables*. With some variables  system settings like your keyboard layout, default terminal and preferred language can be set and some variables are used by operating system to find where a executable binary is or the working directory of some software. So, these variables is similar to a compass or your car's user manual, where important info can be found in need.

Although most Linux users leaves these variables untouched, sysadmins often needs to change and check for them. So let's get started.

## My working environment


**BEWARE:** Below is the working environment I used writing this post. The commands and results may slightly vary for different linux distributions. Always check your OS' official docs site.

* OS - Centos 8.2
* Kernel - xxx
* Host - Vm, hosted Vmware Workstation


### So, show me those variables

To see the current environment variables and their values for your accound issue  `env` command - w/o arguments -.

``` console
cephei@battlestation:~$ env
```

TODO

### Important files behind the scene

### How to set environment variables