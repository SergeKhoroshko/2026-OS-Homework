# Завдання 1. Огляд активних процесів (1 бал)

# Виведи список усіх процесів у системі за допомогою ps.
test@test-VirtualBox:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.1  23300 14840 ?        Ss   Jul06   0:02 /sbin/init splash
root           2  0.0  0.0      0     0 ?        S    Jul06   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        S    Jul06   0:00 [pool_workqueue_release]
root           4  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-rcu_gp]
root           5  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-sync_wq]
root           6  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-kvfree_rcu_reclaim]
root           7  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-slub_flushwq]
root           8  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-netns]
root          11  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/0:0H-events_highpri]
root          13  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-mm_percpu_wq]
root          14  0.0  0.0      0     0 ?        S    Jul06   0:00 [ksoftirqd/0]
root          15  0.0  0.0      0     0 ?        I    Jul06   0:02 [rcu_preempt]
root          16  0.0  0.0      0     0 ?        S    Jul06   0:00 [rcu_exp_par_gp_kthread_worker/0]
root          17  0.0  0.0      0     0 ?        S    Jul06   0:00 [rcu_exp_gp_kthread_worker]
root          18  0.0  0.0      0     0 ?        S    Jul06   0:00 [migration/0]
root          19  0.0  0.0      0     0 ?        S    Jul06   0:00 [idle_inject/0]
root          20  0.0  0.0      0     0 ?        S    Jul06   0:00 [cpuhp/0]
root          21  0.0  0.0      0     0 ?        S    Jul06   0:00 [cpuhp/1]
root          22  0.0  0.0      0     0 ?        S    Jul06   0:00 [idle_inject/1]
root          23  0.0  0.0      0     0 ?        S    Jul06   0:00 [migration/1]
root          24  0.0  0.0      0     0 ?        S    Jul06   0:00 [ksoftirqd/1]
root          26  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/1:0H-events_highpri]
root          27  0.0  0.0      0     0 ?        S    Jul06   0:00 [cpuhp/2]
root          28  0.0  0.0      0     0 ?        S    Jul06   0:00 [idle_inject/2]
root          29  0.0  0.0      0     0 ?        S    Jul06   0:00 [migration/2]
root          30  0.0  0.0      0     0 ?        S    Jul06   0:00 [ksoftirqd/2]
root          32  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/2:0H-events_highpri]
root          33  0.0  0.0      0     0 ?        S    Jul06   0:00 [cpuhp/3]
root          34  0.0  0.0      0     0 ?        S    Jul06   0:00 [idle_inject/3]
root          35  0.0  0.0      0     0 ?        S    Jul06   0:00 [migration/3]
root          36  0.0  0.0      0     0 ?        S    Jul06   0:00 [ksoftirqd/3]
root          38  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/3:0H-events_highpri]
root          39  0.0  0.0      0     0 ?        S    Jul06   0:00 [kdevtmpfs]
root          40  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-inet_frag_wq]
root          41  0.0  0.0      0     0 ?        I    Jul06   0:00 [rcu_tasks_kthread]
root          42  0.0  0.0      0     0 ?        I    Jul06   0:00 [rcu_tasks_rude_kthread]
root          43  0.0  0.0      0     0 ?        I    Jul06   0:00 [rcu_tasks_trace_kthread]
root          44  0.0  0.0      0     0 ?        S    Jul06   0:00 [kauditd]
root          45  0.0  0.0      0     0 ?        S    Jul06   0:00 [khungtaskd]
root          46  0.0  0.0      0     0 ?        S    Jul06   0:00 [oom_reaper]
root          48  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-writeback]
root          50  0.0  0.0      0     0 ?        S    Jul06   0:00 [kcompactd0]
root          51  0.0  0.0      0     0 ?        SN   Jul06   0:00 [ksmd]
root          52  0.0  0.0      0     0 ?        SN   Jul06   0:00 [khugepaged]
root          53  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-kblockd]
root          54  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-blkcg_punt_bio]
root          55  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-kintegrityd]
root          56  0.0  0.0      0     0 ?        S    Jul06   0:00 [irq/9-acpi]
root          60  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-tpm_dev_wq]
root          61  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-ata_sff]
root          62  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-md]
root          63  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-md_bitmap]
root          64  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-edac-poller]
root          65  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-devfreq_wq]
root          66  0.0  0.0      0     0 ?        S    Jul06   0:00 [watchdogd]
root          67  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-quota_events_unbound]
root          68  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/0:1H-kblockd]
root          69  0.0  0.0      0     0 ?        S    Jul06   0:00 [kswapd0]
root          70  0.0  0.0      0     0 ?        S    Jul06   0:00 [ecryptfs-kthread]
root          71  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-kthrotld]
root          72  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-acpi_thermal_pm]
root          73  0.0  0.0      0     0 ?        S    Jul06   0:00 [scsi_eh_0]
root          74  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-scsi_tmf_0]
root          75  0.0  0.0      0     0 ?        S    Jul06   0:00 [scsi_eh_1]
root          76  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-scsi_tmf_1]
root          80  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-mld]
root          81  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-ipv6_addrconf]
root          82  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-kstrp]
root          84  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/u17:0-ttm]
root          95  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-charger_manager]
root          96  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/1:1H-kblockd]
root         123  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/3:1H-kblockd]
root         149  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/2:1H-kblockd]
root         151  0.0  0.0      0     0 ?        S    Jul06   0:00 [scsi_eh_2]
root         152  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-scsi_tmf_2]
root         204  0.0  0.0      0     0 ?        S    Jul06   0:00 [jbd2/sda2-8]
root         205  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-ext4-rsv-conversion]
root         254  0.0  0.2  67172 20340 ?        S<s  Jul06   0:00 /usr/lib/systemd/systemd-journald
root         310  0.0  0.0      0     0 ?        S    Jul06   0:00 [irq/18-vmwgfx]
root         311  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-ttm]
root         329  0.0  0.1  30728  8860 ?        Ss   Jul06   0:00 /usr/lib/systemd/systemd-udevd
systemd+     372  0.0  0.0  17572  7792 ?        Ss   Jul06   0:01 /usr/lib/systemd/systemd-oomd
systemd+     376  0.0  0.1  21476 13612 ?        Ss   Jul06   0:00 /usr/lib/systemd/systemd-resolved
root         414  0.0  0.0      0     0 ?        S    Jul06   0:00 [psimon]
root         652  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/R-iprt-VBoxWQueue]
systemd+     845  0.0  0.0  91060  8000 ?        Ssl  Jul06   0:00 /usr/lib/systemd/systemd-timesyncd
avahi        887  0.0  0.0   8680  4696 ?        Ss   Jul06   0:00 avahi-daemon: running [test-VirtualBox.local]
message+     888  0.0  0.0  12048  7140 ?        Ss   Jul06   0:01 @dbus-daemon --system --address=systemd: --nofork
gnome-r+     892  0.0  0.2 512824 16772 ?        Ssl  Jul06   0:00 /usr/libexec/gnome-remote-desktop-daemon --system
polkitd      911  0.0  0.1 384384 11008 ?        Ssl  Jul06   0:00 /usr/lib/polkit-1/polkitd --no-debug
root         920  0.0  0.0 322208  7916 ?        Ssl  Jul06   0:00 /usr/libexec/power-profiles-daemon
root         925  0.0  0.5 2071668 44960 ?       Ssl  Jul06   0:03 /usr/lib/snapd/snapd
root         931  0.0  0.1 321972  8232 ?        Ssl  Jul06   0:00 /usr/libexec/accounts-daemon
root         939  0.0  0.0  18100  3028 ?        Ss   Jul06   0:00 /usr/sbin/cron -f -P
root         944  0.0  0.0 318512  7440 ?        Ssl  Jul06   0:00 /usr/libexec/switcheroo-control
root         957  0.0  0.1  18148  9152 ?        Ss   Jul06   0:00 /usr/lib/systemd/systemd-logind
root         959  0.0  0.1 469476 14868 ?        Ssl  Jul06   0:00 /usr/libexec/udisks2/udisksd
syslog      1003  0.0  0.0 222572  6304 ?        Ssl  Jul06   0:00 /usr/sbin/rsyslogd -n -iNONE
avahi       1018  0.0  0.0   8488  1548 ?        S    Jul06   0:00 avahi-daemon: chroot helper
root        1019  0.0  0.2 345076 19852 ?        Ssl  Jul06   0:00 /usr/sbin/NetworkManager --no-daemon
root        1031  0.0  0.0  17392  6716 ?        Ss   Jul06   0:00 /usr/sbin/wpa_supplicant -u -s -O DIR=/run/wpa_su
root        1140  0.0  0.1 392108 13176 ?        Ssl  Jul06   0:00 /usr/sbin/ModemManager
root        1330  0.0  0.0 364324  2904 ?        Sl   Jul06   0:04 /usr/bin/VBoxDRMClient
root        1333  0.0  0.0 304464  3872 ?        Sl   Jul06   0:01 /usr/sbin/VBoxService --pidfile /var/run/vboxadd-
root        1423  0.0  0.2 120936 23484 ?        Ssl  Jul06   0:00 /usr/bin/python3 /usr/share/unattended-upgrades/u
root        1435  0.0  0.1 323500  9692 ?        Ssl  Jul06   0:00 /usr/sbin/gdm3
root        1442  0.0  0.1 250940 10448 ?        Sl   Jul06   0:00 gdm-session-worker [pam/gdm-autologin]
test        1453  0.0  0.1  21172 12688 ?        Ss   Jul06   0:00 /usr/lib/systemd/systemd --user
kernoops    1454  0.0  0.0  12752  2440 ?        Ss   Jul06   0:00 /usr/sbin/kerneloops --test
test        1457  0.0  0.0  21476  3648 ?        S    Jul06   0:00 (sd-pam)
kernoops    1458  0.0  0.0  12752  2404 ?        Ss   Jul06   0:00 /usr/sbin/kerneloops
test        1471  0.0  0.1 125268 16152 ?        S<sl Jul06   0:00 /usr/bin/pipewire
test        1472  0.0  0.0 106412  6288 ?        Ssl  Jul06   0:00 /usr/bin/pipewire -c filter-chain.conf
test        1475  0.0  0.2 415484 19340 ?        S<sl Jul06   0:00 /usr/bin/wireplumber
test        1476  0.0  0.1 125572 14572 ?        S<sl Jul06   0:00 /usr/bin/pipewire-pulse
test        1477  0.0  0.1 325168 10232 ?        Ssl  Jul06   0:00 /usr/bin/gnome-keyring-daemon --foreground --comp
test        1487  0.0  0.0  10880  6768 ?        Ss   Jul06   0:00 /usr/bin/dbus-daemon --session --address=systemd:
test        1502  0.0  0.0 618968  7848 ?        Ssl  Jul06   0:00 /usr/libexec/xdg-document-portal
rtkit       1503  0.0  0.0  22948  3552 ?        SNsl Jul06   0:00 /usr/libexec/rtkit-daemon
test        1510  0.0  0.0 244392  6380 tty2     Ssl+ Jul06   0:00 /usr/libexec/gdm-wayland-session env GNOME_SHELL_
test        1517  0.0  0.0 318112  6452 ?        Ssl  Jul06   0:00 /usr/libexec/xdg-permission-store
test        1524  0.0  0.2 306956 17016 tty2     Sl+  Jul06   0:00 /usr/libexec/gnome-session-binary --session=ubunt
root        1543  0.0  0.0   2712  2104 ?        Ss   Jul06   0:00 fusermount3 -o rw,nosuid,nodev,fsname=portal,auto
test        1600  0.0  0.0 162660  7068 ?        Ssl  Jul06   0:00 /usr/libexec/gcr-ssh-agent --base-dir /run/user/1
test        1601  0.0  0.0 100224  5800 ?        Ssl  Jul06   0:00 /usr/libexec/gnome-session-ctl --monitor
test        1617  0.0  0.1 322996  8264 ?        Ssl  Jul06   0:00 /usr/libexec/gvfsd
test        1623  0.0  0.0 468400  7464 ?        Sl   Jul06   0:00 /usr/libexec/gvfsd-fuse /run/user/1000/gvfs -f
test        1626  0.0  0.2 603012 18948 ?        Ssl  Jul06   0:00 /usr/libexec/gnome-session-binary --systemd-servi
test        1659  3.6  7.9 5289832 645004 ?      Ssl  Jul06   5:18 /usr/bin/gnome-shell
test        1661  0.0  0.0 382948  8024 ?        Sl   Jul06   0:00 /usr/libexec/at-spi-bus-launcher --launch-immedia
test        1677  0.0  0.0   9624  5456 ?        S    Jul06   0:00 /usr/bin/dbus-daemon --config-file=/usr/share/def
test        1760  0.0  0.0 236076  7876 ?        Sl   Jul06   0:00 /usr/libexec/at-spi2-registryd --use-gnome-sessio
colord      1762  0.0  0.1 328708 14828 ?        Ssl  Jul06   0:00 /usr/libexec/colord
test        1792  0.0  0.2 655852 22448 ?        Sl   Jul06   0:00 /usr/libexec/gnome-shell-calendar-server
test        1799  0.0  0.5 1287924 43800 ?       Ssl  Jul06   0:00 /usr/libexec/evolution-source-registry
test        1811  0.0  0.3 2532044 27276 ?       Sl   Jul06   0:00 /usr/bin/gjs -m /usr/share/gnome-shell/org.gnome.
root        1816  0.0  0.1 325348  9360 ?        Ssl  Jul06   0:00 /usr/libexec/upowerd
test        1817  0.0  0.8 245204 68928 ?        S    Jul06   0:01 /usr/bin/Xwayland :0 -rootless -noreset -accessx 
test        1829  0.0  0.1 397360 12560 ?        Ssl  Jul06   0:02 /usr/bin/ibus-daemon --panel disable
test        1831  0.0  0.0 392256  6992 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-a11y-settings
test        1832  0.0  0.2 421832 21096 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-color
test        1837  0.0  0.1 440404 12648 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-datetime
test        1838  0.0  0.1 394008  8292 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-housekeeping
test        1840  0.0  0.2 494352 20728 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-keyboard
test        1841  0.0  0.3 529132 26208 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-media-keys
test        1842  0.0  0.3 605996 25064 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-power
test        1843  0.0  0.1 332440 11984 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-print-notifications
test        1844  0.0  0.0 539820  7164 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-rfkill
test        1846  0.0  0.0 318240  6612 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-screensaver-proxy
test        1847  0.0  0.1 551932 11992 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-sharing
test        1848  0.0  0.1 394556  8488 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-smartcard
test        1849  0.0  0.1 402244 10236 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-sound
test        1850  0.0  0.2 495324 21444 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-wacom
test        1890  0.0  0.0 305632  7580 ?        Sl   Jul06   0:00 /usr/libexec/gsd-disk-utility-notify
test        1931  0.0  0.7 912748 64684 ?        Sl   Jul06   0:00 /usr/libexec/evolution-data-server/evolution-alar
test        2006  0.0  0.0 245336  7372 ?        Sl   Jul06   0:00 /usr/libexec/ibus-memconf
test        2008  0.0  0.3 430268 30636 ?        Sl   Jul06   0:02 /usr/libexec/ibus-extension-gtk3
test        2011  0.0  0.1 471764 11936 ?        Ssl  Jul06   0:00 /usr/libexec/gvfs-udisks2-volume-monitor
test        2013  0.0  0.0 319104  7540 ?        Sl   Jul06   0:00 /usr/libexec/ibus-portal
test        2043  0.0  0.3 555408 24844 ?        Sl   Jul06   0:00 /usr/libexec/goa-daemon
test        2061  0.0  0.1 398060  8316 ?        Ssl  Jul06   0:00 /usr/libexec/gvfs-afc-volume-monitor
test        2069  0.0  0.1 397848  9720 ?        Sl   Jul06   0:00 /usr/libexec/goa-identity-service
test        2081  0.0  0.3 899432 25072 ?        Ssl  Jul06   0:00 /usr/libexec/evolution-calendar-factory
test        2083  0.0  0.0 319440  7184 ?        Ssl  Jul06   0:00 /usr/libexec/gvfs-gphoto2-volume-monitor
test        2091  0.0  0.0 318452  6748 ?        Ssl  Jul06   0:00 /usr/libexec/gvfs-goa-volume-monitor
test        2096  0.0  0.0 318472  6836 ?        Ssl  Jul06   0:00 /usr/libexec/gvfs-mtp-volume-monitor
test        2109  0.0  0.3 760292 30896 ?        Ssl  Jul06   0:00 /usr/libexec/evolution-addressbook-factory
test        2135  0.0  0.0 245460  7852 ?        Sl   Jul06   0:00 /usr/libexec/ibus-engine-simple
test        2158  0.0  0.0 230248  6124 ?        Ssl  Jul06   0:00 /usr/libexec/dconf-service
test        2167  0.0  0.1 424924 15420 ?        Sl   Jul06   0:00 /usr/libexec/gsd-printer
test        2183  0.0  0.0 245024  6872 ?        Ssl  Jul06   0:00 /usr/libexec/gvfsd-metadata
test        2184  0.0  0.1 618164  9512 ?        Sl   Jul06   0:00 /usr/libexec/gvfsd-trash --spawner :1.20 /org/gtk
test        2213  0.0  0.1 710324 15224 ?        Ssl  Jul06   0:00 /usr/libexec/xdg-desktop-portal
test        2228  0.0  0.9 3102492 75440 ?       Sl   Jul06   0:02 gjs /usr/share/gnome-shell/extensions/ding@raster
test        2241  0.0  0.3 744416 30060 ?        SNsl Jul06   0:00 /usr/libexec/tracker-miner-fs-3
test        2243  0.0  2.8 2115320 231832 ?      Ssl  Jul06   0:01 /usr/libexec/xdg-desktop-portal-gnome
test        2253  0.0  1.0 650996 85196 ?        Ssl  Jul06   0:00 /usr/libexec/gsd-xsettings
test        2257  0.0  0.1  39140 12188 ?        Ss   Jul06   0:00 /snap/snapd-desktop-integration/343/usr/bin/snapd
test        2274  0.0  0.3 2597580 27340 ?       Sl   Jul06   0:00 /usr/bin/gjs -m /usr/share/gnome-shell/org.gnome.
test        2374  0.0  0.3 275996 25324 ?        Sl   Jul06   0:00 /usr/libexec/ibus-x11
test        2385  0.0  1.2 1423292 104344 ?      Sl   Jul06   0:01 /usr/libexec/mutter-x11-frames
test        2416  0.0  0.3 426524 26784 ?        Ssl  Jul06   0:00 /usr/libexec/xdg-desktop-portal-gtk
test        2444  0.0  0.0  28168  1596 ?        S    Jul06   0:00 /usr/bin/VBoxClient --clipboard
test        2447  0.0  0.0 226976  4868 ?        Sl   Jul06   0:00 /usr/bin/VBoxClient --clipboard
test        2485  0.0  0.0  28168  1596 ?        S    Jul06   0:00 /usr/bin/VBoxClient --vmsvga-session
test        2487  0.0  0.0 160272  2460 ?        Sl   Jul06   0:00 /usr/bin/VBoxClient --vmsvga-session
test        2502  0.0  0.3 429464 31108 ?        Sl   Jul06   0:00 /snap/snapd-desktop-integration/343/usr/bin/snapd
test        2596  2.0  5.6 2615860 462220 ?      Sl   Jul06   2:59 /usr/bin/gnome-text-editor
test        2660  0.0  0.1 471048  9208 ?        Sl   Jul06   0:00 /usr/libexec/gvfsd-network --spawner :1.20 /org/g
test        2670  0.0  0.1 399272  9336 ?        Sl   Jul06   0:00 /usr/libexec/gvfsd-dnssd --spawner :1.20 /org/gtk
test        2691  0.0  0.3 500460 27280 ?        Sl   Jul06   0:00 /usr/bin/update-notifier
test        2778  0.0  0.1 396952  8756 ?        Sl   Jul06   0:00 /usr/libexec/gvfsd-recent --spawner :1.20 /org/gt
root        3043  0.0  0.0      0     0 ?        S    Jul06   0:00 [psimon]
root        3223  0.0  0.0      0     0 ?        I<   Jul06   0:00 [kworker/u17:1-ttm]
test        3664  0.0  3.8 2504628 311068 ?      Sl   Jul06   0:02 /usr/bin/nautilus --gapplication-service
root        3798  0.0  0.1  47476 13088 ?        Ss   00:00   0:00 /usr/sbin/cupsd -l
cups-br+    3801  0.0  0.2 268504 20588 ?        Ssl  00:00   0:00 /usr/sbin/cups-browsed
root        4888  0.0  0.0      0     0 ?        I    00:08   0:00 [kworker/u16:5-kvfree_rcu_reclaim]
root        5384  0.0  0.0      0     0 ?        I    00:12   0:00 [kworker/3:0-cgroup_release]
root        5932  0.0  0.0      0     0 ?        I    00:16   0:00 [kworker/u16:0-flush-8:0]
root        6266  0.0  0.0      0     0 ?        I    00:19   0:00 [kworker/0:1-cgroup_free]
root        6870  0.0  0.0      0     0 ?        I    00:23   0:00 [kworker/u16:1-events_power_efficient]
root        7696  0.0  0.0      0     0 ?        I    00:30   0:00 [kworker/2:1-cgroup_free]
root        7805  0.0  0.0      0     0 ?        I    00:30   0:00 [kworker/u16:2-events_unbound]
root        8025  0.0  0.0      0     0 ?        I    00:32   0:00 [kworker/0:2-cgroup_release]
root        8245  0.0  0.0      0     0 ?        I    00:34   0:00 [kworker/1:2-events]
root        8464  0.0  0.0      0     0 ?        I    00:35   0:00 [kworker/2:2-cgroup_release]
root        8521  0.0  0.0      0     0 ?        I    00:36   0:00 [kworker/3:1-events]
root        8745  0.0  0.0      0     0 ?        I    00:38   0:00 [kworker/0:0-events]
root        8965  0.0  0.0      0     0 ?        I    00:39   0:00 [kworker/1:1-cgroup_free]
root        9240  0.0  0.0      0     0 ?        I    00:41   0:00 [kworker/3:2-cgroup_free]
root        9297  0.0  0.0      0     0 ?        I    00:42   0:00 [kworker/0:3-events]
root        9350  0.0  0.0      0     0 ?        I    00:42   0:00 [kworker/2:0-ata_sff]
test        9857  5.4  0.7 708912 59184 ?        Ssl  00:46   0:00 /usr/libexec/gnome-terminal-server
test        9864  0.0  0.0  19700  5360 pts/0    Ss   00:46   0:00 bash
root        9876  0.0  0.0      0     0 ?        I    00:46   0:00 [kworker/1:0-mm_percpu_wq]
test        9877  0.7  0.0 146128  7784 ?        Ssl  00:46   0:00 /snap/firmware-updater/210/bin/firmware-notifier
test        9932  0.0  0.0  22440  4824 pts/0    R+   00:46   0:00 ps aux

