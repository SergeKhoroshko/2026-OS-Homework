# Завдання 1. Ієрархія каталогів Linux (1 бал)

# Перейди в кореневий каталог / і покажи вміст;
test@test-VirtualBox:~$ cd /
test@test-VirtualBox:/$ 

test@test-VirtualBox:/$ pwd
/

test@test-VirtualBox:/$ ls -lah
total 4.1G
drwxr-xr-x  23 root root 4.0K Jul  5 15:56 .
drwxr-xr-x  23 root root 4.0K Jul  5 15:56 ..
lrwxrwxrwx   1 root root    7 Apr 22  2024 bin -> usr/bin
drwxr-xr-x   2 root root 4.0K Feb 26  2024 bin.usr-is-merged
drwxr-xr-x   3 root root 4.0K Jul  5 17:28 boot
dr-xr-xr-x   2 root root 4.0K Feb 10 02:38 cdrom
drwxr-xr-x  19 root root 4.1K Jul  6 22:21 dev
drwxr-xr-x 140 root root  12K Jul  5 19:02 etc
drwxr-xr-x   4 root root 4.0K Jul  5 19:00 home
lrwxrwxrwx   1 root root    7 Apr 22  2024 lib -> usr/lib
lrwxrwxrwx   1 root root    9 Apr 22  2024 lib64 -> usr/lib64
drwxr-xr-x   2 root root 4.0K Apr  8  2024 lib.usr-is-merged
drwx------   2 root root  16K Jul  5 15:52 lost+found
drwxr-xr-x   3 root root 4.0K Jul  5 17:18 media
drwxr-xr-x   2 root root 4.0K Feb 10 01:19 mnt
drwxr-xr-x   3 root root 4.0K Jul  5 17:28 opt
dr-xr-xr-x 280 root root    0 Jul  6 22:21 proc
drwx------   5 root root 4.0K Jul  5 16:36 root
drwxr-xr-x  35 root root  920 Jul  6 22:27 run
lrwxrwxrwx   1 root root    8 Apr 22  2024 sbin -> usr/sbin
drwxr-xr-x   2 root root 4.0K Mar 31  2024 sbin.usr-is-merged
drwxr-xr-x  15 root root 4.0K Jul  5 19:13 snap
drwxr-xr-x   2 root root 4.0K Feb 10 01:19 srv
-rw-------   1 root root 4.0G Jul  5 15:56 swap.img
dr-xr-xr-x  13 root root    0 Jul  6 22:21 sys
drwxrwxrwt  18 root root 4.0K Jul  6 22:27 tmp
drwxr-xr-x  12 root root 4.0K Feb 10 01:19 usr
drwxr-xr-x  14 root root 4.0K Jul  5 16:35 var

