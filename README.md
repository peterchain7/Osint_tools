# Tools

This repository is for OSINT

## List of Best Hacker Friendly Search Engines and sources of OSINT.

[Shodan](https://www.shodan.io/)

- [x] locate specific device on the internet. Eg

```bash 
i. Webcams
ii. Water treatment facilities
iii. Yachts
iv. Medical devices
v.  Traffic lights
vi. wind turbines,
vii. license plate readers, 
viii. smart TVs, refrigerators, and anything else you can think of.
```

[GreyNoise Viewer](https://www.greynoise.io/)

- [x]


[PublicWWW - Heaven source code](https://publicwww.com/)

- [x] Can search web page source code for HTML,javascript,CSS and plaintext and retrive a list  of URLs that have it.


[Wigle](https://wigle.net/)

- [x] Locate remote enterprises

[censys.io](https://censys.io/)
- [x] information about attacks

[https://viz.greynoise.io/](https://viz.greynoise.io/)

- [x] show us information about attacks, malicious websites or faults it finds.

[https://www.abuseipdb.com/](https://www.abuseipdb.com/)

- [x] Helps in SOC investigation.

[Zoomeye](https://www.zoomeye.org/)

- [x] gather infromation about the search queries

[Hunter.io](https://hunter.io/)

- [x] Email Hunter, Is an email search application that helps marketers find contact information for  domain 🌝.

[OSINT framework](https://osintframework.com/)

- [x] Cybersecurity framework that provides a variet of OSINT technoologies too help you with intel and data collection.

- [https://subdomainfinder.c99.nl/index.php](https://subdomainfinder.c99.nl/index.php)

- Intelligence tools to find subdomains

[https://github.com/sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)

- Hunt down social media accounts by username across social networks.
[https://github.com/x0rz/tweets_analyzer](https://github.com/x0rz/tweets_analyzer)

- Simple Twitter Profile Analyzer:
- Usage:

```bash
python tweets_analyzer.py -n miounster --limit 3000 -s
```

[https://www.osintcombine.com/post/foursquare-the-hidden-osint-gem](https://www.osintcombine.com/post/foursquare-the-hidden-osint-gem)

- It is often overlooked as an OSINT source because it is all about business locations, reviews and identifying what is around you at a given time (when using the app). However this platform has 60 million registered users, and 50 million active users every month as of 2019. That's significant and the platform is alive and well.

[Using dig command](https://linuxize.com/post/how-to-use-dig-command-to-query-dns-in-linux/)

- `Testing SPF, DKIM, and DMARC Using Gmail`

```bash
`Sender Policy Framework`
Sender Policy Framework (SPF) Definition:
SPF is a form of email authentication that defines a process to validate an email message that has been sent from an authorized mail server in order to detect forgery and to prevent spam.
```

```bash
`DKIM (Domain Keys Identified Mail)` 
is an email authentication technique that allows the receiver to check that an email was indeed sent and authorized by the owner of that domain. This is done by giving the email a digital signature.
```

```bash
`standard email authentication method`
DMARC is a standard email authentication method. DMARC helps mail administrators prevent hackers and other attackers from spoofing their organization and domain. Spoofing is a type of attack in which the From address of an email message is forged.
```
[Network tools](https://mxtoolbox.com/NetworkTools.aspx)

- Network tools to test various network services and find some information that woulld be usefull for `penetration testing` and  `Open source Intelligence`


#### Testing SPF, DKIM, and DMARC Using Gmail with `dig`.

```bash
└─$ dig TXT secure-startup.com _dmarc.secure-startup.com

; <<>> DiG 9.18.4-2-Debian <<>> TXT secure-startup.com _dmarc.secure-startup.com
;; global options: +cmd

;; ANSWER SECTION:
secure-startup.com.	1800	IN	TXT	"v=spf1 a mx ?all - HTB{RIP_SPF_Always_2nd"

;; AUTHORITY SECTION:
secure-startup.com.	2225	IN	NS	ns69.domaincontrol.com.
secure-startup.com.	2225	IN	NS	ns70.domaincontrol.com.

;; ADDITIONAL SECTION:
ns69.domaincontrol.com.	103648	IN	A	97.74.104.45
ns70.domaincontrol.com.	103648	IN	AAAA	2603:5:2284::2d

;; ANSWER SECTION:
_dmarc.secure-startup.com. 1800	IN	TXT	"v=DMARC1;p=none;_F1ddl3_2_DMARC}"

;; AUTHORITY SECTION:
secure-startup.com.	2210	IN	NS	ns70.domaincontrol.com.
secure-startup.com.	2210	IN	NS	ns69.domaincontrol.com.
```


[pipl](https://pipl.com/)

```bash
Pipl is a simple website for 'people search,' used by government organizations, financial and security institutions, and media organizations worldwide. It interacts with public and available database. It obtains crucial data from public sources and the deep web to offer concrete data about individuals, competencies, social networks, segments, and contacts associated with a specific person.
```

[haveibeenpwned](https://haveibeenpwned.com/).

- A web site that allows users to search for and determine if the password for an email address has been compromisse due to data breaches. service generated from known leak sites

[https://ivre.rocks/](https://ivre.rocks/)

```bash
IVRE is an open-source network recon platform that uses Web interfaces, CLI tools, and a Python API to evaluate Nmap, Masscan, ZGrabd2, and Zeek/Bro findings. It collects data using well-known open-source tools (Nmap, Masscan, ZGrab2, ZDNS, and Zeek), saves it in a database (MongoDB is the suggested backend), and provides analysis tools.

IVRE include tools for executing Nmap against targets such as an organization or a range of locations, an entire country, a specific AS, or the full related IPv4 address space. Use your output results to differentiate between comparable hosts and other situations. Similarly, IVRE looks to be more suited to hackers, coders, or potential pen analyzers than the Shodan search engine, though hackers may use all three.
```


## Other OSINT tools

- [x] [https://www.osinttechniques.com/osint-tools.html](https://www.osinttechniques.com/osint-tools.html)
- Collection of OSINT tools

- [x] [https://www.nexvisionlab.com/](https://www.nexvisionlab.com/)
- real-time intelligence from the Whole Web (Clear Web, Dark Web, and Social Media)

- [https://sociallinks.io/](https://sociallinks.io/)
-  Extract, analyse and visualise data from open sources including social media, messengers, blockchains, and the Dark Web.

- [Maltego](https://www.paterva.com/index.php)
- This open-source intelligence tool is mainly used to perform a significant exploration against various targets with the help of several in-built transforms (and also provides the capability to write custom ones)

- [TheHarvester](https://github.com/laramies/theHarvester)
-  Is an amazing tool for finding emails, subdomains, IPs, etc. from various public data.
Eg.
```bash
python theHarvester.py -d geekflare.com -v -b dnsdumpster
```
- [SpiderFoot](https://www.spiderfoot.net/)
- It has automatically enabled us to use queries over 100+ OSINT sources to grab the intelligence on emails, names, IP addresses, domain names, etc. It collects an extensive range of information about a target, such as netblocks, e-mails, web servers, and many more. Using Spiderfoot, you may able to target as per your requirement because it will collect the data by understanding how they are related to each other

- [Creepy](https://www.geocreepy.com/)
- is an open-source Geolocation intelligence tool. It collects information about Geolocation by using various social networking platforms and image hosting services that are already published somewhere else.

- [http://technisette.com](http://technisette.com)

- An OSINT project. sources can be found at [https://start.me/p/ZME8nR/osint](https://start.me/p/ZME8nR/osint)

- [Way back machine](https://web.archive.org/)

- Shows how the site was. Help to show the archived data about about a website.

##### Advanced facebook,instagram, search 

- [https://whopostedwhat.com/](https://whopostedwhat.com/)
- help to advance searching in facebook

- [https://plessas.net/facebookmatrix](https://plessas.net/facebookmatrix)
- when your target donot have a facebook profie you can still find him though friends closely to him or her. posts,photos n.k

- [https://www.searchmy.bio/](https://www.searchmy.bio/)
-  Find some information in instagram bio's


#### Validate E-mail address.

- [x] [https://verifalia.com/validate-email](https://verifalia.com/validate-email)
- [x] [https://tools.emailhippo.com](https://tools.emailhippo.com)

## Google is Not the Only Search Engine:

- [x] [Bing.com](http://bing.com/)

 - By Microsoft is the second largest search engine. It also has advanced search features

- [x] [Duckduckgo.com](https://duckduckgo.com/)

- Search engine used by Tor browser because of it's anonymity. 

- [x] [Baidu.com](https://www.baidu.com/) 
 - is a large Chinese search engine.

- [x] [Yandex.com](https://yandex.com/)
-  is a large Russian search engine.


####  REFERENCE

- [x] [https://aofirs.org/articles/hacker-search-engines](https://aofirs.org/articles/hacker-search-engines)


## Links

- [x] [https://inteltechniques.com/tools/Images.html](https://inteltechniques.com/tools/Images.html)
- [x] [https://techcrunch.com/2017/03/09/names-and-definitions-of-leaked-cia-hacking-tools/](https://techcrunch.com/2017/03/09/names-and-definitions-of-leaked-cia-hacking-tools/)
- [x] [https://wikileaks.org/+-Intelligence-+.html](https://wikileaks.org/+-Intelligence-+.html)
- [x] [https://andreafortuna.org/2017/03/16/my-personal-list-of-osint-sources-search-tools/](https://andreafortuna.org/2017/03/16/my-personal-list-of-osint-sources-search-tools/)
- [x] [https://www.sans.org/blog/list-of-resource-links-from-open-source-intelligence-summit-2021/](https://www.sans.org/blog/list-of-resource-links-from-open-source-intelligence-summit-2021/)


## Images

1. Surface web, Deep web and Dark web

![Surface web, deep web, dark web](/images/webs.jpg)