# Запусти інтерактивний монітор top (або htop, якщо він встановлений) та знайди процес, який споживає найбільше пам'яті (RAM).
test@test-VirtualBox:~$ top
top - 00:50:57 up  2:29,  1 user,  load average: 0.09, 0.09, 0.03
Tasks: 218 total,   1 running, 217 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.2 us,  0.1 sy,  0.0 ni, 99.8 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st 
MiB Mem :   7940.1 total,   4436.2 free,   2088.6 used,   1707.2 buff/cache     
MiB Swap:   4096.0 total,   4096.0 free,      0.0 used.   5851.5 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                      
   1659 test      20   0 5292152 646960 170300 S   0.3   8.0   5:53.72 gnome-shell                                  
      1 root      20   0   23300  14840   9880 S   0.0   0.2   0:02.25 systemd                                      
      2 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kthreadd                                     
      3 root      20   0       0      0      0 S   0.0   0.0   0:00.00 pool_workqueue_release                       
      4 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-rcu_gp                             
      5 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-sync_wq                            
      6 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-kvfree_rcu_reclaim                 
      7 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-slub_flushwq                       
      8 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-netns                              
     11 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/0:0H-events_highpri                  
     13 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-mm_percpu_wq                       
     14 root      20   0       0      0      0 S   0.0   0.0   0:00.05 ksoftirqd/0                                  
     15 root      20   0       0      0      0 I   0.0   0.0   0:02.33 rcu_preempt                                  
     16 root      20   0       0      0      0 S   0.0   0.0   0:00.00 rcu_exp_par_gp_kthread_worker/0              
     17 root      20   0       0      0      0 S   0.0   0.0   0:00.03 rcu_exp_gp_kthread_worker                    
     18 root      rt   0       0      0      0 S   0.0   0.0   0:00.05 migration/0                                  
     19 root     -51   0       0      0      0 S   0.0   0.0   0:00.00 idle_inject/0                                
     20 root      20   0       0      0      0 S   0.0   0.0   0:00.00 cpuhp/0                                      
     21 root      20   0       0      0      0 S   0.0   0.0   0:00.00 cpuhp/1                                      
     22 root     -51   0       0      0      0 S   0.0   0.0   0:00.00 idle_inject/1                                
     23 root      rt   0       0      0      0 S   0.0   0.0   0:00.29 migration/1                                  
     24 root      20   0       0      0      0 S   0.0   0.0   0:00.06 ksoftirqd/1                                  
     26 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/1:0H-events_highpri                  
     27 root      20   0       0      0      0 S   0.0   0.0   0:00.00 cpuhp/2                                      
     28 root     -51   0       0      0      0 S   0.0   0.0   0:00.00 idle_inject/2                                
     29 root      rt   0       0      0      0 S   0.0   0.0   0:00.28 migration/2                                  
     30 root      20   0       0      0      0 S   0.0   0.0   0:00.04 ksoftirqd/2                                  
     32 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/2:0H-events_highpri                  
     33 root      20   0       0      0      0 S   0.0   0.0   0:00.00 cpuhp/3                                      
     34 root     -51   0       0      0      0 S   0.0   0.0   0:00.00 idle_inject/3                                
     35 root      rt   0       0      0      0 S   0.0   0.0   0:00.28 migration/3                                  
     36 root      20   0       0      0      0 S   0.0   0.0   0:00.03 ksoftirqd/3                                  
     38 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/3:0H-events_highpri                  
     39 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kdevtmpfs                                    
     40 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-inet_frag_wq                       
     41 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_kthread                            
     42 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_rude_kthread                       
     43 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_trace_kthread                      
     44 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kauditd                                      
     45 root      20   0       0      0      0 S   0.0   0.0   0:00.00 khungtaskd                                   
     46 root      20   0       0      0      0 S   0.0   0.0   0:00.00 oom_reaper                                   
     48 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-writeback                          
     50 root      20   0       0      0      0 S   0.0   0.0   0:00.41 kcompactd0                                   
     51 root      25   5       0      0      0 S   0.0   0.0   0:00.00 ksmd                                         
     52 root      39  19       0      0      0 S   0.0   0.0   0:00.00 khugepaged                                   
     53 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-kblockd                            
     54 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-blkcg_punt_bio
     
