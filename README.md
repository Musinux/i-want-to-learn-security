# i-want-to-learn-security

As a teacher, I frequently get asked the following question: "I'd like to learn security, but where to start ?"

This document is a list of resources to help you learn stuff related to security.

It will be updated from time to time.

## Get some culture

After all, learning security is a matter of knowledge about what you want to secure. Knowing what exists may be a good starting point
Don't get my word on it: [Brian Krebs: Thinking of a cybersecurity career? Read This](https://krebsonsecurity.com/2020/07/thinking-of-a-cybersecurity-career-read-this/)
### Level: Introduction, general knowledge

* [Hacker News](https://news.ycombinator.com/best) (en): read news from the Hacker community (not only security, everything about IT, or not even related to IT). Learn the language, the keywords, the terms, the concepts, by being exposed regularly to it. If you don't understand a word, Google it.
* [Bleeping computer](https://www.bleepingcomputer.com/) (en): news site dedicated to security. Well explained, greatly sourced
* [Next Inpact](https://www.nextinpact.com/) (fr): great website about the digital world. Not related to security, more about IT.
* [Développez.com Sécurité](https://securite.developpez.com/) (fr): news about security issues, in french.
* [Computerphile (youtube channel)](https://www.youtube.com/channel/UC9-y-6csu5WGm29I7JiwpnA) (en): computer enthousiasts talking about IT, and security (crypto, etc.). Really well explained.

## Level: intermediate

* [C Internals (course)](http://www.avabodh.com/cin/cin.html): learn the basics of how C language is interpreted into intel x86 assembly. Useful for debugging C applications & reverse-engineering

### Level: high

* [Google Project Zero (blog)](https://googleprojectzero.blogspot.com/): highly technical blog articles about vulnerabilities found by the Project Zero team at Google. Hard to read, but well written and first-hand content (spectre, windows vulns, one-byte overflow leading to RCE,...)
* [LWN](https://lwn.net/): a webzine dedicated to the linux implementors community. It explains the latest functionnalities, or the core functionalities, like [Anatomy of a system call](https://lwn.net/Articles/604287/)
* [LiveOverflow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w): Youtube channel dedicated to the explanation of memory vulnerabilities

## Learn by doing

The best way to hack your way into security is to try hard.
These are websites with challenges, where the goal is to find a secret (named "flag"), hidden somewhere.
There are a lot of categories, you should try them all to see what appeals you the most and then focus on something to gain real knowledge of it.

WARNING: it may take you a lot of time (really a lot, like hours or days or even weeks to finish ONE challenge), but thats the most rewarding thing.

* [Root Me](https://root-me.org): french website, with categories like: web client, web server, network, cryptography, steganography, forensic, memory exploitation, script exploitation...
* [Hack The Box](https://www.hackthebox.eu/)

## Books

To have a deeper knowledge of the stuff you manipulate everyday, you must read the full length books that explain it all. If not, you're going to have only partial information, because a summary cannot go into that level of details.

### Level: introduction

* Histoire des codes secrets, by Simon Singh (fr): a must have to understand from where comes the cryptography
* Techniques de Hacking, by Jon Erikson (fr): covers the basics of system and network exploitation, c programming seen by the hacker point of view
* [The Art of UNIX Programming](https://www.arp242.net/the-art-of-unix-programming/) (en): book that explains the philosophy behind unix and linux. No code involved, only history, culture, impacts, practical aspects. Thoughtful

### Level: intermediate

* Modern Operating Systems, Andrew S. Tannenbaum, 4th ed. (en): know how Operating Systems work, with algorithms, definitions, architecture
* Computer Networks, Andrew S. Tannenbaum, 5th ed. (en): know how Networks work
* Applied Cryptography: Protocols, Algorithms, and Source Code in C, by Bruce Schneier

## Interesting Stuff

Other interesting stuff that may be of interest (Generally gathered from great Hacker News posts)

* [O(n^2), again, now in WMI (blog post, about performance debugging on Windows)](https://randomascii.wordpress.com/2019/12/08/on2-again-now-in-wmi/)
* [Use-after-free explanation (Live Overflow), from an exploit in iOS](https://www.youtube.com/watch?v=YV3jewkUJ54)
* [ToTok App analysis, chat app that sends info to a government (blog post)](https://objective-see.com/blog/blog_0x52.html)
* [Explanation of Smart Home devices light vulnerabilities (Smarter Everyday)](https://www.youtube.com/watch?v=ozIKwGt38LQ&t=329s)
* I also maintain a list about [Node.js interesting stuff](https://github.com/Musinux/links-about-node), if you want to have a look