# Перейди в /etc і покажи вміст;
test@test-VirtualBox:/$ cd /etc
test@test-VirtualBox:/etc$ pwd
/etc
test@test-VirtualBox:/etc$ ls -lah
total 1.2M
drwxr-xr-x 140 root                 root                  12K Jul  5 19:02 .
drwxr-xr-x  23 root                 root                 4.0K Jul  5 15:56 ..
-rw-r--r--   1 root                 root                 3.4K Jul  5  2023 adduser.conf
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:28 alsa
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:06 alternatives
-rw-r--r--   1 root                 root                  335 Apr  8  2024 anacrontab
-rw-r--r--   1 root                 root                  433 Apr  8  2024 apg.conf
drwxr-xr-x   5 root                 root                 4.0K Feb 10 01:27 apm
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:09 apparmor
drwxr-xr-x   9 root                 root                  12K Jul  5 17:09 apparmor.d
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:29 apport
drwxr-xr-x   9 root                 root                 4.0K Jul  5 15:51 apt
drwxr-xr-x   3 root                 root                 4.0K Jul  5 16:02 avahi
-rw-r--r--   1 root                 root                 2.3K Mar 31  2024 bash.bashrc
-rw-r--r--   1 root                 root                   45 Jan 24  2020 bash_completion
-rw-r--r--   1 root                 root                  367 Aug  2  2022 bindresvport.blacklist
drwxr-xr-x   2 root                 root                 4.0K Apr 19  2024 binfmt.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 bluetooth
-rw-r-----   1 root                 root                   33 Feb 10 01:31 brlapi.key
drwxr-xr-x   7 root                 root                 4.0K Feb 10 01:28 brltty
-rw-r--r--   1 root                 root                  30K Mar 31  2024 brltty.conf
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:19 ca-certificates
-rw-r--r--   1 root                 root                 6.8K Jul  5 16:02 ca-certificates.conf
-rw-r--r--   1 root                 root                 6.2K Feb 10 01:20 ca-certificates.conf.dpkg-old
drwxr-s---   2 root                 dip                  4.0K Feb 10 01:29 chatscripts
drwxr-xr-x   5 root                 root                 4.0K Jul  5 17:10 cloud
drwxr-xr-x   2 colord               colord               4.0K Jul  5 16:36 colord
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:53 console-setup
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 cracklib
drwx------   2 root                 root                 4.0K Apr 19  2024 credstore
drwx------   2 root                 root                 4.0K Apr 19  2024 credstore.encrypted
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 cron.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 cron.daily
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:19 cron.hourly
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 cron.monthly
-rw-r--r--   1 root                 root                 1.2K Mar 31  2024 crontab
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 cron.weekly
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:19 cron.yearly
drwxr-xr-x   5 root                 lp                   4.0K Jul  6 22:22 cups
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 cupshelpers
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:19 dbus-1
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:28 dconf
-rw-r--r--   1 root                 root                 2.9K Apr 12  2024 debconf.conf
-rw-r--r--   1 root                 root                   11 Apr 22  2024 debian_version
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 debuginfod
drwxr-xr-x   3 root                 root                 4.0K Jul  5 16:02 default
-rw-r--r--   1 root                 root                 1.7K Jul  5  2023 deluser.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:28 depmod.d
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:20 dhcp
-rw-r--r--   1 root                 root                 1.4K Mar 31  2024 dhcpcd.conf
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:31 dictionaries-common
drwxr-xr-x   3 root                 root                 4.0K Jul  5 17:06 dkms
drwxr-xr-x   4 root                 root                 4.0K Jul  5 17:06 dpkg
-rw-r--r--   1 root                 root                  685 Apr  8  2024 e2scrub.conf
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:27 emacs
-rw-r--r--   1 root                 root                  106 Feb 10 01:19 environment
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:31 environment.d
-rw-r--r--   1 root                 root                 1.9K Oct 18  2022 ethertypes
drwxr-xr-x   5 root                 root                 4.0K Feb 10 01:29 fonts
-rw-r--r--   1 root                 root                   20 Apr  4  2024 fprintd.conf
-rw-r--r--   1 root                 root                  473 Jul  5 15:56 fstab
-rw-r--r--   1 root                 root                  694 Apr  8  2024 fuse.conf
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:29 fwupd
-rw-r--r--   1 root                 root                 2.6K Jan 31  2024 gai.conf
drwxr-xr-x   3 root                 root                 4.0K Jul  5 17:09 gdb
drwxr-xr-x   8 root                 root                 4.0K Jul  5 17:10 gdm3
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:31 geoclue
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:27 ghostscript
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:27 glvnd
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 gnome
drwxr-xr-x   2 gnome-remote-desktop gnome-remote-desktop 4.0K Feb 10 01:31 gnome-remote-desktop
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 gnutls
-rw-r--r--   1 root                 root                 3.9K Feb  9 22:03 gprofng.rc
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 groff
-rw-r--r--   1 root                 root                 1.2K Jul  5 19:02 group
-rw-r--r--   1 root                 root                 1.2K Jul  5 19:02 group-
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:33 grub.d
-rw-r-----   1 root                 shadow                999 Jul  5 19:02 gshadow
-rw-r-----   1 root                 shadow                993 Jul  5 19:02 gshadow-
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:19 gss
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 gtk-2.0
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:31 gtk-3.0
-rw-r--r--   1 root                 root                 4.4K Oct  6  2022 hdparm.conf
-rw-r--r--   1 root                 root                   92 Apr 22  2024 host.conf
-rw-r--r--   1 root                 root                   16 Jul  5 15:57 hostname
-rw-r--r--   1 root                 root                  230 Jul  5 15:57 hosts
-rw-r--r--   1 root                 root                  411 Feb 10 01:28 hosts.allow
-rw-r--r--   1 root                 root                  711 Feb 10 01:28 hosts.deny
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:03 hp
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:28 ifplugd
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 init
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 init.d
drwxr-xr-x   5 root                 root                 4.0K Feb 10 01:29 initramfs-tools
-rw-r--r--   1 root                 root                 1.9K Mar 31  2024 inputrc
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 insserv.conf.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 ipp-usb
drwxr-xr-x   4 root                 root                 4.0K Jul  5 17:09 iproute2
-rw-r--r--   1 root                 root                   26 Feb  6 08:23 issue
-rw-r--r--   1 root                 root                   19 Feb  6 08:23 issue.net
drwxr-xr-x   8 root                 root                 4.0K Jul  5 17:06 kernel
-rw-r--r--   1 root                 root                 1.3K Mar 31  2024 kerneloops.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 krb5.conf.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 ldap
-rw-r--r--   1 root                 root                  64K Jul  5 17:28 ld.so.cache
-rw-r--r--   1 root                 root                   34 Aug  2  2022 ld.so.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:06 ld.so.conf.d
-rw-r--r--   1 root                 root                  267 Apr 22  2024 legal
-rw-r--r--   1 root                 root                   27 Apr  8  2024 libao.conf
-rw-r--r--   1 root                 root                  191 Mar 31  2024 libaudit.conf
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:28 libblockdev
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 libibverbs.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 libnl-3
drwxr-xr-x   2 root                 root                 4.0K Apr  8  2024 libpaper.d
-rw-r--r--   1 root                 root                 3.0K Mar 30  2024 locale.alias
-rw-r--r--   1 root                 root                  230 Jul  5 18:50 locale.conf
-rw-r--r--   1 root                 root                 9.4K Jul  5 16:36 locale.gen
lrwxrwxrwx   1 root                 root                   33 Jul  5 16:36 localtime -> /usr/share/zoneinfo/Europe/Berlin
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:27 logcheck
-rw-r--r--   1 root                 root                  13K Feb 22  2024 login.defs
-rw-r--r--   1 root                 root                  586 Apr  8  2024 logrotate.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 logrotate.d
-rw-r--r--   1 root                 root                  104 Feb  6 08:22 lsb-release
-r--r--r--   1 root                 root                   33 Jul  5 15:53 machine-id
-rw-r--r--   1 root                 root                  111 Mar 31  2024 magic
-rw-r--r--   1 root                 root                  111 Mar 31  2024 magic.mime
-rw-r--r--   1 root                 root                 5.2K Apr  8  2024 manpath.config
-rw-r--r--   1 root                 root                  74K Jul 12  2023 mime.types
-rw-r--r--   1 root                 root                  744 Apr  8  2024 mke2fs.conf
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:28 ModemManager
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:06 modprobe.d
-rw-r--r--   1 root                 root                  212 Feb 10 01:20 modules
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 modules-load.d
lrwxrwxrwx   1 root                 root                   19 Feb 10 01:19 mtab -> ../proc/self/mounts
-rw-r--r--   1 root                 root                  12K May 23  2023 nanorc
-rw-r--r--   1 root                 root                  767 Mar 31  2024 netconfig
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:36 netplan
drwxr-xr-x   6 root                 root                 4.0K Feb 10 01:28 network
drwxr-xr-x   8 root                 root                 4.0K Feb 10 01:20 networkd-dispatcher
drwxr-xr-x   8 root                 root                 4.0K Jul  5 17:10 NetworkManager
-rw-r--r--   1 root                 root                   91 Apr 22  2024 networks
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:20 newt
-rwxr-xr-x   1 root                 root                  243 Oct 19  2023 nftables.conf
-rw-r--r--   1 root                 root                  594 Feb 10 01:29 nsswitch.conf
drwxr-xr-x   4 root                 root                 4.0K Jul  5 16:02 openvpn
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:19 opt
lrwxrwxrwx   1 root                 root                   21 Feb  6 08:23 os-release -> ../usr/lib/os-release
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:03 PackageKit
-rw-r--r--   1 root                 root                  552 Oct 13  2022 pam.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 pam.d
-rw-r--r--   1 root                 root                    3 Feb 10 01:28 papersize
-rw-r--r--   1 root                 root                 2.9K Jul  5 19:02 passwd
-rw-r--r--   1 root                 root                 2.9K Jul  5 19:02 passwd-
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 pcmcia
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:27 perl
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:28 pki
drwxr-xr-x   2 root                 root                 4.0K Feb 25  2025 plymouth
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:28 pm
-rw-r--r--   1 root                 root                 7.5K Feb 10 01:29 pnm2ppa.conf
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:28 polkit-1
drwxr-xr-x   8 root                 dip                  4.0K Feb 10 01:29 ppp
lrwxrwxrwx   1 root                 root                   18 Jul  5 16:03 printcap -> /run/cups/printcap
-rw-r--r--   1 root                 root                  582 Apr 22  2024 profile
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 profile.d
-rw-r--r--   1 root                 root                 3.1K Oct 18  2022 protocols
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:29 pulse
-rw-------   1 root                 root                    0 Feb 10 01:19 .pwd.lock
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:20 python3
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 python3.12
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc0.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc1.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc2.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc3.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc4.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc5.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:57 rc6.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 rcS.d
lrwxrwxrwx   1 root                 root                   39 Feb 10 01:20 resolv.conf -> ../run/systemd/resolve/stub-resolv.conf
-rw-r--r--   1 root                 root                  862 Feb 10 01:19 .resolv.conf.systemd-resolved.bak
lrwxrwxrwx   1 root                 root                   13 Jun 19 16:00 rmt -> /usr/sbin/rmt
-rw-r--r--   1 root                 root                  911 Oct 18  2022 rpc
-rw-r--r--   1 root                 root                 1.2K Mar 22  2024 rsyslog.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:10 rsyslog.d
-rw-r--r--   1 root                 root                 5.7K Jan  6  2024 rygel.conf
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:31 sane.d
drwxr-xr-x   4 root                 root                 4.0K Jul  5 16:02 security
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:19 selinux
-rw-r--r--   1 root                 root                  11K Mar 31  2024 sensors3.conf
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 sensors.d
-rw-r--r--   1 root                 root                  13K Mar 27  2021 services
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:31 sgml
-rw-r-----   1 root                 shadow               1.5K Jul  5 19:02 shadow
-rw-r-----   1 root                 shadow               1.4K Jul  5 19:02 shadow-
-rw-r--r--   1 root                 root                  118 Feb 10 01:19 shells
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:19 skel
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:28 snmp
drwxr-xr-x   4 root                 root                 4.0K Feb 10 01:29 speech-dispatcher
drwxr-xr-x   3 root                 root                 4.0K Jul  5 16:36 ssh
drwxr-xr-x   4 root                 root                 4.0K Jul  5 16:02 ssl
drwx--x--x   3 root                 root                 4.0K Feb 10 01:28 sssd
-rw-r--r--   1 root                 root                   37 Jul  5 19:02 subgid
-rw-r--r--   1 root                 root                   18 Jul  5 19:01 subgid-
-rw-r--r--   1 root                 root                   37 Jul  5 19:02 subuid
-rw-r--r--   1 root                 root                   18 Jul  5 19:01 subuid-
-rw-r--r--   1 root                 root                 4.3K Apr  8  2024 sudo.conf
-r--r-----   1 root                 root                 1.8K Jan 29  2024 sudoers
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 sudoers.d
-rw-r--r--   1 root                 root                 9.6K Apr  8  2024 sudo_logsrvd.conf
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:20 supercat
-rw-r--r--   1 root                 root                 2.2K Mar 24  2024 sysctl.conf
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 sysctl.d
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 sysstat
drwxr-xr-x   6 root                 root                 4.0K Jul  5 16:02 systemd
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 terminfo
drwxr-xr-x   2 root                 root                 4.0K Jul  5 15:56 thermald
-rw-r--r--   1 root                 root                   14 Jul  5 16:36 timezone
drwxr-xr-x   2 root                 root                 4.0K Apr 19  2024 tmpfiles.d
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:09 ubuntu-advantage
-rw-r--r--   1 root                 root                 1.3K Jan 27  2023 ucf.conf
drwxr-xr-x   4 root                 root                 4.0K Jul  5 16:02 udev
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 udisks2
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:29 ufw
-rw-r--r--   1 root                 root                  208 Feb 10 01:19 .updated
drwxr-xr-x   3 root                 root                 4.0K Feb 10 01:30 update-manager
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:09 update-motd.d
drwxr-xr-x   2 root                 root                 4.0K Apr  2  2025 update-notifier
drwxr-xr-x   2 root                 root                 4.0K Feb 10 01:29 UPower
-rw-r--r--   1 root                 root                 1.5K Apr  8  2024 usb_modeswitch.conf
drwxr-xr-x   2 root                 root                 4.0K Dec 16  2023 usb_modeswitch.d
lrwxrwxrwx   1 root                 root                   16 Feb 10 01:19 vconsole.conf -> default/keyboard
-rw-r--r--   1 root                 root                   51 Mar  7  2022 vdpau_wrapper.cfg
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:02 vim
drwxr-xr-x   4 root                 root                 4.0K Jul  5 15:57 vmware-tools
lrwxrwxrwx   1 root                 root                   23 Feb 26  2024 vtrgb -> /etc/alternatives/vtrgb
drwxr-xr-x   5 root                 root                 4.0K Feb 10 01:27 vulkan
-rw-r--r--   1 root                 root                 4.9K Jun 19  2024 wgetrc
-rw-r--r--   1 root                 root                   30 Jul  5 18:37 whoopsie
drwxr-xr-x   2 root                 root                 4.0K Jul  5 17:09 wpa_supplicant
drwxr-xr-x  12 root                 root                 4.0K Feb 10 01:31 X11
-rw-r--r--   1 root                 root                  681 Apr  8  2024 xattr.conf
drwxr-xr-x   6 root                 root                 4.0K Feb 10 01:28 xdg
drwxr-xr-x   2 root                 root                 4.0K Jul  5 16:03 xml
-rw-r--r--   1 root                 root                  460 Jan 20  2023 zsh_command_not_found