# процес, який споживає найбільше пам'яті (RAM) - 1659 gnome-shell 8%

# Знайди PID процесу вашої поточної оболонки (bash/zsh).
test@test-VirtualBox:~$ ps -ef | grep bash
test        9864    9857  0 00:46 pts/0    00:00:00 bash

# Завдання 2. Робота у фоні та керування процесами (1 бали)

# Запусти довгу команду (наприклад, sleep 1000) у фоновому режимі.
test@test-VirtualBox:~$ sleep 1000 &
[1] 11778

# Перевір список фонових завдань.
test@test-VirtualBox:~$ jobs
[1]+  Running                 sleep 1000 &

# Поверни цей процес із фону на передній план.
test@test-VirtualBox:~$ fg %1
sleep 1000
^Z
[1]+  Stopped                 sleep 1000

# Зупини процес та «примусово» заверши його за допомогою kill.
test@test-VirtualBox:~$ kill -9 11778
test@test-VirtualBox:~$ jobs
[1]+  Killed                  sleep 1000

# Запусти будь-яку команду за допомогою nohup, щоб вона продовжувала працювати після закриття терміналу.
test@test-VirtualBox:~$ nohup sleep 300 > nohup_sleep.log 2>&1 &
[1] 12506
test@test-VirtualBox:~$ ps aux | grep sleep
test       12506  0.0  0.0  16980  2168 pts/0    S    01:06   0:00 sleep 300
test       12566  0.0  0.0  17824  2376 pts/0    S+   01:06   0:00 grep --color=auto sleep

