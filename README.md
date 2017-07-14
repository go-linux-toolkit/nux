nux
===

*nux metric collector


运行结果

go test

======kernel======
KernelMaxFiles:187796 <nil>
KernelAllocateFiles:2592 <nil>
KernelMaxProc:32768 <nil>
KernelHostname:cacti69 <nil>
======loadavg======
LoadAvg:<1min:0.250000, 5min:0.060000, 15min:0.020000> <nil>
======cpuinfo======
NumCpu:2
CpuMHz:2133.409 <nil>
======cpustat======
CPU :<User:60262904, Nice:10092, System:38007736, Idle:959452359, Iowait:6236416, Irq:128431, SoftIrq:586617, Steal:0, Guest:0, Total:1064684555>
CPU0:<User:29630641, Nice:5323, System:18447143, Idle:478934396, Iowait:3361926, Irq:89457, SoftIrq:333581, Steal:0, Guest:0, Total:530802467>
CPU1:<User:30632262, Nice:4769, System:19560593, Idle:480517962, Iowait:2874490, Irq:38974, SoftIrq:253036, Steal:0, Guest:0, Total:533882086>
======dfstat======
<FsSpec:tmpfs, FsFile:/dev/shm, FsVfstype:tmpfs, BPFree:100.000000...> <nil>
<FsSpec:/dev/sda2, FsFile:/, FsVfstype:ext4, BPFree:52.782971...> <nil>
<FsSpec:/dev/sda1, FsFile:/boot, FsVfstype:ext4, BPFree:96.528658...> <nil>
<FsSpec:/dev/mapper/docker-8:2-2495095-422e313d9c5c291f07cabecabe384c537881c553ab14f5d4b93af2ec7cc226cf, FsFile:/var/lib/docker/devicemapper/mnt/422e313d9c5c291f07cabecabe384c537881c553ab14f5d4b93af2ec7cc226cf, FsVfstype:ext4, BPFree:98.665859...> <nil>
<nil> no such file or directory
<FsSpec:/dev/mapper/docker-8:2-2495095-a9cf7f97d975afcd4df012ac8b8af797407c7da0f4877d2eee2cef142e9ee306, FsFile:/var/lib/docker/devicemapper/mnt/a9cf7f97d975afcd4df012ac8b8af797407c7da0f4877d2eee2cef142e9ee306, FsVfstype:ext4, BPFree:96.766719...> <nil>
<nil> no such file or directory
<FsSpec:/dev/mapper/docker-8:2-2495095-e80079882f5e972a26c75c7ccd080c876215769c8c202c9ac49cdf8d5a981303, FsFile:/var/lib/docker/devicemapper/mnt/e80079882f5e972a26c75c7ccd080c876215769c8c202c9ac49cdf8d5a981303, FsVfstype:ext4, BPFree:93.408173...> <nil>
<nil> no such file or directory
<FsSpec:/dev/mapper/docker-8:2-2495095-812a4a485438f539218cd8463ffee31b8d79b9354407b2aa01950224401f16bf, FsFile:/var/lib/docker/devicemapper/mnt/812a4a485438f539218cd8463ffee31b8d79b9354407b2aa01950224401f16bf, FsVfstype:ext4, BPFree:93.408049...> <nil>
<nil> no such file or directory
<FsSpec:/dev/mapper/docker-8:2-2495095-85a7bc39c20dce30b4cf848ee77b860e35c86bd1578c507bf7dc1249387f9ecb, FsFile:/var/lib/docker/devicemapper/mnt/85a7bc39c20dce30b4cf848ee77b860e35c86bd1578c507bf7dc1249387f9ecb, FsVfstype:ext4, BPFree:93.408214...> <nil>
<nil> no such file or directory
======NetIfs======
<Iface:lo,InBytes:5146825762,InPackages:56049094...>
<Iface:eth0,InBytes:86503410163,InPackages:1033470011...>
<Iface:dummy0,InBytes:0,InPackages:0...>
<Iface:docker0,InBytes:1236892,InPackages:5371...>
<Iface:veth762955c,InBytes:1600081339,InPackages:8319267...>
<Iface:vethdef86ba,InBytes:243602373,InPackages:1570331...>
<Iface:vethecba454,InBytes:721485,InPackages:14070...>
<Iface:vethd67dab8,InBytes:751267240,InPackages:2383976...>
<Iface:veth5a63a4e,InBytes:5089792377,InPackages:10811076...>
======ListDiskStats======
<Device:sda, Major:8, Minor:0, ReadRequests:76206115...>
<Device:sda1, Major:8, Minor:1, ReadRequests:1517...>
<Device:sda2, Major:8, Minor:2, ReadRequests:27917277...>
<Device:sda3, Major:8, Minor:3, ReadRequests:48287148...>
<Device:dm-0, Major:253, Minor:0, ReadRequests:360247...>
<Device:dm-1, Major:253, Minor:1, ReadRequests:446...>
<Device:dm-2, Major:253, Minor:2, ReadRequests:9595...>
<Device:dm-3, Major:253, Minor:3, ReadRequests:72213...>
<Device:dm-4, Major:253, Minor:4, ReadRequests:74254...>
<Device:dm-5, Major:253, Minor:5, ReadRequests:76118...>
<Device:dm-6, Major:253, Minor:6, ReadRequests:79193...>
======MemInfo:======
<MemTotal:1968099328, MemFree:149381120, Buffers:10547200, Cached:92381184...> <nil>
=========TcpExt:=======
map[ListenOverflows:0 TCPDirectCopyFromPrequeue:303993213 TCPSACKReorder:0 TCPSchedulerFailed:1 TCPACKSkippedTimeWait:0 TCPAbortOnMemory:0 TCPAbortOnTimeout:36 TCPSackShiftFallback:9435 TCPOFODrop:0 SyncookiesRecv:0 SyncookiesFailed:153 RcvPruned:0 TWKilled:0 DelayedACKLocked:450 TCPSackRecovery:355 TCPACKSkippedSynRecv:0 TCPACKSkippedSeq:8 EmbryonicRsts:4 OfoPruned:0 TCPPureAcks:667304 TCPPartialUndo:0 TCPAbortOnLinger:0 TCPACKSkippedPAWS:0 TCPFromZeroWindowAdv:12 ArpFilter:0 PAWSActive:0 ListenDrops:0 TCPDirectCopyFromBacklog:2676634 TCPTSReorder:0 TCPSYNChallenge:14 TCPSACKDiscard:0 TCPDSACKIgnoredNoUndo:14 OutOfWindowIcmps:78 DelayedACKLost:3692 TCPPrequeued:16433466 TCPForwardRetrans:7 TCPDSACKRecv:1223 TCPAbortOnData:252 TCPHPHits:28653860 TCPDSACKOfoSent:3 TCPLostRetransmit:3 TCPTimeouts:10982 TCPRcvCollapsed:105548 TCPDSACKOfoRecv:0 TCPSpuriousRTOs:0 TCPOFOMerge:4 PruneCalled:551 TCPFACKReorder:0 TCPRenoFailures:0 TCPSackFailures:1 TCPFastRetrans:1012 TCPSlowStartRetrans:10 LockDroppedIcmps:0 TCPRenoRecoveryFail:0 TCPMemoryPressures:0 TCPMD5NotFound:0 TCPBacklogDrop:0 TCPHPHitsToUser:16387385 TCPRenoRecovery:0 TCPFullUndo:0 TCPLoss:309 TCPOFOQueue:209982 TCPWantZeroWindowAdv:7391 TCPMinTTLDrop:0 BusyPollRxPackets:0 SyncookiesSent:0 PAWSPassive:0 TCPSACKReneging:0 TCPLossFailures:1 TCPAbortOnClose:100 TCPAbortFailed:0 TCPToZeroWindowAdv:12 TWRecycled:0 TCPPrequeueDropped:0 TCPDSACKUndo:49 TCPChallengeACK:16 TCPSackRecoveryFail:0 TCPDSACKOldSent:3567 TCPACKSkippedFinWait2:0 TCPSackMerged:0 PAWSEstab:43 DelayedACKs:1697138 TCPHPAcks:39583900 TCPRenoReorder:0 TCPDSACKIgnoredOld:0 TCPSackShifted:0 TW:75713 TCPLossUndo:1115 TCPMD5Unexpected:0 TCPACKSkippedChallenge:0] <nil>
=========IpExt:=======
map[OutBcastPkts:0 InOctets:36367126169 OutBcastOctets:0 InNoRoutes:0 OutMcastPkts:0 InBcastPkts:123255987 OutOctets:14904074307 InMcastOctets:432 OutMcastOctets:0 InBcastOctets:12714123856 InTruncatedPkts:0 InMcastPkts:12] <nil>
=========ListeningPorts:=======
[3000 43168 57154 199 9000 6379 9999 80 111 22 631 5432 25] <nil>
=========Procs:=======
<Pid:1, Name:init, Cmdline:/sbin/init>
<Pid:1068, Name:auditd, Cmdline:auditd>
<Pid:1102, Name:rsyslogd, Cmdline:/sbin/rsyslogd-i/var/run/syslogd.pid-c5>
<Pid:1136, Name:irqbalance, Cmdline:irqbalance--pid=/var/run/irqbalance.pid>
<Pid:1176, Name:rpc.statd, Cmdline:rpc.statd>
<Pid:1210, Name:dbus-daemon, Cmdline:dbus-daemon--system>
<Pid:1232, Name:cupsd, Cmdline:cupsd-C/etc/cups/cupsd.conf>
<Pid:1264, Name:acpid, Cmdline:/usr/sbin/acpid>
<Pid:1276, Name:hald, Cmdline:hald>
<Pid:1277, Name:hald-runner, Cmdline:hald-runner>
<Pid:1309, Name:hald-addon-inpu, Cmdline:hald-addon-input: Listening on /dev/input/event2 /dev/input/event0>
and more...
==============ss -s===============
map[orphaned:0 synrecv:0 timewait:8 slabinfo.timewait:0 estab:5 closed:57] <nil>
=============uptime:==============
64 days, 20 hours, 16 mins
PASS
ok  	github.com/go-linux-toolkit/nux	0.409s