# Перейди у каталог /home і покажи список користувачів;
test@test-VirtualBox:/etc$ cd /home
test@test-VirtualBox:/home$ pwd
/home
test@test-VirtualBox:/home$ ls -lah
total 16K
drwxr-xr-x  4 root  root  4.0K Jul  5 19:00 .
drwxr-xr-x 23 root  root  4.0K Jul  5 15:56 ..
drwxr-x--- 16 test  test  4.0K Jul  6 22:24 test
drwxr-x--- 14 test1 test1 4.0K Jul  5 19:04 test1

# Завдання 2. Файли, каталоги та посилання (2 бали)

# Створи новий каталог у домашньому каталозі
test@test-VirtualBox:/home$ cd ~
test@test-VirtualBox:~$ mkdir lab2
test@test-VirtualBox:~$ cd lab2
test@test-VirtualBox:~/lab2$ 

# Створи всередині файл
test@test-VirtualBox:~/lab2$ touch file.txt
test@test-VirtualBox:~/lab2$ ls -lah
total 8.0K
drwxrwxr-x  2 test test 4.0K Jul  6 23:05 .
drwxr-x--- 17 test test 4.0K Jul  6 23:03 ..
-rw-rw-r--  1 test test    0 Jul  6 23:05 file.txt

# Скопіюй файл у нове ім’я
test@test-VirtualBox:~/lab2$ cp file.txt file_copy.txt

