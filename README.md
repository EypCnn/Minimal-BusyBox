# Minimal BusyBox

Copyright (C) 2017 OneTeam-EypCnn

Bu uygulama, Android için bir BusyBox yükleyicisidir.

[BusyBox] (http://busybox.net) birçok yaygın UNIX yardımcı programının küçük sürümlerini tek bir küçük çalıştırılabilir dosyaya birleştirir. Genellikle GNU fileutils, shellutils, vs.'de bulunan araçların birçoğu için değiştirmeler sağlar. BusyBox'daki yardımcı programların genelde tam özellikli GNU kuzenlerinden daha az seçeneği vardır; Bununla birlikte, içerilen seçenekler beklenen işlevselliği sağlar ve GNU muadillerine çok benzer davranır. BusyBox, herhangi bir küçük veya gömülü sistem için oldukça kapsamlı bir ortam sağlar.

En son BusyBox v1.0, desteklenen 338 uygulaması:

	[, [[, acpid, adjtimex, ar, arp, ash, awk, base64, basename, bbconfig,
	beep, blkdiscard, blkid, blockdev, bootchartd, brctl, bunzip2, bzcat,
	bzip2, cal, cat, catv, chat, chattr, chgrp, chmod, chown, chpst,
	chroot, chrt, chvt, cksum, clear, cmp, comm, conspy, cp, cpio, crond,
	crontab, cryptpw, cttyhack, cut, date, dc, dd, deallocvt, devfsd,
	devmem, df, diff, dirname, dmesg, dnsd, dnsdomainname, dos2unix, dpkg,
	dpkg-deb, du, dumpkmap, echo, ed, egrep, env, envdir, envuidgid,
	ether-wake, expand, expr, fakeidentd, false, fatattr, fbset, fbsplash,
	fdflush, fdformat, fdisk, fgconsole, fgrep, find, findfs, flock, fold,
	free, freeramdisk, fsck, fsck.minix, fstrim, fsync, ftpd, ftpget,
	ftpput, fuser, getopt, grep, groups, gunzip, gzip, halt, hd, hdparm,
	head, hexdump, hostname, httpd, hush, hwclock, i2cdetect, i2cdump,
	i2cget, i2cset, id, ifconfig, ifdown, ifenslave, ifplugd, ifup, inetd,
	init, inotifyd, install, ionice, iostat, ip, ipaddr, ipcalc, iplink,
	ipneigh, iproute, iprule, iptunnel, kbd_mode, kill, killall, killall5,
	klogd, less, linux32, linux64, linuxrc, ln, loadkmap, logger, logname,
	losetup, lpd, lpq, lpr, ls, lsattr, lsof, lspci, lsusb, lzcat, lzma,
	lzop, lzopcat, makedevs, makemime, man, md5sum, mesg, mkdir, mkdosfs,
	mke2fs, mkfifo, mkfs.ext2, mkfs.minix, mkfs.reiser, mkfs.vfat, mknod,
	mkpasswd, mkswap, mktemp, modinfo, more, mount, mountpoint, mpstat, mt,
	mv, nameif, nbd-client, nc, netstat, nice, nmeter, nohup, nsenter,
	nslookup, ntpd, od, openvt, patch, pgrep, pidof, ping, ping6,
	pipe_progress, pivot_root, pkill, pmap, popmaildir, poweroff, powertop,
	printenv, printf, ps, pscan, pstree, pwd, pwdx, raidautorun, rdate,
	rdev, readlink, readprofile, realpath, reboot, reformime, renice,
	reset, resize, rev, rfkill, rm, rmdir, route, rpm, rpm2cpio, rtcwake,
	run-parts, runsv, runsvdir, rx, script, scriptreplay, sed, sendmail,
	seq, setarch, setconsole, setkeycodes, setlogcons, setserial, setsid,
	setuidgid, sh, sha1sum, sha256sum, sha3sum, sha512sum, showkey, shuf,
	slattach, sleep, smemcap, softlimit, sort, split, start-stop-daemon,
	stat, strings, stty, sum, sv, svc, svlogd, swapoff, swapon,
	switch_root, sync, sysctl, tac, tail, tar, taskset, tcpsvd, tee,
	telnet, telnetd, test, tftp, tftpd, time, timeout, top, touch, tr,
	traceroute, traceroute6, true, truncate, tty, ttysize, tunctl, tune2fs,
	ubiattach, ubidetach, ubimkvol, ubirmvol, ubirsvol, ubiupdatevol,
	udpsvd, uevent, umount, uname, uncompress, unexpand, uniq, unix2dos,
	unlink, unlzma, unlzop, unshare, unxz, unzip, uptime, usleep, uudecode,
	uuencode, vconfig, vi, volname, watch, watchdog, wc, wget, which,
	whoami, whois, xargs, xz, xzcat, yes, zcat, zcip

**Gereksinimler**:

* ARM, x86 veya MIPS mimarisi olan cihaz
* Android 2.3 (API 9) veya daha yenisi
* Root