# Завдання 3. Пріоритети та обмеження (2 бал)

# Запусти нову команду з підвищеним значенням nice (нижчим пріоритетом).
test@test-VirtualBox:~$ nice -n 10 sleep 300 &
[1] 12969
test@test-VirtualBox:~$ ps -o pid,ni,cmd -p 12969
    PID  NI CMD
  12969  10 sleep 300

# Зміни пріоритет вже запущеного процесу.
test@test-VirtualBox:~$ renice -n 15 -p 12969
12969 (process ID) old priority 10, new priority 15
test@test-VirtualBox:~$ ps -o pid,ni,cmd -p 12969
    PID  NI CMD
  12969  15 sleep 300

# Переглянь поточні обмеження ресурсів вашого користувача за допомогою ulimit.
test@test-VirtualBox:~$ ulimit -a
real-time non-blocking time  (microseconds, -R) unlimited
core file size              (blocks, -c) 0
data seg size               (kbytes, -d) unlimited
scheduling priority                 (-e) 0
file size                   (blocks, -f) unlimited
pending signals                     (-i) 31423
max locked memory           (kbytes, -l) 1016328
max memory size             (kbytes, -m) unlimited
open files                          (-n) 1024
pipe size                (512 bytes, -p) 8
POSIX message queues         (bytes, -q) 819200
real-time priority                  (-r) 0
stack size                  (kbytes, -s) 8192
cpu time                   (seconds, -t) unlimited
max user processes                  (-u) 31423
virtual memory              (kbytes, -v) unlimited
file locks                          (-x) unlimited


# Завдання 4. Моніторинг ресурсів (1 бал)

# Виведи інформацію про використання дискового простору (вільне/зайняте місце).
test@test-VirtualBox:~$ df -h
Filesystem      Size  Used Avail Use% Mounted on
tmpfs           795M  1.6M  793M   1% /run
/dev/sda2        49G   12G   36G  25% /
tmpfs           3.9G     0  3.9G   0% /dev/shm
tmpfs           5.0M  8.0K  5.0M   1% /run/lock
tmpfs           795M  144K  794M   1% /run/user/1000
/dev/sr0         51M   51M     0 100% /media/test/VBox_GAs_7.2.4

# Покажи обсяг вільної та використаної оперативної пам'яті в системі у зручному для читання форматі (Мб/Гб).
test@test-VirtualBox:~$ free -h
               total        used        free      shared  buff/cache   available
Mem:           7.8Gi       2.0Gi       4.3Gi        55Mi       1.7Gi       5.7Gi
Swap:          4.0Gi          0B       4.0Gi

# End of SKhoroshko_homework_3.md