# Перейменуй копію
test@test-VirtualBox:~/lab2$ mv file_copy.txt renamed_file.txt

# Створи жорстке посилання
test@test-VirtualBox:~/lab2$ ln file.txt hard_link.txt

# Створи символічне посилання
test@test-VirtualBox:~/lab2$ ln -s file.txt symbolic_link.txt

test@test-VirtualBox:~/lab2$ ls -lai
total 8
2491055 drwxrwxr-x  2 test test 4096 Jul  6 23:08 .
2490370 drwxr-x--- 17 test test 4096 Jul  6 23:03 ..
2490706 -rw-rw-r--  2 test test    0 Jul  6 23:05 file.txt
2490706 -rw-rw-r--  2 test test    0 Jul  6 23:05 hard_link.txt
2490636 -rw-rw-r--  1 test test    0 Jul  6 23:06 renamed_file.txt
2490814 lrwxrwxrwx  1 test test    8 Jul  6 23:08 symbolic_link.txt -> file.txt

# Знайди файл по імені
test@test-VirtualBox:~/lab2$ find ~/lab2 -type f -name file.txt
/home/test/lab2/file.txt

# Завдання 3. Права доступу (1 бал)

# Переглянь права файлу, який ти створив
test@test-VirtualBox:~/lab2$ ls -l file.txt
-rw-rw-r-- 2 test test 0 Jul  6 23:05 file.txt

