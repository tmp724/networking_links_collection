# networking links collection
Just a collection of networking-related news sites and tools i personally make use of. 

## Overview
- [list of lists](#list-of-lists)
- [general information and news](#general-information-and-news)
- [monitoring glasses and similar](#monitoring-glasses-and-similar)
- [programming tools](#programming-tools)
- [administration tools](#administration-tools)
- [books](#books)
- [conferences](#conferences)
- [shopping](#shopping)

## list of lists
- [Awesome list of awesome lists](https://github.com/sindresorhus/awesome)
- [Awesome pcap tools list](https://github.com/caesar0301/awesome-pcaptools)
- [Awesome network automation list](https://github.com/networktocode/awesome-network-automation)
- [Awesome SDN list](https://github.com/sdnds-tw/awesome-sdn): same with a focus on software defined networking
- [Awesome SNMP](https://github.com/eozer/awesome-snmp)
- [packet pushers list](https://packetpushers.net/blog/open-source-networking-projects)

## general information and news
### papers
- [Papers](https://arxiv.org/list/cs.NI/recent): I actually use the arXiv mobile phone app (available on F-Droid) to skim through papers and then download the important ones from here
### general news
- [sdnlab](https://www.sdnlab.com/): It is in Chinese, but it's the best SDN related news site i know of. My Chinese isn't much better than anyones, but with 
[the right dictionary](https://www.mdbg.net/chinese/dictionary#), it's actually not that hard the grasp the key points from a text full of english language buzzwords.
- [r/networking](https://www.reddit.com/r/networking/new/): vivid community of networking engineers
- [APNIC blog](https://blog.apnic.net/)
- [ipspace blog](https://blog.ipspace.net/)
- [Electronic Frontier Foundation](https://www.eff.org/)
### podcasts - all available on Antennapod
- [Software gone wild](https://www.ipspace.net/Podcast/Software_Gone_Wild/)
- [History of networking](https://rule11.tech/history-of-networking/)
- [Network collective](https://networkcollective.com/)
- [Packet pushers](https://packetpushers.net/series/podcasts/)
- [The internet report](https://www.thousandeyes.com/the-internet-report/)
- [Ping](https://blog.apnic.net/ping-podcast/)
### other communities than r/networking
- [Networkengineering on stackexchange](https://networkengineering.stackexchange.com/)
- [Serverfault](https://serverfault.com/)
### german language sites
- [heise](https://www.heise.de/): Tech reporting is good, note that the quality of their political reporting subsite Telepolis is questionable
- [netzpolitik.org](https://netzpolitik.org/)
- [Logbuch Netzpolitik](https://logbuch-netzpolitik.de/)
- [DLF: Computer und Kommunikation](https://www.deutschlandfunk.de/computer-und-kommunikation)
- [fachinformatiker.de](https://www.fachinformatiker.de/)
### linux mailing lists
- [XDP newbies](https://www.spinics.net/lists/xdp-newbies/)
- [netfilter](https://www.spinics.net/lists/netfilter/)
- [bpf](https://lore.kernel.org/bpf/)
- [netfilter-devel](https://www.spinics.net/lists/netfilter-devel/)
- [netdev](https://www.spinics.net/lists/netdev/)

## monitoring glasses and similar
- [Wondernetwork pings](https://wondernetwork.com/pings): global ping (RTT) statistics
- [Shadowserver](https://www.shadowserver.org/): Nonprofit organization that scans the internet for vulnerabilities and crafts reports with their findings. Any ASN or public IP space holder 
may subscribe to get customized reports.
- [APNIC Internet deployment resource explorer](https://rex.apnic.net/overview)
- [Hurricane Electric's fancy network map](https://he.net/3d-map/)
- [Hurricane Electric's free BGP online services](https://bgp.he.net/)
- [RIPE measurements atlas](https://atlas.ripe.net/)
- [Peeringdb](https://peeringdb.com/): who peers with whom and where
- [Chinafirewalltest](http://www.chinafirewalltest.com/): Test if a site is available from different locations within China. Do note that the Great Firewall does not only base on DNS and IP filtering and can be wonky.
- [Tor projects](https://2019.www.torproject.org/projects/projects.html.en)
- [IXPdb](https://ixpdb.euro-ix.net/en/)
- [Mutually Agreed Norms for Routing Security](https://www.manrs.org/)
- [Catalyst 3750 Switch Software Configuration Guide](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750/software/release/15-0_2_se/configuration/guide/scg3750.html): Exemplary switch configuration guide

## programming tools
### network emulation
- [a first list](https://www.brianlinkletter.com/2023/02/network-emulators-and-network-simulators-2023/)
- [mininet](http://mininet.org/)
- [gns3](https://docs.gns3.com/)
- [containerlab](https://containerlab.dev/)
- [netlab](https://netsim-tools.readthedocs.io/en/latest/index.html)
- [packet tracer](https://www.netacad.com/courses/packet-tracer)
- [eve-ng](https://www.eve-ng.net/)
- [netem](https://wiki.linuxfoundation.org/networking/netem)
- [CORE](https://coreemu.github.io/core/)
- [Imunes](http://imunes.net/)
### network simulation
- [ns-3](https://www.nsnam.org/)
- [omnet++](https://omnetpp.org/)
### traffic generation
- [a first list](http://traffic.comics.unina.it/software/ITG/link.php)
- [scapy](https://scapy.net/)
- [netcat](https://en.wikipedia.org/wiki/Netcat)
- [tcpreplay](http://tcpreplay.appneta.com/)
- [D-ITG](http://traffic.comics.unina.it/software/ITG/)
- [trex](trex-tgn.cisco.com/)
- [hping3](https://linux.die.net/man/8/hping3)
- [sendip](https://www.earth.li/projectpurple/progs/sendip.html)
- [nemesis](https://github.com/libnet/nemesis)
- [moongen](https://github.com/emmericp/MoonGen)
- [dpdk-packetgen](https://pktgen-dpdk.readthedocs.io/en/latest/)
### high speed packet processing languages and libraries
#### low-level APIs
- [P4](https://p4.org/)
- [eBPF](https://ebpf.io/), [Traffic control](https://man7.org/linux/man-pages/man8/tc-bpf.8.html) and [XDP](https://prototype-kernel.readthedocs.io/en/latest/networking/XDP/)
- [VPP](https://fd.io/vppproject/vpptech/) on [the Fast Data Project](https://fd.io/)
- [dpdk](https://www.dpdk.org/)
- [PF_RING](https://www.ntop.org/products/packet-capture/pf_ring/)
- [libpcap](https://www.tcpdump.org/pcap.html)
- [Socket programming](https://beej.us/guide/bgnet/)
#### higher-functionality wrappers
- [pcapplusplus](https://pcapplusplus.github.io/): C++ wrapper for packet capture engines such as libpcap, DPDK, PF_RING or raw sockets, a lot of good features
- [Rust's libpnet](https://docs.rs/pnet/0.27.2/pnet/)
- [GoPacket](https://pkg.go.dev/github.com/google/gopacket)
#### high-level networking libraries
- [libcurl](https://curl.se/libcurl/)
#### software routers/routing APIs
- [Berkeley Extensible Software Switch](http://span.cs.berkeley.edu/bess.html)
- [Click](https://github.com/kohler/click) and [FastClick](https://github.com/gkatsikas/fastclick): other Click derivatives exist
### packet capture/analysis
- [a first list](https://github.com/caesar0301/awesome-pcaptools)
- [a second list](https://github.com/paulveillard/cybersecurity-pcap-tools)
- [wireshark](https://www.wireshark.org/)
- [tools related to wireshark](https://wiki.wireshark.org/Tools)
- [tshark](https://tshark.dev/): This is really all you need. Do the tshark tutorials from sharkfest yesterday. Learn to use it in scripting, and never look back.  
- [arkime](https://github.com/arkime/arkime): large scale packet capture and search
- [tcpdump](https://www.tcpdump.org/): better performance than *shark
- [tcptrace](https://linux.die.net/man/1/tcptrace): summarizes pcap info
- [tcpslice](https://www.tcpdump.org/manpages/tcpslice.1.html): slice a pcap file
### troubleshooting tools
- ping
- iperf3
- dns troubleshooting: dig, digdns, intodns, mxtoolbox
- whois, nslookup
- mtr/traceroute
- pchar: like traceroute, but with per-hop bw measurements
- hping: like ping, but with tcp/udp transport protocols, get rtt for specific ports
- speedtest
- nsntrace: save packets from specific process using network namespaces
- w

## administration tools
### diagrams
- [draw.io offline](https://github.com/jgraph/drawio-desktop)
- [networkdiagram101](http://networkdiagram101.com/)
- [netdisco](http://netdisco.org/)
### network monitoring
- [pmacct](http://www.pmacct.net/): powerful UNIX passive network monitoring tool
- [nethogs](https://github.com/raboof/nethogs): bw per process
- [bwm-ng](https://github.com/vgropp/bwm-ng)
- [iftop](https://linux.die.net/man/8/iftop)
- [monitorix](https://www.monitorix.org/)
- [librenms](https://www.librenms.org/)
- [TIG stack](https://github.com/matisku/tig-stack)
- [netxms](https://www.netxms.org/)
- [vnstat](https://humdi.net/vnstat/)
- [ibmonitor](http://ibmonitor.sourceforge.net/)
- [bmon](https://github.com/tgraf/bmon)
- [PRTG](https://www.paessler.com/prtg)
- [net-snmp](http://www.net-snmp.org/)
### routing daemons
- [Free range routing](http://docs.frrouting.org/en/latest/overview.html#about-frr)
- Babel
- B.A.T.M.A.N. 
- BIRD 
- FRRouting 
- GNU Zebra 
- OpenBGPD 
- OpenOSPFD 
- Quagga 
- XORP
### UNIX-based routing distros
- VyOS
- PFsense
- OpenWRT
- Untangle
- freeBSD/OpenBSD
- more: Endian Floppyfw IPFire LEDE libreCMC OpenWrt VyOS Zeroshell
- and more: m0n0wall OPNsense pfSense
### Network configuration management
- [nornir](https://nornir.readthedocs.io/en/latest/)
- [paramiko](https://www.paramiko.org/)
- [netmiko](https://github.com/ktbyers/netmiko)
- [Oxidized](https://github.com/ytti/oxidized)
- [Rancid](https://shrubbery.net/rancid/)
- [Unimus](https://unimus.net/)
- [napalm](https://napalm.readthedocs.io/en/latest/)
- [netpalm](https://github.com/tbotnz/netpalm)
### network/asset/ip address management
- [Kuwaiba](https://www.kuwaiba.org/)
- [ralph](https://ralph.allegro.tech/)
- [racktables](http://www.racktables.org/)
- [GLPI](https://glpi-project.org/)
- [iTop](https://www.combodo.com/itop-193)
- [phpIPAM](https://phpipam.net/)
- [netbox](https://github.com/netbox-community/netbox)
### network login management/authorization
- [freeradius](https://freeradius.org/)
### linux network configuration tools
- [iproute2: ip, ss, lnstat, ctstat, nstat, routef, routel, rtstat, arpd, rtacct, rtmon, tc, tipc, bridge](https://wiki.linuxfoundation.org/networking/iproute2)
- [NetworkManager: nmcli, nmtui](https://wiki.gnome.org/Projects/NetworkManager)
- [netplan](https://www.linuxjournal.com/content/have-plan-netplan)
### miscellaneous
- [Various tools for networking, among other things](https://tools.kali.org/tools-listing)
- [Task-centered iproute2 user guide](https://www.baturin.org/docs/iproute2/)
- [ss](https://linux.die.net/man/8/ss)
- netstat
- devlink
- [qgis](https://www.qgis.org/en/site/): deployment planning outside
- [airmon-ng](https://www.aircrack-ng.org/doku.php?id=airmon-ng): wifi monitoring
- [tcptrace](https://sourceforge.net/projects/open-tcptrace/)
- nfpcapd, mergecap
- elastiflow
- hping3, sipcalc, aggregate, netperf, Observium, iptraf, pktstat, pmacct, cacti, grepcidr, snmp
- tc as a traffic shaping program
- traceroute - print route packets trace to network host
- nmap - scan remote ports/networks
- [zmap](https://github.com/zmap/zmap)
- netcat - test connectivity to specific ports
- ipcalc/sipcalc
- tcptraceroute
- arping
- aggregate
- iwlist
- ettercap
- nutty
- snmpwalk
- fping
- UnicornScan, Kismet Wireless
- virl, strace, nftables, bpfilter, netdisco
- bandwidth shaper: trickle
- iwconfig: configure wifi characteristics

## books
### theoretical basics
- Computer Networking: A Top-Down Approach
### administration
- Cisco Official Cert Guide for CCNA
- [CCNA workbook](http://www.freeccnaworkbook.com/workbooks/ccna)
- Network Warrior
- Unix and Linux System Administration Handbook
- Arista Warrior
- Practical Packet Analysis
### programming
- Hands-On Network Programming with C
- Network Algorithmics
- Linux Observability with BPF: Advanced Programming for Performance Analysis and Networking
### advanced design books
- Internet Routing Architectures
- MPLS in the SDN Era
### other advanced books
- Design, Measurement and Management of Large-Scale IP Networks
- High Performance Switches and Routers
- Recent Advances in Networking
- Analysis of Computer Networks
- Network Traffic Anomaly Detection and Prevention
- Fundamentals of Network Forensics 

## conferences
- [ACM Internet Measurement Conference](https://www.sigcomm.org/events/imc-conference)
- [ACM SIGCOMM](https://sigcomm.org/events/sigcomm-conference)
- [sharkfest](https://sharkfest.wireshark.org/sfus/)
- [netdev](https://netdevconf.info/)

## shopping
- [fs.com](https://www.fs.com/): cheap business switches, fiber etc.
- [monoprice](https://www.monoprice.com/)
