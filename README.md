# openbsd-router
OpenBSD makes a great router.  This configuration is derived from [openbsd.org](https://www.openbsd.org/faq/pf/example1.html):

- DHCP server for lan
- Secure DNS for lan
- Local records for common hosts
- Reverse dns lookup for common hosts

# Why
Typical consumer routers ship with seldom updated software with poor user interfaces.  Additionally the
hardware itself is underpowered, whereas one can build a high performance router for $400USD that
provides rock solid performance, security updates, and the ability to perform advanced network
operations such as traffic shaping, quality of service, and most importantly not rebooting your 
router every month and having people wonder if its their device or the network.
