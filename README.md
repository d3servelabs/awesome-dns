# README

## Keywords
DNS, NameServer, EPP(Extensible Provisioning Protocol), WHOIS, RDAP(Registration Data Access Protocol)

## NameServers
- BIND9 aka 9th version of BIND(Berkeley Internet Name Domain) a complete, highly portable implementation of the Domain Name System (DNS) protocol.
  - [source on GitLab(primary)](https://gitlab.isc.org/isc-projects/bind9), [source on Github(mirror)](https://github.com/isc-projects/bind9)
  - Maintainer: [Internet Systems Consortium (ISC)](https://www.isc.org/)

- CoreDNS: NameServer implementation in Golang
  - [Source](https://github.com/coredns/coredns)
  - Maintainer: [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/)

- PowerDNS
  - [Source](https://github.com/PowerDNS/pdns)
  - Maintainer: [PowerDNS.COM BV](https://www.powerdns.com/)

- Knot DNS
  - [Website](https://www.knot-dns.cz)
  - [Source Code](https://gitlab.nic.cz/knot/knot-dns)
  - Maintainer: [CZ.NIC](https://gitlab.nic.cz/knot/knot-dns)
  - Description: An authoritative-only DNS server designed for high performance with modern DNS features

- Unbound
  - [Website](https://www.nlnetlabs.nl/projects/unbound/about/)
  - [Source Code](https://github.com/NLnetLabs/unbound)
  - Maintainer: [NLnet Labs](https://github.com/NLnetLabs)
  - Description: A validating, recursive, and caching DNS resolver designed to be fast and lean

- TRust-DNS
  - [Source](https://github.com/bluejekyll/trust-dns)
  - Maintainer: Benjamin Fry (@bluejekyll)

- djbdns
  - [Source](https://cr.yp.to/djbdns.html)
  - Maintainer: D.J. Bernstein

- dnsmasq
  - [Website](http://www.thekelleys.org.uk/dnsmasq/doc.html)
  - [Source Code](http://thekelleys.org.uk/git/dnsmasq.git)
  - Maintainer: [Simon Kelley](http://thekelleys.org.uk/)
  - Description: Lightweight DNS forwarder and DHCP server for small networks

- MaraDNS
  - [Website](https://maradns.samiam.org)
  - [Source Code](https://github.com/samboy/MaraDNS)
  - Maintainer: [Sam Trenholme](https://github.com/samboy)
  - Description: Small, secure DNS server for both authoritative and recursive DNS services

## Extensible Provisioning Protocol (EPP)
- CentralNic PHP-EPP
  - [Source](https://github.com/centralnic/php-epp)
  - Maintainer: [CentralNic](https://www.centralnic.com/)

- EPP Self Test Tool by ICANN
  - [Source](https://github.com/icann/rst-epp-selftest-tool)
  - Maintainer: [ICANN](https://www.icann.org/)

- Net::EPP
  - [Source](https://github.com/gbxyz/perl-net-epp)
  - Maintainer: Gavin Brown (@gbxyz)

- Python EPP Client
  - [Source](https://github.com/cloudregistry/python-epp-client)
  - Maintainer: Cloud Registry

- Nomulus
  - [Website](https://nomulus.dev)
  - [Source Code](https://github.com/google/nomulus)
  - Maintainer: [Google](https://github.com/google)
  - Description: Cloud-based service for operating top-level domains (TLDs)

## WHOIS/RDAP Tools
- RDAP Reference Server
  - [Source](https://github.com/NICMx/rdap-server)
  - Maintainer: [NIC Mexico](https://www.nicmexico.mx/)

- phpWhois
  - [Source](https://github.com/phpWhois/phpWhois)
  - Maintainer: phpWhois Community

- whois-parser-go
  - [Source](https://github.com/likexian/whois-parser)
  - Maintainer: Li Kexian (@likexian)

- whois3
  - [Source](https://github.com/DannyCork/python-whois)
  - Maintainer: Danny Cork (@DannyCork)

- Who-Dat
  - [Source](https://github.com/Lissy93/who-dat)
  - Maintainer: [Alicia Sykes](https://github.com/Lissy93)
  - Description: Free, no-CORS WHOIS/RDAP lookup API

- OpenRDAP
  - [Source](https://github.com/openrdap/openrdap)
  - Maintainer: [OpenRDAP Contributors](https://github.com/openrdap)
  - Description: RDAP command-line client

- ICANN's RDAP Conformance Tool
  - [Source](https://github.com/icann/rdap-conformance-tool)
  - Maintainer: [ICANN](https://github.com/icann)
  - Description: Tool for verifying RDAP server implementation conformance

## Domain Management Tools
- opensrs-python
  - [Source](https://github.com/opensrs-py/opensrs)
  - Maintainer: OpenSRS Community

- Enom API Client
  - [Source](https://github.com/markcarver/enom-api)
  - Maintainer: Mark Carver (@markcarver)

## DNS Security
- DNSCrypt
  - [Source](https://github.com/DNSCrypt/dnscrypt-proxy)
  - Maintainer: Frank Denis (@jedisct1)

- DNSSec-Trigger
  - [Source](https://github.com/NLnetLabs/dnssec-trigger)
  - Maintainer: [NLnet Labs](https://nlnetlabs.nl/)

## DNS Testing & Monitoring
- DNSPerf
  - [Source](https://github.com/DNS-OARC/dnsperf)
  - Maintainer: [DNS-OARC](https://www.dns-oarc.net/)

- Zonemaster
  - [Source](https://github.com/zonemaster/zonemaster)
  - Maintainer: [IIS (Internet Foundation in Sweden)](https://internetstiftelsen.se/) and [AFNIC](https://www.afnic.fr/)
 
## Debugging and Analysis Tools

- **[DNSViz](https://dnsviz.net)**  
  A comprehensive DNS analysis and visualization tool to troubleshoot DNS configurations, focusing on DNSSEC validation.  
  - **Maintainer**: [Casey Deccio](https://github.com/deccio)  
  - **Source Code**: [GitHub](https://github.com/dnsviz/dnsviz)

- **[dnstracer](https://packages.debian.org/sid/dnstracer)**  
  A command-line tool to trace the path to the authoritative DNS server for a given domain name.  
  - **Maintainer**: Debian Community  
  - **Source Code**: [SourceForge](http://www.mavetju.org/unix/dnstracer.php)

- **[dnsping](https://github.com/klepner/dnsping)**  
  A simple utility to measure DNS latency and response times using `ping`-like behavior for DNS.  
  - **Maintainer**: [klepner](https://github.com/klepner)  
  - **Source Code**: [GitHub](https://github.com/klepner/dnsping)

- **[DNSCheck](https://dnscheck.iis.se)**  
  A web-based tool to test the delegation of a domain, including DNSSEC validation and operational checks.  
  - **Maintainer**: IIS.se (Internetstiftelsen i Sverige)  
  - **Source Code**: Private

- **[ZoneMaster](https://zonemaster.net)**  
  A tool for testing and validating DNS zones to detect misconfigurations and operational issues, including DNSSEC checks.  
  - **Maintainer**: [zonemaster](https://github.com/zonemaster)  
  - **Source Code**: [GitHub](https://github.com/zonemaster)

## DNS Libraries

- **[dnspython](https://www.dnspython.org)**  
  A Python library for working with DNS. It provides tools to perform DNS queries, updates, and DNSSEC validation.  
  - **Maintainer**: [dnspython](https://github.com/rthalley)  
  - **Source Code**: [GitHub](https://github.com/rthalley/dnspython)

- **[go-dns](https://github.com/miekg/dns)**  
  A DNS library for Go, supporting all DNS resource records, queries, and DNSSEC validation.  
  - **Maintainer**: [Miek Gieben](https://github.com/miekg)  
  - **Source Code**: [GitHub](https://github.com/miekg/dns)

- **[Node.js DNS](https://nodejs.org/api/dns.html)**  
  A DNS module included with Node.js, providing query and resolve functionality for DNS records.  
  - **Maintainer**: [Node.js Foundation](https://github.com/nodejs)  
  - **Source Code**: [GitHub](https://github.com/nodejs/node)

- **[ldns](https://www.nlnetlabs.nl/projects/ldns/)**  
  A C library for DNS and DNSSEC, designed for querying and manipulation of DNS zones.  
  - **Maintainer**: [NLnet Labs](https://github.com/NLnetLabs)  
  - **Source Code**: [GitHub](https://github.com/NLnetLabs/ldns)

- **[libunbound](https://nlnetlabs.nl/projects/unbound/about/)**  
  A DNS resolver library extracted from Unbound, useful for embedding DNS functionality into applications.  
  - **Maintainer**: [NLnet Labs](https://github.com/NLnetLabs)  
  - **Source Code**: [GitHub](https://github.com/NLnetLabs/unbound)

## Network Troubleshooting Tools with DNS Features

- **[Wireshark](https://www.wireshark.org)**  
  A network protocol analyzer that includes DNS decoding and debugging features.  
  - **Maintainer**: Wireshark Foundation  
  - **Source Code**: [GitLab](https://gitlab.com/wireshark/wireshark)

- **[Dig](https://linux.die.net/man/1/dig)**  
  A command-line utility to perform DNS lookups. It supports DNSSEC and advanced query options.  
  - **Maintainer**: ISC (BIND Project)  
  - **Source Code**: Part of [BIND](https://gitlab.isc.org/isc-projects/bind9)

- **[Drill](https://nlnetlabs.nl/projects/ldns/)**  
  A DNS query tool similar to `dig`, included with the `ldns` library, designed to simplify DNSSEC usage.  
  - **Maintainer**: [NLnet Labs](https://github.com/NLnetLabs)  
  - **Source Code**: [GitHub](https://github.com/NLnetLabs/ldns)
