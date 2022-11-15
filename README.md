# DNS-Hole - List for hole domains

The following lists are used in [Open BLD DNS](https://lab.sys-adm.in) project

## Lists

* dns-blocklist.txt:     list of blocked domains
* whitelist.txt:         list of whitelisted domains
* bld-testing:           list of test Sys-Admin BLD service
* regex                  common regexed domains bl/wl
* vendors                some vendors, like as Google, Microsoft, Yandex whitelisted in the separated files

## Aggregated lists

All bl/wl lists aggregated in to solid and sorted files with [BLD-Agregator](https://github.com/m0zgen/bld-agregator.git) project and this files daily updated and refreshed, and available with URL's:

* [blocklist.txt](https://raw.githubusercontent.com/m0zgen/bld-agregator/data/blocklist.txt)
* [allowlist.txt](https://raw.githubusercontent.com/m0zgen/bld-agregator/data/allowlist.txt)

## Report an issue

If you have any problems with web-resources availability while using BLD service, feel free to report an [issue](https://github.com/m0zgen/dns-hole/issues) using the following template:

**1. Short issue description**

**2. Time of issue with timezone:**

e.g. 20.11.2021 15:44 GMT+3

**3. Ensure what the resource work without BLD**

Perform these steps to check:
1. Disable BLD
2. Clear browser cache / reload page with `Shift+F5` or `Ctrl+Shift+R`
3. Restart browser / reboot device
4. Check the resource again: is it available?
5. Enable BLD
6. Check if the issue persist

**4. Steps to reproduce**

    1. Open example.com / Run some app
    2. Navigate to ...
    3. ...
    4. ...
    5. No expected page block ... / Got 404 / Media doesn't play

**5. Device on which the issue occured**
- Device: *e.g. Desktop, LG Smart TV, iPhone 10, Xiaomi A3*
- OS version: *e.g. Windows 10 21h1 build 19043, Ubuntu 20.04, Android 10, Custom firmware (with details)*
- Browser version: *e.g Firefox 94.0.1, Chrome 96.0.4664.45*
- Apps affected (if any): *e.g. YouTube, Instagram*

**6. Details on how BLD is set up**
* BLD service address used
* Configuration type:
    - on device (system-wide configuration)
    - in a browser
    - on a network router
* Protocol:
    - DoH (DNS over HTTPS)
    - DoT (DNS over TLS)

**7. Screenshots**

**8. Additional context that may help to investigate the issue**
