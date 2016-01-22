## Synopsis

At the top of the file there should be a short introduction and/ or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)


![Alt text](https://raw.githubusercontent.com/port9org/hw/master/TL_wr841n-v9/20160103_201918.jpg "Optional title")
----
Firmware auslesen per JTAG?
Firmware dump?
Custom Firmware?
Memory Upgrade?
firmware hacker kit 

######################

PORT      STATE SERVICE
22/tcp    open  ssh
80/tcp    open  http
1900/tcp  open  upnp
49152/tcp open  unknown

##############


./unsquashfs_all.sh /root/Desktop/TL_wr841n-v9/Firmware/_wr841nv9_en_3_16_9_up_boot\(141013\).bin.extracted/120200.squashfs

/etc/shadow ist: root:$1$GTN.gpri$DlSyKvZKMR9A9Uj9e9wR3/:15502:0:99999:7:::
Login: root Password: sohoadmin

Model: TL-wr841n
Interface: COM4
Baud Speed: 115200

----------------------
tpl

U-Boot 1.1.4 (Build from LSDK-9.5.3.16 at Oct 13 2014 - 17:01:20)

ap143 - Honey Bee 1.1

DRAM:   32 MB
Flash Manuf Id 0xc2, DeviceId0 0x20, DeviceId1 0x16
Flash:  4 MB
Using default environment

In:    serial
Out:   serial
Err:   serial
Net:   ath_gmac_enet_initialize...
ath_gmac_enet_initialize: reset mask:0xc02200
Scorpion ---->S27 PHY*
S27 reg init
GMAC: cfg1 0x800c0000 cfg2 0x7114
eth0: ba:be:fa:ce:08:41
athrs27_phy_setup ATHR_PHY_CONTROL 4:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 4:0x10
eth0 up
Honey Bee ---->  MAC 1 S27 PHY*
S27 reg init
ATHRS27: resetting s27
ATHRS27: s27 reset done
GMAC: cfg1 0x800c0000 cfg2 0x7214
eth1: ba:be:fa:ce:08:41
athrs27_phy_setup ATHR_PHY_CONTROL 0:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 0:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 1:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 1:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 2:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 2:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 3:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 3:0x10
eth1 up
eth0, eth1
Setting 0x181162c0 to 0x5cb9a100
is_auto_upload_firmware=0
Autobooting in 1 seconds
## Booting image at 9f020000 ...
   Uncompressing Kernel Image ... OK

Starting kernel ...

Booting QCA953x
Linux version 2.6.31 (tomcat@buildserver) (gcc version 4.3.3 (GCC) ) #6 Mon Oct                                                        13 17:03:27 CST 2014
flash_size passed from bootloader = 4
Ram size passed from bootloader =33554432
CPU revision is: 00019374 (MIPS 24Kc)
ath_sys_frequency: cpu apb ddr apb cpu 550 ddr 396 ahb 198
Determined physical RAM map:
 memory: 02000000 @ 00000000 (usable)
Zone PFN ranges:
  Normal   0x00000000 -> 0x00002000
Movable zone start PFN for each node
early_node_map[1] active PFN ranges
    0: 0x00000000 -> 0x00002000
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 8128
Kernel command line: console=ttyS0,115200 root=31:2 rootfstype=squashfs init=/sb                                                       in/init mtdparts=ath-nor0:128k(u-boot),1024k(kernel),2816k(rootfs),64k(config),6                                                       4k(art) mem=32M
PID hash table entries: 128 (order: 7, 512 bytes)
Dentry cache hash table entries: 4096 (order: 2, 16384 bytes)
Inode-cache hash table entries: 2048 (order: 1, 8192 bytes)
Primary instruction cache 64kB, VIPT, 4-way, linesize 32 bytes.
Primary data cache 32kB, 4-way, VIPT, cache aliases, linesize 32 bytes
Writing ErrCtl register=00000000
Readback ErrCtl register=00000000
Memory: 24188k/32768k available (1563k kernel code, 8580k reserved, 381k data, 1                                                       08k init, 0k highmem)
NR_IRQS:128
plat_time_init: plat time init done
Calibrating delay loop... 365.56 BogoMIPS (lpj=731136)
Mount-cache hash table entries: 512

****************ALLOC***********************
 Packet mem: 80213240 (0x600000 bytes)
********************************************

NET: Registered protocol family 16
bio: create slab <bio-0> at 0
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
net_link: create socket ok.
TCP established hash table entries: 1024 (order: 1, 8192 bytes)
TCP bind hash table entries: 1024 (order: 0, 4096 bytes)
TCP: Hash tables configured (established 1024 bind 1024)
TCP reno registered
NET: Registered protocol family 1
ATH GPIOC major 0
squashfs: version 4.0 (2009/01/31) Phillip Lougher
msgmni has been set to 47
io scheduler noop registered
io scheduler deadline registered (default)
Serial: 8250/16550 driver, 1 ports, IRQ sharing disabled
serial8250.0: ttyS0 at MMIO 0xb8020000 (irq = 19) is a 16550A
console [ttyS0] enabled
PPP generic driver version 2.4.2
NET: Registered protocol family 24
5 cmdlinepart partitions found on MTD device ath-nor0
Creating 5 MTD partitions on "ath-nor0":
0x000000000000-0x000000020000 : "u-boot"
0x000000020000-0x000000120000 : "kernel"
0x000000120000-0x0000003e0000 : "rootfs"
0x0000003e0000-0x0000003f0000 : "config"
0x0000003f0000-0x000000400000 : "art"
->Oops: flash id 0xc22016 .
Ooops, why the devices couldn't been initialed?
TCP cubic registered
NET: Registered protocol family 17
802.1Q VLAN Support v1.8 Ben Greear <greearb@candelatech.com>
All bugs added by David S. Miller <davem@redhat.com>
athwdt_init: Registering WDT success
VFS: Mounted root (squashfs filesystem) readonly on device 31:2.
Freeing unused kernel memory: 108k freed
init started:  BusyBox v1.01 (2014.10.13-09:06+0000) multi-call binary
This Board use 2.6.31
xt_time: kernel timezone is -0000
nf_conntrack version 0.5.0 (512 buckets, 5120 max)
ip_tables: (C) 2000-2006 Netfilter Core Team
insmod: cannot open module `/lib/modules/2.6.31/kernel/iptable_raw.ko': No such                                                        file or directory
insmod: cannot open module `/lib/modules/2.6.31/kernel/flashid.ko': No such file or directory
PPPoL2TP kernel driver, V1.0
PPTP driver version 0.8.3
insmod: cannot open module `/lib/modules/2.6.31/kernel/harmony.ko': No such file or directory
insmod: cannot open module `/lib/modules/2.6.31/kernel/af_key.ko': No such file or directory
insmod: cannot open module `/lib/modules/2.6.31/kernel/xfrm_user.ko': No such file or directory
Now flash open!
Now flash open!
qca955x_GMAC: Length per segment 1536
953x_GMAC: qca953x_gmac_attach
Link Int Enabled
qca953x_set_gmac_caps  CHECK DMA STATUS
mac:1 Registering S27....
qca955x_GMAC: RX TASKLET - Pkts per Intr:32
qca955x_GMAC: Max segments per packet :   1
qca955x_GMAC: Max tx descriptor count :   512
qca955x_GMAC: Max rx descriptor count :   128
qca955x_GMAC: Mac capability flags    :   2D81
953x_GMAC: qca953x_gmac_attach
Link Int Enabled
qca953x_set_gmac_caps  CHECK DMA STATUS
mac:0 Registering S27....
qca955x_GMAC: RX TASKLET - Pkts per Intr:32
qca955x_GMAC: Max segments per packet :   1
qca955x_GMAC: Max tx descriptor count :   512
qca955x_GMAC: Max rx descriptor count :   128
qca955x_GMAC: Mac capability flags    :   2581

 (none) mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
(none) login: athr_gmac_ring_alloc Allocated 8192 at 0x81c54000
athr_gmac_ring_alloc Allocated 2048 at 0x81cb1000
HONEYBEE ----> S27 PHY MDIO
ATHRS27: resetting s27
ATHRS27: s27 reset done
++++ athrs27_igmp_setup once
port0 vid is 0xb000b
port1 vid is 0x30003
port2 vid is 0x50005
port3 vid is 0x70007
port4 vid is 0x90009
++ PVID: 0x0000000b, bitmap: 0x0000001f
++ PVID: 0x00000003, bitmap: 0x0000001f
++ PVID: 0x00000005, bitmap: 0x0000001f
++ PVID: 0x00000007, bitmap: 0x0000001f
++ PVID: 0x00000009, bitmap: 0x0000001f
vtable vid: 0x00000002, bitmap 0x00000003
vtable vid: 0x00000004, bitmap 0x00000005
vtable vid: 0x00000006, bitmap 0x00000007
vtable vid: 0x00000008, bitmap 0x00000009
vtable vid: 0x0000000a, bitmap 0x0000000b
vtable vid: 0x0000000c, bitmap 0x0000000d
vtable vid: 0x0000000e, bitmap 0x0000000f
vtable vid: 0x00000010, bitmap 0x00000011
vtable vid: 0x00000012, bitmap 0x00000013
vtable vid: 0x00000014, bitmap 0x00000015
vtable vid: 0x00000016, bitmap 0x00000017
vtable vid: 0x00000018, bitmap 0x00000019
vtable vid: 0x0000001a, bitmap 0x0000001b
vtable vid: 0x0000001c, bitmap 0x0000001d
vtable vid: 0x0000001e, bitmap 0x0000001f
vtable vid: 0x00000020, bitmap 0x00000021
Setting Drop CRC Errors, Pause Frames and Length Error frames
Setting PHY...
athr_gmac_ring_alloc Allocated 8192 at 0x81cbc000
athr_gmac_ring_alloc Allocated 2048 at 0x81e98000
HONEYBEE ----> S27 PHY MDIO
Setting Drop CRC Errors, Pause Frames and Length Error frames
Setting PHY...
device eth0 entered promiscuous mode
Now flash open!
athr_gmac_ring_free Freeing at 0x81cbc000
athr_gmac_ring_free Freeing at 0x81e98000
athr_gmac_ring_alloc Allocated 8192 at 0x81cbc000
athr_gmac_ring_alloc Allocated 2048 at 0x81e98000
HONEYBEE ----> S27 PHY MDIO
Setting Drop CRC Errors, Pause Frames and Length Error frames
Setting PHY...
athr_gmac_ring_free Freeing at 0x81c54000
athr_gmac_ring_free Freeing at 0x81cb1000
athr_gmac_ring_alloc Allocated 8192 at 0x81ccc000
athr_gmac_ring_alloc Allocated 2048 at 0x81cb1000
HONEYBEE ----> S27 PHY MDIO
Setting Drop CRC Errors, Pause Frames and Length Error frames
Setting PHY...
nf_conntrack_rtsp v0.6.21 loading
nf_nat_rtsp v0.6.21 loading
adf: module license 'Proprietary' taints kernel.
Disabling lock debugging due to kernel taint
ath_hal: 0.9.17.1 (AR5416, AR9380, REGOPS_FUNC, WRITE_EEPROM, 11D)
ath_rate_atheros: Copyright (c) 2001-2005 Atheros Communications, Inc, All Rights Reserved
ath_dev: Copyright (c) 2001-2007 Atheros Communications, Inc, All Rights Reserved
ath_ahb: 9.5.3.16 (Atheros/multi-bss)
Enterprise mode: 0x03fc0000
Restoring Cal data from Flash
ath_get_caps[5872] rx chainmask mismatch actual 3 sc_chainmak 0
ath_get_caps[5847] tx chainmask mismatch actual 3 sc_chainmak 0
ATH_RESERVED_TXBUF = 1000
wifi0: Atheros ???: mem=0xb8100000, irq=2
ath_pci: 9.5.3.16 (Atheros/multi-bss)
VAP device ath0 created
Setting Max Stations:32
        DCS for CW interference mitigation:   0
        DCS for WLAN interference mitigation: 0

 DES SSID SET=TP-LINK_D9F5A4
 ieee80211_ioctl_siwmode: imr.ifm_active=131712, new mode=3, valid=1
athr_gmac_ring_free Freeing at 0x81ccc000
athr_gmac_ring_free Freeing at 0x81cb1000
br0: port 1(eth0) entering disabled state
athr_gmac_ring_alloc Allocated 8192 at 0x81f6c000
athr_gmac_ring_alloc Allocated 2048 at 0x81cb1000
HONEYBEE ----> S27 PHY MDIO
Setting Drop CRC Errors, Pause Frames and Length Error frames
Setting PHY...
device ath0 entered promiscuous mode
br0: port 2(ath0) entering forwarding state
 ieee80211_ioctl_siwmode: imr.ifm_active=1442432, new mode=3, valid=1
br0: port 2(ath0) entering disabled state

 DES SSID SET=TP-LINK_D9F5A4
br0: port 2(ath0) entering forwarding state
qca955x_GMAC: GE0 RX DMA ENABLE
blockWps_proc_write 806: write value = 0
**** drop_caches_sysctl_handler: all done timer added ...****

 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login:
 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login:
 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login:
 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login:
 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login:
 TL-WR841N mips #6 Mon Oct 13 17:03:27 CST 2014 (none)
TL-WR841N login: tplink
Password:
Login incorrect
TL-WR841N login: tplink
Password:


Login incorrect
TL-WR841N login: TL-WR841N login: TL-WR841N login:
TL-WR841N login:
TL-WR841N login:
TL-WR841N login:
TL-WR841N login: tplink
¦assword:

U-Boot 1.1.4 (Build from LSDK-9.5.3.16 at Oct 13 2014 - 17:01:20)

ap143 - Honey Bee 1.1

DRAM:   32 MB
Flash Manuf Id 0xc2, DeviceId0 0x20, DeviceId1 0x16
Flash:  4 MB
Using default environment

In:    serial
Out:   serial
Err:   serial
Net:   ath_gmac_enet_initialize...
ath_gmac_enet_initialize: reset mask:0xc02200
Scorpion ---->S27 PHY*
S27 reg init
GMAC: cfg1 0x800c0000 cfg2 0x7114
eth0: ba:be:fa:ce:08:41
athrs27_phy_setup ATHR_PHY_CONTROL 4:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 4:0x10
eth0 up
Honey Bee ---->  MAC 1 S27 PHY*
S27 reg init
ATHRS27: resetting s27
ATHRS27: s27 reset done
GMAC: cfg1 0x800c0000 cfg2 0x7214
eth1: ba:be:fa:ce:08:41
athrs27_phy_setup ATHR_PHY_CONTROL 0:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 0:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 1:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 1:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 2:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 2:0x10
athrs27_phy_setup ATHR_PHY_CONTROL 3:0x1000
athrs27_phy_setup ATHR_PHY_SPEC_STAUS 3:0x10
eth1 up
eth0, eth1
Setting 0x181162c0 to 0x5cb9a100
is_auto_upload_firmware=0
Autobooting in 1 seconds
hb> tpl
Unknown command 'tpl' - try 'help'
hb> tpl
Unknown command 'tpl' - try 'help'
hb> tpl
Unknown command 'tpl' - try 'help'
hb> ls
Unknown command 'ls' - try 'help'
hb> help
?       - alias for 'help'
boot    - boot default, i.e., run 'bootcmd'
bootd   - boot default, i.e., run 'bootcmd'
bootm   - boot application image from memory
cp      - memory copy
erase   - erase FLASH memory
help    - print online help
md      - memory display
mm      - memory modify (auto-incrementing)
mtest   - simple RAM test
mw      - memory write (fill)
nm      - memory modify (constant address)
ping    - send ICMP ECHO_REQUEST to network host
printenv- print environment variables
progmac - Set ethernet MAC addresses
reset   - Perform RESET of the CPU
run     - run commands in an environment variable
setenv  - set environment variables
tftpboot- boot image via network using TFTP protocol
version - print monitor version
hb> printenv-
Unknown command 'printenv-' - try 'help'
hb> printenv
bootargs=console=ttyS0,115200 root=31:02 rootfstype=squashfs init=/sbin/init mtdparts=ath-nor0:128k(u-boot),1024k(kernel),2816k(rootfs),64k(config),64k(art)
bootcmd=bootm 0x9f020000
bootdelay=1
baudrate=115200
ethaddr=0xba:0xbe:0xfa:0xce:0x08:0x41
ipaddr=192.168.1.1
serverip=192.168.1.10
dir=
lu=tftp 0x80060000 ${dir}u-boot.bin&&erase 0x9f000000 +$filesize&&cp.b $fileaddr 0x9f000000 $filesize
lf=tftp 0x80060000 ${dir}ap143${bc}-squashfs&&erase 0x9f120000 +$filesize&&cp.b $fileaddr 0x9f120000 $filesize
lk=tftp 0x80060000 ${dir}vmlinux${bc}.lzma.uImage&&erase 0x9f020000 +$filesize&&cp.b $fileaddr 0x9f020000 $filesize
stdin=serial
stdout=serial
stderr=serial
ethact=eth0

Environment size: 676/65532 bytes
hb> ls
Unknown command 'ls' - try 'help'
hb> dir
Unknown command 'dir' - try 'help'
hb> dd
Unknown command 'dd' - try 'help'
hb>
hb> mm
Usage:
mm      - memory modify (auto-incrementing)

hb> version

U-Boot 1.1.4 (Build from LSDK-9.5.3.16 at Oct 13 2014 - 17:01:20)
hb> sysupgrade
Unknown command 'sysupgrade' - try 'help'
hb> U-Boot 1.1.4 (Build from LSDK-9.5.3.16 at Oct 13 2014 - 17:01:20)
Unknown command 'U-Boot' - try 'help'
hb>
