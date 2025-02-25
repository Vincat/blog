+++
date = '2025-02-25T12:56:39+10:30'
draft = false
title = 'Pi Hole V6 Update'
tags = ['Pi-hole', 'dns']
+++

Over the last week, Pi-hole has officially released the long awaited V6. So now V5 will no longer receive updates.  
I have been running 2 Pi-hole V6 Beta on bare metal (Raspberry pi4) for the past 6 months, so now is the time to update them to the official release.  

## How to upgrade  

```bash
sudo apt upgrade && sudo apt upgrade -y
sudo pihole checkout master
sudo pihole -up
```

That should be it. As a side note I have been using [nebula-sync](https://github.com/lovelaze/nebula-sync) to keep the 2 Pi-hole in sync.  

[Updates to the release](https://pi-hole.net/blog/2025/02/21/v6-post-release-fixes-and-findings/#page-content)
