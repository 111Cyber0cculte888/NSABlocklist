NSABlocklist© project original created under the MIT license 2015-2018 by [CHEF-KOCH](https://github.com/CHEF-KOCH).

<p align="center">
  <img width="500" height="320" src="https://raw.githubusercontent.com/CHEF-KOCH/NSABlocklist/master/big-brother.jpg")">
</p>

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/FZeven)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/204394292519632897/widget.png)](https://discord.me/NVinside)

Description
------------

This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to _stop_ known NSA / GCHQ / C.I.A. or F.B.I. servers from being connecting to you without permission, of course the IPs also can be used for Bot Revolt or other tools. The list is not designed to block common malware, spyware/ads or anything that is already available on the net via a proper designed hosts for such special case. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


My list is original based on 2007 published Wikileaks documents and includes my own modifications from 2008, 2012, 2014 and 2015.


**Current Status**: 2,45 Mio files (not everything upload [yet]). I need to wait for GitHub approval in order to bulk upload bigger file set (100MB+ files).



This project includes
------------

* A '[HOSTS](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/HOSTS)' file that includes all Servers/DNS domains that are known to be involved in spying. The confirmation is given within the _Research_ link(s) at the bottom and with my own tests.
* An '[Super Ranges.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/Super%20Ranges.txt)' file which includes a list of known IP ranges that are compromised (be careful with that!).
* An '[LICENSE](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/LICENSE)' File to shows the MIT license.
* The '[README](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/README.md)' (this) file that includes the latest news, updates and explanations,...
* An '[problematic.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/problematic.txt)' file which includes DNS/PTRs that are possible problematic for you. 
* The 'Mail.txt' file in case you want to speak with me over encrypted email.
* An 'test' folder for IPv6 only domains. It also contains an 'html' folder for html formatted entries, an 'onion' folder for suspect or faked .onions and an 'Tor' folder for a quick guide how to run an non-exit relay in around 10 minutes.
* The 'References.txt' which contains relevant information about spying or additional topics which may related to reveal surveillance.
* Under the [release page](https://github.com/CHEF-KOCH/NSABlocklist/releases) you will find complete collections/dumps.
* Information on hardware based attacks. 


Any problems, questions or something wrong?
------------

* Feel free to open an issue ticket and I will look at it asap. - Pull Requests or ideas are always welcome!


Important Notice
------------

* A true list of compromised IPs would list the entire Internet, then on to the fuller range open mouth blabbering of blogs, email, chat rooms, texting, aided and abetted by the world's telecoms, postal services, and, most reliably, bedroom  murmurings.
* I do not accept donations in this project, I'm not doing this because I want $$money or hype, I'm doing this because I didn't found a proper list on the whole Internet and of course I want to share my knowledge for free. I always think that such information should be available for everyone on the world.
* The project has no political orientation, there will be no political leaks/information since this is not the main mission here.
* Please keep in mind that updates/encryption/knowledge is our _only real_ weapon against NSA and other agencies. The more you know the better you can build strategies and new systems to defeat mass surveillance.



Do you hate the NSA or other agencies?
------------

* I do not _hate_ the NSA or other agencies but I really don't like that everyone is automatically under the microscope (mass surveillance) and of course that there is no 'opt-out' or transparency except lies and more lies (and some excuses ...yeah, we are doing this because terrorism, go f$ck yourself with such statements!)
* Everyone have something to hide, passwords, private data, accounts, other meta-data, [...]



Known problems
------------

* An HOSTS file is no guarantee that if the NSA is already 'in your system/network' - to protect you - it's just to late.
* HOSTS files are no guarantee that NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilities on your system/router.
* HOSTS files can't protect against attacks directly in hardware, e.g. if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP/Domain/PTR record. If something was changed, feel free to open a pull request or send me an eMail.
* The GOSTS file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware/trojans can do this. Ensure that the file was marked as read-only and you're not logged in as administrator.
* Trace-route analysis especially on IPv4 networks are sometimes outdated (due the mass of requests).
* Be careful when blocking IP addresses, as IP addresses change frequently and can block people you don't intend to block.
* **NSA and other agencies can spy on traffic directly from supercomputers like infamous Echelon connected directly to some backbone without revealing any IP. This is an common problem, only strong and proper implemented encryption helps.**




Utils
------------

* [IPduh](https://ipduh.com/)
* [Robtex](https://www.robtex.com)
* [ZMap - The Internet Scanner](https://zmap.io/)
* [IP Address Details (ipinfo.io)](https://ipinfo.io/)
* tracert nsa.gov, see [how TRACERT command works](http://support.microsoft.com/?kbid=162326)
* [GlobalLeaks](https://globaleaks.org/) [Open-source anonymous whistleblowing software]
* [Freedom Box](http://freedomboxfoundation.org/learn/)
* [DenyHosts](http://denyhosts.sourceforge.net/)
* [Decode Your HTTP Traffic with Open Source Sysdig (sysdig.com)](https://sysdig.com/decode-your-http-traffic-with-sysdig/)
* [Courage Foundation](https://www.couragefound.org/)
* [shodan.io](https://www.shodan.io/)
* [censys.io](https://censys.io/)
* ... [others](http://www.rationallyparanoid.com/resources/)



Project History
------------

- [x] 04.06.2018 Add Anti-NSA project list.
- [x] 03.06.2018 Ipfilter update, Amzon list finally fully merged.
- [x] 06.05.2018 Readme updates, pdf section sorted, new PDF files updated. Project Status added, several other minor changes.
- [x] 05.05.2018 Ipfilter update.
- [x] 22.03.2018 Bitcoing (Blockchain) tracking documents (revealed by E.S.) added
- [x] 21.01.2018 Intel, AMD, Trusted Computing papers added among Vault 8 (Hive) source and documentation
- [x] 30.01.2016 Video section added, official guidance from nsa.gov added + an section for future tips
- [x] 15.09.2015 Separate the into his own References.txt file (list was also updated)
- [x] 04.09.2015 Added Ipv6 list, sort the test lists in his own cat.
- [x] 02.09.2015 Added 'Snowden documents compilations'
- [x] 19.08.2015 Added Backbone Providers and other involved services
- [x] 18.08.2015 More domains added 7821 in total
- [x] 16.08.2015 Removed some duplicates and added new domains, small Readme.md changes
- [x] 15.08.2015 Created a new start page chef-koch.github.io/NSABlocklist
- [x] 14.08.2015 Initial upload of the entire project and small Readme.md corrections



Snowden documents compilations
------------

* [The NSA files | The Guardian](http://www.theguardian.com/us-news/the-nsa-files)
* [Unofficial page to search E. Snowden leaked documents](https://search.edwardsnowden.com/)
* https://edwardsnowden.com/revelations/
* [Free Haven's Selected Papers in Anonymity](http://freehaven.net/anonbib/)
* [GitHub: nsa-observer project](https://github.com/nsa-observer/documents/tree/master/files/pdf)
* [ACLU NSA Documents Search](https://www.aclu.org/nsa-documents-search) [2013 Archive](https://www.aclu.org/nsa-documents-released-public-june-2013)
* [Free Snowden project](http://freesnowden.is/category/revealed-documents/index.html)
* [NSA Spying | Electronic Frontier Foundation](https://www.eff.org/de/nsa-spying)
* [Introducing a Compendium of the Released NSA Spying Documents by EFF](https://www.eff.org/deeplinks/2013/11/nsa-spying-primary-sources)
* [LeakSource](http://leaksource.wordpress.com/)
* [DEBORAH NATSIOS AND JOHN YOUNG BIBLIOGRAPHY](http://natsios-young.org/)
* [The NSA Toolbox](https://nsa.gov1.info/dni/)
* [Snowden Surveillance Archive](https://snowdenarchive.cjfe.org/greenstone/cgi-bin/library.cgi)
* [Snowden Archive Searchable](https://www.cjfe.org/snowden)



## Anti-NSA programs and networks

* [Hackers build a new Tor client designed to beat the NSA](https://www.dailydot.com/layer8/tor-astoria-timing-attack-client/)



Compromised ISP Providers
------------

* [AT&T helped to spy on an array of Internet traffic | The New York Times](http://www.nytimes.com/2015/08/16/us/politics/att-helped-nsa-spy-on-an-array-of-internet-traffic.html) & via [ProPublica](https://www.propublica.org/article/nsa-spying-relies-on-atts-extreme-willingness-to-help)
* Telecom US / T-Mobile 
* Vodafone
* Deutsche Telekom
* E-Plus / O2
* Alphabet (Goolgle) 'Project Fi alias T-Com' [Apr. 2015, needs a special Fi SIM for Nexus 6 XT1103 only (atm)]
* Digital Ocean, Inc.s
* TM Net, Internet Service Provider
* REN
* Verizon
* TNG
* Spint
* easybell
* L8NT
* Charter
* Suddenlink
* Sprint
* Unicom (GFW)
* CERNET (GFW)
* Embarq
* Telecom Egypt
* [Türk Telekom](https://www.btk.gov.tr/File/?path=ROOT%2F1%2FDocuments%2FPages%2FMarket_Data%2F2017_Q1_Eng.pdf)
* Belgacom
* [Tor has a community based good/bad ISP list](https://trac.torproject.org/projects/tor/wiki/doc/GoodBadISPs)



Blockchain monitoring
------------
* [OAKSTAR](https://en.wikipedia.org/wiki/OAKSTAR) (sub-project MONKEYROCKET)
* SHIFTINGSHADOW
* ORANGECRUSH
* YATCHSHOP
* ORANGEBLOSSOM
* SILVERZEPHYR
* BLUEZEPHYR
* COBALTFALCON


Videos
------------

* [USENIX Enigma 2016 - NSA TAO Chief on Disrupting Nation State Hackers](https://youtu.be/bDJb8WOJYdA)


Tips directly from nsa.gov
------------

* [NSA IA Guidance](https://www.nsa.gov/ia/mitigation_guidance/index.shtml) incl. several pdf's.


Backbone Providers
------------

* AT&T
* ATM S.A.
* Cable & Wireless
* Global Crossing
* Comcast
* Cox Communications
* Sprint Nextel 
* Level 3 / Level 2 / Level 1
* NTT Communications
* SAVVIS Communications
* Net By Net Holding LLC
* Verizon Communications
* ATM-Telekom
* [IBM](https://cryptome.org/2015/08/ibm-stop-tor.pdf)


VPN providers which are not secure or logging
------------

Spying:<br />
* [HotSpotShield](https://cdt.org/files/2017/08/FTC-CDT-VPN-complaint-8-7-17.pdf)
* [Hide My Ass](http://www.hacker10.com/internet-anonymity/hma-vpn-user-arrested-after-ip-handed-over-to-the-fbi/)
* ProXPN
* [PureVPN](https://www.justice.gov/opa/press-release/file/1001841/download)
* [EarthVPN](http://www.wipeyourdata.com/other-data-erasing/no-logs-earthvpn-user-arrested-after-police-finds-logs/)
* Betternet
* Slickvpn (keeps logs)
* [IPVanish](https://www.courtlistener.com/recap/gov.uscourts.insd.67065.2.0.pdf) (keeps logs)


Recommendation:<br />

* [ProtonVPN](https://protonvpn.com/)
* [Private Internet Access](https://www.privateinternetaccess.com) ([raid proof](https://torrentfreak.com/vpn-providers-no-logging-claims-tested-in-fbi-case-160312/)) + [h ere](https://torrentfreak.com/private-internet-access-no-logging-claims-proven-true-again-in-court-180606/)
* [ExpressVPN](https://www.expressvpn.com) ([raid proof](https://www.bestvpn.com/privacy-news/expressvpn-cannot-hand-over-logs/))
* [Perfect Privacy](https://www.perfect-privacy.com/)

See [here](https://thatoneprivacysite.net/vpn-comparison-chart/) for a more detailed comparison chart - keep in mind that this chart is not 100% correct but since everyone can submit findings it's more or less reliable. 



Other services providers + social media platforms
------------

* Facebook
* PushTalk / PalTalk
* MySpace
* [Google Inc. alias Alphabet](http://www.salon.com/2014/11/16/googles_secret_nsa_alliance_the_terrifying_deals_between_silicon_valley_and_the_security_state/)
* Amazon
* Microsoft 
* Apple
* Wikipedia, well it's for all
* Automattic, Inc
* LLC 
* Yahoo
* Twitter (FBI records)
* [Cookie based tracking](NSA uses advertisers’ cookies to track specific web browsers - report)


Government mass surveillance
------------

* [ECHELON](https://en.wikipedia.org/wiki/ECHELON) - International mass surveillance program.
* [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore)
* [PRISM](https://en.wikipedia.org/wiki/PRISM_(surveillance_program))
* [Carnivore](https://en.wikipedia.org/wiki/Carnivore_(software))
* [DISHFIRE](https://en.wikipedia.org/wiki/DISHFIRE)
* [STONEGHOST](https://en.wikipedia.org/wiki/STONEGHOST)
* [Tempora](https://en.wikipedia.org/wiki/Tempora)
* [Frenchelon](https://en.wikipedia.org/wiki/Frenchelon) Active-Passive-Exfilration (APEX)
* [FAIRVIEW](https://en.wikipedia.org/wiki/Fairview_(surveillance_program))
* [MYSTIC](https://en.wikipedia.org/wiki/MYSTIC_(surveillance_program))
* [Boundless Informant](https://en.wikipedia.org/wiki/Boundless_Informant)
* [BULLRUN](https://en.wikipedia.org/wiki/BULLRUN)
* [PINWALE](https://en.wikipedia.org/wiki/PINWALE)
* [Stingray](https://en.wikipedia.org/wiki/Stingray_phone_tracker)
* [TURMOIL / Turbulence](https://en.wikipedia.org/wiki/Turbulence_(NSA))
* [SIGINT Activity Designator (or SIGAD)](https://en.wikipedia.org/wiki/SIGINT_Activity_Designator)
* [MUSCULAR](https://en.wikipedia.org/wiki/Muscular_(surveillance_program))
* [STORMBREW](https://en.wikipedia.org/wiki/STORMBREW)
* Customer Proprietary Network Information / CPNI (metadata) - can be deactivated on Android 5.1+ and e.g. Fi networks


Discontinued
------------

* U.S. Terrorist Surveillance Program 
* Multistate Anti-Terrorism Information Exchange (MATRIX)
* ThinThread
* Trailblazer Project



European Union
------------

* Data Retention Directive
* INDECT
* Schengen Information System


Australia
------------ 

* Status: unclear, needs confirmation + evidence


China
------------

* Golden Shield Project
* Monitoring Bureau -> Status: unclear, needs confirmation + evidence
* Public Information Network Security -> Status: unclear, needs confirmation + evidence


France
------------

* Frenchelon 


Germany
------------

* Nachrichtendienstliches Informationssystem
* Project 6
* RAMPART-A with BND / NSA (needs more evidence)


India
------------

* Central Monitoring System (CMS)
* DRDO NETRA
* NATGRID


Russia
------------

* SORM
* Yarovaya Law 
* other systems rumored - Status: unclear, needs confirmation + evidence


Sweden
------------

* Titan traffic database
* X-Keyscore



Switzerland
------------

* Onyx


United Kingdom
------------

* Impact Nominal Index
* Interception Modernisation Programme
* Mastering the Internet (MTI)
* UK National DNA Database (NDNAD)
* Tempora
* Royal Concierge



United States
------------

* Boundless Informant (needs confirmation)
* BULLRUN
* Carnivore
* Comprehensive National Cybersecurity Initiative
* DCSNet
* Fairview
* Financial Crimes Enforcement Network
* ICREACH
* Magic Lantern (needs confirmation)
* Main Core
* MAINWAY
* Media monitoring services
* MUSCULAR
* MYSTIC
* Nationwide Suspicious Activity Reporting Initiative
* NSA ANT catalog
* PRISM
* Room 641A via AT&T 
* Sentry Eagle
* Special Collection Service
* Stellar Wind (code name)
* Tailored Access Operations
* Terrorist Finance Tracking Program
* Turbulence (NSA)
* US Intelligence Community (IC)
* Utah Data Center
* X-Keyscore


Possible Iran (unconfirmed + needs proof)
------------
* GhostNet
* Stuxnet



Spying programs
------------

* Traceroute "Packaged Goods" / "Treasure Map"
* VOIP: Hammerchant
* WEALTHYCLUSTER
* APEX
* COMSAT
* IRRITANT HORN (hijacks Google Play Store contained apps)
* HACIENDA


**Thanks goes to everyone which are fighting for www. security! Give spying no chance!**


