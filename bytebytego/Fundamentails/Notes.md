======Bytebybyte=====
#10+key memory and storages sytems:
                              types of memoery
	
    	memeory                                                     storages
	Ram               ROM                                                        - HD
	  -SRAM               -firmware            DRAM                              - SSD: SOlid state
           -CPU Cahces    -BIOS                  -SDRAM                          - USB Drive
		   -faster than DRAM                     -DDR  SDRAM  - DDR4(widely use) - SD Card
		                                                      - DDR5(widely use)
								                 -GDDR SDRAM(							   
													   								
SRAM: static RAM-special type of memory, high access or quick access types of memeory, CPU caches

DRAM: Dynamic->Slower,  and cheaper than SRAM
 
	
	Ram- random access memoery, volatatile, flexisble and fast access
	ROM: Not volatatile memoery, firmware, BIOS

in the market today are DDR variants, like DDR4, DDR4

GDDR6-> also worth mentioning, it is a specialized type of DRAM optimized for faster data transfer rate.
         which the GPU needs for its massive parallel processing.
		 GDDR6 is most widely useds
	
	
Esssential roles of ROM: Firsmware and BIOS	

Firsmware: type of s/w, controls how H/W devices communicate with each others

BIOS: Basic Input/Output system, is the first software your computer runs when you power it up.
it respinsible for starting your computer, initializing H/W componetes and hand over the control to the OS



HDD:Hard disk Drives, or HDD have been around for a long time.they store data on magnetic disks  and are known for their
large storage capacities at a low price.
SSD: Solid state drives, SSDs, use NAND based flash memory, provideing faster data access, reduced power comnsumptions and increase
durability compared to HDD,but come at a higher price.

NVMe or non volatile Memory Express is a high performcance interfaces for SSDs that connects directly to the CPU via PCIs lanes.
lower latelncy, and signifaclnyt faster data transfer rates compared to SATA-based SSDS.

SD cards: come in threed main physical sizes: SD, micro SD, and miniSD

	
	
====================
#How DNS works:
DNS, Domain name system is the backbone of the internet.

DNS is the internet Directory. It translates human-readable domain names such as 
google.com to machine-readable IP addresess.

                               Root nameservers
 com nameservers                        org nameservers                     edu nameservers
 yahoo.com                                      iete.org                    bharatx.edu
 nameservers

		----------
        |         |    -> www.google.com-> DNS resolver
		| Browser |   <- 91.34.20.40    <-------------|
		------------
		
		
		DNS have diffenrent hieracy and it serves different purpose
		
		When brower make DNS query, its asking a DNS resolver.

      This DNS resolver could be from our ISP,or populars DNS providers like cloudflare's 1.1.1.1 or google's 8.8.8.8

if DNS resolver does not have the answer in its caches. it finds the right authoritative nameserver and ask it.
the Authoritative nameserver is the one that holds the answer.


There are three main levesl of authoritative DNS servers.

1. They ar the root name servers, the Top level domain(or TLD) name servers,
2. Authoritative Nameservers

The root name servers store the IP addresses of the TLD name servers.
there are 13 logical root name servers:
01.a.root-servers.net     198.41.0.7
02.b.root-servers.net     8.8.0.4
03.c.root-servers.net     18.1.0.8
04.d.root-servers.net     38.91.0.9
05.e.root-servers.net     298.31.0.8
06.f.root-servers.net     198.21.0.2
07.g.root-servers.net     49.91.0.8
08.h.root-servers.net     98.1.0.9
09.i.root-servers.net     198.61.0.3	  
10.j.root-servers.net     78.491.0.7
11.k.root-servers.net     28.451.0.5
12.l.root-servers.net     1.9.401.0.2
13.m.root-servers.net     200.4.0.40
Each root name server has a single IP addresses assigned to it.
