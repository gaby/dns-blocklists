![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhagezi%2Fdns-blocklists&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
## DNS Blocklists - *For a better internet!*

### *Made with :heartbeat: for a safer and cleaner internet!*

### Table of Contents
1. [Overview](#overview)
2. [Multi light](#light) - *Hand brush: Light protection*
3. [Multi normal](#normal) - *Broom: All-round protection*
4. [Multi pro](#pro) - *Big broom: Extended protection*
5. [Multi pro++](#proplus) - *Sweeper: Maximum protection (more aggressive)*
6. [Multi ultimate](#ultimate) - *Ultimate Sweeper: Aggressive protection*
7. [Fake](#fake) - *Protects against internet scams, traps & fakes!*
8. [Threat Intelligence Feeds](#tif) - *Increases security significantly!*
9. [DoH/VPN/TOR/Proxy Bypass](#bypass) - *Prevent methods to bypass your DNS!*
10. [Safesearch not supported](#safesearch) - *Prevent the use of search engines that do not support safesearch!*
11. [Dynamic DNS](#dyndns) - *Protects against the malicious use of dynamic DNS services!*
12. [Badware Hoster](#hoster) - *Protects against the malicious use of free host services!*
13. [Most Abused TLDs](#tlds) - *Protects against known malicious Top Level Domains!*
14. [Personal](#personal) - *My manually maintained blacklist*
15. [Native Tracker](#native) - *Broadband tracker of devices, services and operating systems*
16. [Credits](#credits)
17. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - *Leave a star (top right)!*
18. [Recommendation](#recommendation)
19. [Online DNS Services](#dnsservices): [RethinkDNS](#rethinkdns) / [DNSforge](#dnsforge) / [DNSwarden](#dnswarden) / [AdGuardDNS](#adguarddns) / [ControlD](#controld) / [NextDNS](#nextdns)
20. [About](#about) / [Referral Domains](#referral) / [Support Me](#support)
21. [Sources/Statistics](usedsources.md)
22. [Raw data collection](https://github.com/hagezi/dns-data-collection) - *Data collection to generate the DNS blocklists*

### ***Multi - Cleans the Internet and protects your privacy!*** <a name="overview"></a>
*An all in one DNS blocklist in **various versions (light, normal, pro, pro++ and ultimate)**. It can be used as a stand alone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various blocklists](usedsources.md).*

#### ***Multi blocklist version and size overview:***
| Version | Hosts | Pro++ | Pro | Normal | Light | [Fake](#fake) | [TIF](#tif) | [Personal](#personal) | 
|:--------|---:|:---:|:------:|:-----:|:----:|:---:|:------:|:----------:|
| [Light](#light)             | 246365<br>111715     | |   |   | = | X | P | X |
| [Normal](#normal)       | 1080329<br>370221     | |   | = | X | X | P | X |
| [Pro](#pro)              | 1274100<br>449611         | | = | X | X | X | P | X |
| [Pro++](#proplus)    | 1387323<br>468134 | | ++ | X | X | X | P |  X |
| [Ultimate](#ultimate)    | 2120029<br>840014 | ++ | X | X | X | X | X |  X |
           
*X = contains the named lists in the column header*       
*P = partially contains the named list in the column header*       
*++ = more sources, more aggressive*
              
---
         
### ***Multi LIGHT*** - **Light protection** <a name="light"></a>
      
*Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics, some Malware and Fake.*
          
**Entries:** *246365 domains/hosts - 111715 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#light)         
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/light.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/light.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi NORMAL*** - **All-round protection** <a name="normal"></a>
      
*Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1080329 domains/hosts - 370221 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#multi)        
          
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS          |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/multi.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO*** - **Extended protection (Recommended)** <a name="pro"></a>
      
*Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1274100 domains/hosts - 449611 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#pro)        
           
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS             |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO++*** - **Maximum protection** <a name="proplus"></a>

*Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
*More aggressive version of the Multi PRO blocklist. It may contain few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *1387323 domains/hosts - 468134 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#proplus)    
                                                
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.plus.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.plus.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus.txt) | DNSCrypt, DNSCloak, YogaDNS, ...  |
                  
### ***Multi ULTIMATE*** - **Aggressive protection** <a name="ultimate"></a>

*Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking (+Referral), Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Coins and other "Crap".*
         
*Stricter version of the Multi PRO++ blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *2120029 domains/hosts - 840014 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#ultimate)    
                                                
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/ultimate.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/ultimate.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/ultimate.txt) | ~~AdGuard~~ (oversized, limited to 535000 rules!), AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/ultimate.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/ultimate.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/ultimate.txt) | DNSCrypt, DNSCloak, YogaDNS, ...  |
                         
**Expires:** *24 hours (update frequency)*

---

### ***Fake - Protects against internet scams, traps & fakes!*** <a name="fake"></a>
*An blocklist for blocking fake stores, -news, -science, -streaming, rip-offs, cost traps and co.*         
        
**Entries:** *10726 domains/hosts - 5563 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#fake)
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/fake.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/fake.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/fake.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Threat Intelligence Feeds - Increases security significantly!*** <a name="tif"></a>
*An blocklist for blocking malware, crypto, coin, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
**Entries:** *1086537 domains/hosts - 613011 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#tif)
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) | ~~AdGuard~~ (oversized, limited to 535000 rules!), AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *24 hours (update frequency)*

---

### ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!*** <a name="bypass"></a>

*Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS (TCP 853) outbound.*
          
***The block list exists in two versions:***

#### ***Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies*** <a name="bypass_all"></a>
       
**Entries:** *1429 domains/hosts - 1313 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh-vpn-proxy-bypass)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh-vpn-proxy-bypass.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh-vpn-proxy-bypass.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh-vpn-proxy-bypass.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

#### ***Encrypted DNS Servers only*** <a name="bypass_dns"></a>
       
**Entries:** *363 domains/hosts - 277 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!*** <a name="safesearch"></a>
*An blocklist for blocking search engines that do not support safesearch.*         
        
**Entries:** *146 domains/hosts - 143 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#nosafesearch)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/nosafesearch.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/nosafesearch.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/nosafesearch.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!*** <a name="dyndns"></a>
*An blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
**Entries:** *793 domains/hosts - 791 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#dyndns)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/dyndns.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/dyndns.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/dyndns.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/dyndns.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Badware Hoster blocking - Protects against the malicious use of free host services!*** <a name="hoster"></a>
*An blocklist for blocking known free hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.*         
                      
**Entries:** *51 domains/hosts - 50 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#hoster)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/hoster.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/hoster.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/hoster.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/hoster.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/hoster.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/hoster.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Most Abused TLDs - Protects against known malicious Top Level Domains!*** <a name="tlds"></a>
*An blocklist for blocking Top Most Abused Top Level Domains, merged from @Yokoffing, @DandelionSprout and SpamHaus.*         
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| AdGuard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt) | uBlock |

**Expires:** *Updated regularly*

---

### ***Personal - My manually maintained blacklist*** <a name="personal"></a>
*My personal blocklist, an extension for known blocklists. Blocks ads, trackers, native device trackers, badware and more. Not intended to be used as a standalone blocklist, it serves as a addition for other blocklists!*         
        
**Entries:** *20828 domains/hosts - 13985 compressed domains*
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/personal.txt) | PiHole, Blocky, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist, TechnitiumDNS | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/personal.txt) | PiHole, Blocky, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch, NetGuard, TechnitiumDNS              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/personal.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/personal.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/personal.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Native Tracker - Broadband tracker of devices, services and operating systems*** <a name="native"></a>
*Blocks native broadband tracker from devices, services and operating systems that track your activity.*         
                         
| Device/Service | Domains | Hosts | Adblock | Unbound | DNSMasq | Wildcard |
|:-------|:--------|:------|:--------|:--------|:--------|:---------|
| Apple (iOS, macOS, tvOS) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.apple.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple.txt) |
| Huawei (Devices) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.huawei.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.huawei.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.huawei.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.huawei.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.huawei.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.winoffice.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice.txt) |
| TikTok (Fingerprinting) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.tiktok.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.tiktok.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.tiktok.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.tiktok.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok.txt) |

**Expires:** *Updated regularly*

---

### ***Credits*** <a name="credits"></a>

**A huge thank you to the following list maintainers of the [sources that were partially used](usedsources.md), alphabetical order:**

*abpindo, abpvn, abuse.ch, adaway, adguardteam, adroitadorkhan, amnestytech, anti-ad, anudeepnd, assoechap, azorult-tracker.net, badmojr, barbblock, bigdargon, bkrucarci, blahdns, bongochong, botvrij.eu, cats-team, cbuijs, cert-agid.gov.it, cmiksche, craiu, d3ward, dandelionsprout, davidonzo, developerdan, digitalside.it, dogino, drsdavidsoft, durablenapkin, easylist, easylist-lithuania, easylist-thailand, elliotwutingfeng, fademind, fanboy, firebog.net, frogeye.fr, gioxx, guardicore, hblock, hexxiumcreations, hole.cert.pl, hoshsadiq, hpthreatresearch, hufilter, iam-py-test, ihgalis, infinitytec, jawz101, jdlingyu, jkrejcha, joewein.net, kargig, kees1958, kevinthomas0, kriskintel.com, laicure, laniksj, lassekongo83, latvian-list, list-kr, logroid, malware-filter, marco-acorte, matomo-org, metamask, migueldemoura, mitchellkrogza, molinero.dev, mvps.org, netlab.360, nextdns, nitrohorse, notonmyshift, notracking, oisd.nl, olbat, oneoffdallas, ookangzheng, paulgb, perflyst, phishing.army, piperun, piquark6046, polishfiltersteam, prodaft, quidsup, rescure.me, scafroglia93, shadowwhisperer, shallalist, shreyasminocha, sjhgvr, smed79, someonewhocares.org, stamparm, stanev.org, stevenblack, stopforumspam.com, symbuzzer, systemjargon, t145, th3m3, tiuxo, tomasko126, ublockorigin, ultimate-hosts, uniartisan, ut1, velesila, wally3k, yokoffing, yourduskquibbles, yous, yoyo.org, zerodot1, zoso.ro*

---

### ***Recommendation*** <a name="recommendation"></a>

*As a network-wide DNS blocker, I recommend using [Adguard Home](https://adguard.com), [Pi-Hole](https://pi-hole.net/), [TechnitiumDNS](https://technitium.com/dns/), [Blocky](https://github.com/0xERR0R/blocky) (advanced users) or [eBlocker](https://eblocker.org/).*
        
*DNS blocker offer a good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!         
Therefore, I* ***additionally*** *recommend the use of a browser content blocker such as [AdGuard](https://adguard.com) or [uBlock](https://ublockorigin.com) with the appropriate block lists (EasyList, AdGuard, uBlock, ...).*
                     
*Check out @yokoffing's [Recommended Filters for uBlock Origin](https://github.com/yokoffing/filterlists) for content blocker filter lists.*

---

### ***Online DNS Services*** <a name="dnsservices"></a>        

*If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then I recommend one of the following DNS services:*

### ***RethinkDNS - free*** <a name="rethinkdns"></a>

*In [RethinkDNS](https://rethinkdns.com) you can use my blocklists:*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS | Apple Mobileconfig |
|:-----------|:---------------|:-------------|:-------------------|
| Normal (PRO + TIF)  | `https://sky.rethinkdns.com/1:AAoACBAA` | `1-aafaacaqaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACBAA) and click on the red apple  |
| Aggressive (PRO plus + TIF) | `https://sky.rethinkdns.com/1:AAoACAgA` | `1-aafaacaiaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACAgA) and click on the red apple |
| Strikt (ULTIMATE) | `https://sky.rethinkdns.com/1:gAAAQA==` | `1-qaaaaqa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:gAAAQA==) and click on the red apple |
            
### ***DNSforge (Germany) - free*** <a name="dnsforge"></a>

*[DNSforge](https://dnsforge.de/) uses my light blocklist:*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS | DNS-over-QUIC |
|:-----------|:---------------|:-------------|:-------------------|
| Normal (LIGHT + more) | `https://dnsforge.de/dns-query` | `dnsforge.de` | `quic://dnsforge.de:853`  |
            
### ***DNSwarden - free*** <a name="dnswarden"></a>

*In [DNSwarden](https://dnswarden.com/customfilter.html) you can use my light, multi, pro, pro++ and tif list.*
            
### ***AdGuardDNS - limited free/paid*** <a name="adguarddns"></a>        
          
*My blocklist recommendations for [AdGuardDNS](https://adguard-dns.io) are:*          

| Profile    | Blocklists                                                                                    |
|:-----------|:----------------------------------------------------------------------------------------------|
| Pro | 1Hosts (Lite) + AdGuard DNS + [HaGeZi Personal Black & White](https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/main/filters/general/filter_34_HageziPersonal/filter.txt) + OISD full + NoTracking + StevenBlack |
           
*Black & White includes: [Personal](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt) + [Wildcard Rules](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal-wildcard-rules.txt) + [Fake](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt) + [Whitelist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/whitelist.txt) + [Whitelist Referral](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/whitelist-referral.txt)*

*You can also import my [server settings](https://github.com/hagezi/files/blob/main/adguarddns/hagezi_dns_server_settings.json), it contains - under the user rules - also my [RegEx rules](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal-regex.txt). Follow these [download instructions](https://www.howtogeek.com/devops/how-to-download-single-files-from-a-github-repository/) to save the file in the correct format!*
            
### ***ControlD - free/paid*** <a name="controld"></a>

*In [ControlD](https://controld.com/free-dns) you can use [my blocklists](https://kb.controld.com/en/3rd-party-filters):*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:-------------|
| Normal | `https://freedns.controld.com/x-hagezi-normal` | `x-hagezi-normal.freedns.controld.com` |
| Pro | `https://freedns.controld.com/x-hagezi-pro` | `x-hagezi-pro.freedns.controld.com` |
| Pro Plus | `https://freedns.controld.com/x-hagezi-proplus` | `x-hagezi-proplus.freedns.controld.com` |

### ***NextDNS - limited free/paid*** <a name="nextdns"></a>        

*In [NextDNS](https://nextdns.io/?from=jvpyfdfc) you can use my light, multi, pro, pro++ and ultimate list.*
               
*Check out @yokoffing [NextDNS Config Guide](https://github.com/yokoffing/NextDNS-Config) for recommended [NextDNS](https://nextdns.io/?from=jvpyfdfc) configuration settings.*

---

### ***About*** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

*The blocklists are based on [various sources](usedsources.md) and my own [blacklists](https://github.com/hagezi/dns-data-collection/tree/main/data). They were designed to avoid [false positive domains](whitelist.txt) as much as possible without losing effectiveness and efficiency. [Dead hosts](deadlist.txt) are regularly removed from the lists to keep them as small as possible. Made with :heartbeat: for a safer and cleaner internet.*         
*All lists were tested against 6000 websites from the Cisco Umbrella Top 1 million list. It was checked whether the pages load, the page content is displayed correctly, navigation links work, images load, videos start and much more.*                 
*They are updated and maintained daily.*
                        
*No, it's not just blocklists cobbled together from multiple sources. They have been optimized and extended to efficiently "clean the Internet" in all areas.                   
Test them and give [feedback](https://github.com/hagezi/dns-blocklists/discussions)!*
                
*Please [report false positive](https://github.com/hagezi/dns-blocklists/issues) domains.*

#### Referral Domains <a name="referral"></a>

*Affiliate and tracking links (referral domains) that appear frequently on offer web pages, in emails or in search results are allowed in my lists. These are mostly called only after manual clicking on a link and are not used to display advertising.
If these are blocked, the first hit links from search results, for example, no longer work.* 
          
*[Referral domains](whitelist-referral.txt) have been removed from all lists except from the ultimate list, only some of them were removed but not all!*
                  
*There are users who want to block referral domains anyway, so for each list I show the domains that were whitelisted because of referral. You can see them in the list of [used sources](usedsources.md) behind the link "whitelisted referral domains" per list.
This list can then be used as a blocklist to "undo" the whitelisting of referral domains.*
          
*Allowing referral domains in my lists is equivalent to the [NextDNS](https://nextdns.io/?from=jvpyfdfc) feature "Privacy > Allow Affiliate & Tracking Links".*
          
#### Support Me <a name="support"></a>

*I do not want any money donations. If you don't know what to do with your money, invest it in aid or similar projects, do something good with it. There is enough misery in the world.*             
*Accepting money donations would also be absolutely unfair to the maintainers of the sources used, that's not my way. Without the existing lists. these lists would be simply nothing.*
                                    
*If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!* 
                                
*Give feedback, show me your ideas, report false positve domains and help to keep the internet safe and clean.*               
*Help and cooperation of any kind is welcome!*
         
***Thanks for your support!***

---

### ***Keep the internet clean!*** - Join the Matrix: [#dnsblocklists:matrix.org](https://matrix.to/#/#hagezi:matrix.org)

---
