Recon
=====

GitMiner
----

Tool for advanced mining for content on Github 
https://github.com/danilovazb/GitMiner

![](https://camo.githubusercontent.com/75c5214c528fb4a250c7bb4899c677d28a25abb3/68747470733a2f2f332e62702e626c6f6773706f742e636f6d2f2d3141734e6d464b66736f412f56744c79764a46793257492f4141414141414141626e6f2f433778546278747a4f6f382f73313630302f6a6f6f6d6c6145582e706e67)

RobotsDisallowed
---

The RobotsDisallowed project is a harvest of the Disallowed directories from the robots.txt files of the world's top websites--specifically the Alexa 100K.
https://github.com/danielmiessler/RobotsDisallowed

netscreen-backdoor-scanner.py
---

A very simple SHODAN/Censys + Paramiko scanner to check for backdoored Internet-facing Juniper ScreenOS devices. 
https://github.com/juliocesarfort/netscreen-shodan-scanner

Tilt: Terminal Ip Lookup Tool
---

Tilt: Terminal ip lookup tool, is an easy and simple open source tool implemented in Python for ip/host passive reconnaissance. It's very handy for first reconnaissance approach and for host data retrieval.
https://github.com/AeonDave/tilt

![](https://raw.githubusercontent.com/AeonDave/tilt/master/doc/screenshot/tilt.png)

Sublist3r
---

Sublist3r is python tool that is designed to enumerate subdomains of websites using search engines.
https://github.com/aboul3la/Sublist3r

![](https://github.com/aboul3la/Sublist3r)

BLUTO
---

The target domain is queried for MX and NS records. Sub-domains are passively gathered via NetCraft. The target domain NS records are each queried for potential Zone Transfers. If none of them gives up their spinach, Bluto will brute force subdomains using parallel sub processing on the top 20000 of the 'The Alexa Top 1 Million subdomains'. NetCraft results are presented individually and are then compared to the brute force results, any duplications are removed and particularly interesting results are highlighted. 
https://github.com/RandomStorm/Bluto

Flashlight
---

Flashlight (Fener) provides services to scan network/ports and gather information rapidly on target networks. So Flashlight should be the choice to automate discovery step during a penetration test. In this article, usage of Flashligh application will be explained.
https://github.com/galkan/flashlight

Advanced Virtual Host BruteForcer (AVHBF)
---

 This tool try to bruteforce virtualhosts (HOST HTTP header) on your target server (web server or proxy balancer) and try to find something valid...

Why this tool is better than MSF module?

    Have a hybrid mode. When domain name is provided this tool try to find test.domain, dev.domain e.t.c... (taking subdomains from dictionary);
    Try to find .dev / .test / .local / .development / .beta / .int zones for current domain and for all subdomains while bruteforcing;
    "Smart" detect mechanism. Comparing not equal or not full text between non-exist domain and testing domain and not headers (nginx replies for non-exist domain 200 HTTP code by default config). You can set in percent what is the maximum difference in responses between non-exist and founded domain;
    Have a bigger than msf dictionary (include msf domains of course);
    Preventing false-positive answers;
    Not required msf :P
    Also try to bruteforce with HOST header from domains.txt file (standard msf feature).

https://github.com/BeLove/avhbf

Python API for dnsdumpster.com
---

https://github.com/PaulSec/API-dnsdumpster.com