# Надай файлу права тільки на читання
test@test-VirtualBox:~/lab2$ chmod 444 file.txt
test@test-VirtualBox:~/lab2$ ls -l file.txt
-r--r--r-- 2 test test 0 Jul  6 23:05 file.txt

# Надай власнику право на запис
test@test-VirtualBox:~/lab2$ chmod u+w file.txt
test@test-VirtualBox:~/lab2$ ls -l file.txt
-rw-r--r-- 2 test test 0 Jul  6 23:05 file.txt

# Переглянь значення umask
test@test-VirtualBox:~/lab2$ umask
0002

# Встанови нове значення, наприклад 022
test@test-VirtualBox:~/lab2$ umask 022
test@test-VirtualBox:~/lab2$ umask
0022

# Завдання 4. Користувачі (1 бал)

# Створи нового користувача
test@test-VirtualBox:~/lab2$ sudo adduser trainee
[sudo] password for test: 
info: Adding user `trainee' ...
info: Selecting UID/GID from range 1000 to 59999 ...
info: Adding new group `trainee' (1002) ...
info: Adding new user `trainee' (1002) with group `trainee (1002)' ...
info: Creating home directory `/home/trainee' ...
info: Copying files from `/etc/skel' ...
New password: 
Retype new password: 
passwd: password updated successfully
Changing the user information for trainee
Enter the new value, or press ENTER for the default
	Full Name []: trainee
	Room Number []: 
	Work Phone []: 
	Home Phone []: 
	Other []: 
Is the information correct? [Y/n] y
info: Adding new user `trainee' to supplemental / extra groups `users' ...
info: Adding user `trainee' to group `users' ...

# Додай його до sudo-групи
test@test-VirtualBox:~/lab2$ sudo usermod -aG sudo trainee

# Перевір, що користувач існує
test@test-VirtualBox:~/lab2$ cat /etc/passwd | grep trainee
trainee:x:1002:1002:trainee,,,:/home/trainee:/bin/bash

# End of SKhoroshko_homework_2.md
