## День 1
* Введение (краткая история Unix и Linux, диаграмма эволюции Unix https://en.wikipedia.org/wiki/Unix#/media/File:Unix_history-simple.svg)
* Unix консоль как интерфейс к системе
* Демонстрация работы в консоли: ls -alF and ps
* Красота Linux консоли: zsh и oh-my-zsh
* Понятие пакета и пакетного менеджера
* Домашнее задание: написать сервер, показывающий динамическую веб-страницу (на любом ЯП)
* Анатомия Unix-системы: кернелспейс и юзерспейс
* Кольца (rings) процессора
* Очень краткая история операционных систем
* Дебаты Торвальдс-Танненбаум
* История дистрибутивов Linux
* Анатомия Unix-системы еще раз: все является файлом
* Файловые системы: стандарт файловой иерархии FHS
* Файлы /etc/fstab, /etc/mtab, проблемы /etc/mtab
* Файловые системы: superblock, inodes, blocks
* Файловые системы: hardlinks, symlinks
* Файловые системы: ext2, ext3, ext4, понятие журналирования, разные степени журналирования, понятние барьеров
* ext\*: место, зарезервированное для пользователя root
* Файловые системы: утилита blktrace
* Файловые системы: ZFS, алгоритм CoW, ARC, снэпшоты
* Утилита smartctl, SMART long tests

## День 2
* Файловые системы: снэпшоты как часть Disaster Recovery Plan
* Файловые системы: BTRFS
* Файловые системы: псевдо-файловые системы /dev, /proc, /sys
* Файловые системы: утилиты разметки fdisk, cfdisk, parted, работа с дисками в Advanced Format
* Файловые системы: утилита file
* Пользователи: файл /etc/passwd и его поля
* Пользователи: суперпользователи (понятие UID, соответствие UID и имен, UID 0) и обычные пользователи
* Пользователи: модель безопасности Unix
* Модель безопасности Unix: подсистема PAM
* Модель безопасности Unix: su и sudo
* Модель безопасности Unix применительно к файловым системам: традиционные права
* Права на файлы и флаги: биты rwx
* Права на файлы и флаги: биты SUID и SGID
* Права на файлы и флаги: sticky bit
* Модель безопасности Unix применительно к файловым системам: расширенные атрибуты, SELinux и другие MAC/RBAC фреймворки (GRSecurity, Tomoyo)
* Модель безопасности Unix применительно к файловым системам: POSIX ACLs
* AppArmor и его проблемы
* Модель памяти: использованная память, swap и RSS
* Модель памяти: zram
* Модель памяти: KSM и UKSM
* Модель памяти применительно к файловым системам: block cache
* Процессы и межпроцессное взаимодействие: порядок запуска программы из бинарного файла на диске
* Процессы и межпроцессное взаимодействие: динамическая линковка и динамический линкер/загрузчик
* Процессы и межпроцессное взаимодействие: magic numbers
* Процессы и межпроцессное взаимодействие: стандартные файловые дескрипторы
* Процессы и файлы: файловые дескрипторы, стандартный API для чтения/записи
* Процессы и файлы: системный вызов ioctl и асинхронная обработка
* Процессы и межпроцессное взаимодействие: процесс-родитель и процесс-потомок, вызовы fork() и exec(), еще раз про алгоритм CoW
* Процессы и межпроцессное взаимодействие: пайпы
* Процессы и межпроцессное взаимодействие: сигналы и обработчики сигналов, утилита kill, сигнал SIGKILL и его особенности
* Процессы и межпроцессное взаимодействие: стандартные сигналы
* Процессы и межпроцессное взаимодействие: многопоточность, отображения потоков 1:1 и N:M
* Процессы и межпроцессное взаимодействие: лимиты (и /proc/XXXX/limits), утилита ulimit, файл /etc/security/limits.conf
* Процессы и межпроцессное взаимодействие: разделяемая память, семафоры, UNIX-сокеты
* Домашняя работа: система Vagrant

## День 3
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
* Logging: ELK, Graylog, Splunk
* Networking: basic network configuration
* Networking: TCP and UDP
* Networking: Network Manager
* Networking: ethtool
* Networking: MAC address
* Networking: ifconfig
* Networking: 'ip' command
* Networking: DNS
* Networking: routing
* Networking: GRE tunnels
* Networking: IPsec
* Networking: OpenVPN (L2 and L3)
* Networking: tcpdump and Wireshark
* Networking: NFS
* Networking: Samba
* Networking: LDAP

## День 4
* Networking: netfilter and iptables
* Networking: port knocking
* Networking: ipset
* Networking: NAT (SNAT, DNAT) and masquerading
* Networking: conntrack table
* Networking: FTP
* Networking: SSH, scp and SFTP
* Networking: ssh-agent
* Networking: HTTP
* Networking: Apache and nginx
* Networking: rsync and rsyncd
* Networking: netcat
* A word on scripting (dynamic vs static languages)
* Bash scripting: interactive and non-interactive mode, config files
* Bash scripting: variables and exporting
* Bash scripting: built-ins
* Bash scripting: globs
* Bash scripting: control structures (if, case, for)
* Bash scripting: test command and test built-in
* Bash scripting: magic variables ($? and so on)
* Bash scripting: debugging
* Bash scripting: arrays
* Writing a simple program in bash
* >, >> and <
* Unix commands: wc, cat, cut, sort
* Unix commands: awk and sed 
* Unix commands: find
* Unix commands: xargs
* Bash scripting: defensive programming
* A word on Perl scripting
* Source control systems: non-distribited and distribiuted
* Source control systems: git
* Creating and cloning a git repo
* Git: config variables and origin repos
* Anatomy of a git repository
* Git: working copy, non-bare and bare repositories
* Git: branching, merging and rebasing

## День 5
* Git flow
* A word on observability
* Linux observability tools: Brendan Gregg's matrix
* Tracing: strace
* Tracing: ltrace
* Tracing: ptrace() call
* gdb and debug symbols
* Tracing: Poor Man's Profiler
* core files and backtrace gdb command
* Observability: top
* Observability: atop
* Observability: mpstat
* Observability: iostat
* Observability: pidstat
* Observability: iotop
* Observability: cat /proc/interrupts
* Observability: Munin
* Observability: Zabbix and time series databases
* Observability: Graphite stack
* Observability: netdata
* Observability: perf
* Observability: DTrace
* Observability: BPF and BPF tools
* Observability: flamegraphs
* Observability: kaldur
* Observability: flamegraphs and dynamic languages
* Homework: show your code
* Homework: writing a reference implementation
* A word on package managers
* RPM and dpkg
* Docker and Nix
* Homework: creating a Debian package using FPM
* Homework: creating a Debian package using checkinstall
* Homework: creating a Debian repo
* Homework: stress testing using ab
* Homework: stress testing using siege
* Homework: writing an upstart service definition file
* Homework: writing a systemd unit file
