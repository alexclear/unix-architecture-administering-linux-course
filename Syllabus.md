## Day 1
* Intorduction (a word on Unix and Linux, a Unix evolution diagram https://en.wikipedia.org/wiki/Unix#/media/File:Unix_history-simple.svg)
* Unix console as an interface to everything else
* Demo time: ls -alF and ps
* The beauty of Linux console: zsh and oh-my-zsh
* A word on package managers
* Homework: a server which serves a webpage in any language
* Anatomy of a Unix system: kernel space and user space
* Processor rings
* History of Linux distributions
* Anatomy of a Unix system again: everything is a file
* Filesystems: file hierarchy, FHS
* /etc/fstab, /etc/mtab, caveats
* Filesystems: superblock, inodes, blocks
* Filesystems: hardlinks, symlinks
* Filesystems: ext2, ext3, ext4, notion of journaling, different journaling modes, barriers
* ext\*: reserved for root
* Filesystems: blktrace
* Filesystems: ZFS, CoW, ARC, snapshots
* smartctl, SMART long tests

## Day 2
* Filesystems: snapshots as a part of DRP strategy
* Filesystems: BTRFS
* Filesystems: /dev, /proc, /sys
* Filesystems: fdisk, cfdisk, parted, ADF drives
* Filesystems: 'file' command
* Users: /etc/passwd and its fields
* Users: superusers (UID 0 and mapping of names to UIDs) and ordinary users
* Users: UNIX security model
* UNIX security model: PAM
* UNIX security model: su and sudo
* UNIX security model (filesystems): traditional rights
* File permissions and flags: rwx bits
* File permissions and flags: SUID and SGID bit
* File permissions and flags: sticky bit
* UNIX security model (filesystems): extended attributes, SELinux and other MAC/RBAC frameworks (GRSecurity, Tomoyo)
* UNIX security model (filesystems): POSIX ACLs
* AppArmor and its caveats
* Memory model: used memory, swap and RSS
* Memory model: zram
* Memory model: KSM and UKSM
* Memory model (filesystems): block cache
* Processes and IPC: starting a program from a binary file
* Processes and IPC: dynamic linking and dynamic linker/loader
* Processes and IPC: magic numbers
* Processes and IPC: standard file descriptors
* Processes and files: file descriptors, standard read/write API
* Processes and files: ioctls and asynchronous processing
* Processes and IPC: parents and children, fork() and exec(), CoW again
* Processes and IPC: pipes
* Processes and IPC: signals and signal handlers, 'kill' command, SIGKILL
* Processes and IPC: standard signals
* Processes and IPC: multithreading, 1:1 and N:M threads
* Processes and IPC: limits (and /proc/XXXX/limits), ulimit, /etc/security/limits.conf
* Processes and IPC: shmem, semaphores, UNIX sockets
* Homework: Vagrant

## Day 3

* Processes and IPC: niceness, 'nice' and 'ionice' commands
* Linux boot process: BIOS and UEFI
* Linux boot process: BIOSes on various hardware
* Linux boot process: MBR, format of MBR and GPT
* Linux boot process: partition records
* Linux boot process: syslinux, LILO and GRUB
* Linux boot process: GRUB1 and its config, GRUB2 and its config
* Linux boot process: real and protected modes
* Linux boot process: /dev static entries, devfs and udev
* Linux boot process: PCI IDs and USB IDs, automatic hardware detection and configuration
* Linux boot process: init and /etc/inittab
* Linux boot process: BSD initscripts and SysV initscripts, runlevels
* Linux boot process: initrd and initramfs
* Linux boot process: anatomy of initrd, kernel modules, dracut
* Linux boot process: concurrency, bootchart, bootlog, concurrent initscripts
* Linux boot process: upstart, OpenRC, SMF
* Supervisors: daemontools, runit, god, bluepill, eye, forever, supervisord
* Linux boot process: systemd
* Linux boot process: cgroups and namespaces, their relation to systemd
* Logging: syslog
* Networking: basic network configuration
* Networking: TCP and UDP
* Networking: Network Manager
* Networking: ethtool
* Networking: MAC address
* Networking: ifconfig
* Networking: 'ip' command
* Networking: routing
* Networking: GRE tunnels
* Networking: IPsec
* Networking: OpenVPN (L2 and L3)
* Networking: tcpdump and Wireshark
* Networking: NFS
* Networking: Samba
* Networking: LDAP
* Networking: Apache and nginx
* Networking: netfilter and iptables

## Day 4

## Day 5
