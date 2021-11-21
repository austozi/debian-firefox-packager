# Upstream DEB Packager
This repository contains scripts to package the latest upstream releases of selected software.

# Why?
I use Debian Stable as my main operating system. The official Debian repositories for the stable release do not include certain software packages, such as the regular release of Firefox (Debian only ships the extended support release, or ESR, of Firefox). I wrote these scripts to supplement the software offering of the official Debian repositories.

I have set up a cron job on my home server to trigger the automatic packaging of the selected software, and publish them to a personal repository using [reprepro](https://packages.debian.org/stable/reprepro). I have added the personal repository to the source list of various devices running Debian stable, so the packaged software is available as regular upgrades. 
