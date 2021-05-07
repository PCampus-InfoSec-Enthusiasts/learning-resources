# RESOURCES

# Contents:
* [Linux](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#linux)
* [Web sec](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#web-sec)
* [Cryptography](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#cryptography)
* [Steganography](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#steganography)
* [OSINT](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#osint)
* [Binary exploitation](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#binary-exploitation)
* [Networking](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#networking)
* [Cloud sec](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#cloud-sec)
* [Windows](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#windows)
* [Bug bounty](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#windows)
* [General hacking resources](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#general-hacking-resources)
* [Other cool contents](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#other-cool-contents)

---

## Linux:
* Collection of Beginner to Advanced level resources: <br>https://www.notion.so/Linux-Resources-ad018e0a007347ab9d039cc2d29c3bf4

* Linux exercises[lab]:<br>https://overthewire.org/wargames/natas/

* Linux challenges: <br>https://tryhackme.com/room/zthlinux

* Introduction to tmux: <br>https://www.youtube.com/watch?v=Lqehvpe_djs

* Learn find command in linux : I have tried to cover most of the flags used in `find` command in incremental way.: <br>https://shishirsubedi.com.np/linux/find/

* Bash Pitfalls: <br>https://mywiki.wooledge.org/BashPitfalls
	
* Iptables:
  * Part 1 : https://www.thegeekstuff.com/2011/01/iptables-fundamentals/
  * Part 2 : https://www.thegeekstuff.com/2011/02/iptables-add-rule/
  * Part 3 : https://www.thegeekstuff.com/2011/03/iptables-inbound-and-outbound-rules/

* Nmap cheat sheet: <br>https://shishirsubedi.com.np/network/nmap/

* Port Forwarding using chisel:

 ```
 Local box : sudo ./chisel server -p 1880 --reverse
 on Remote box : ./chisel client 10.6.31.213:1880 R:4506:127.0.0.1:4506 
 ```

* Bypassing IDS for network scanning using nmap - Part 1: <br>https://redcodelabs.io/blog/exploring_nmap_1.html

* FFUF — Everything You Need To Know: <br>https://www.cybersecnerds.com/ffuf-everything-you-need-to-know/

* CURL — Everything You Need To Know: <br>https://www.cybersecnerds.com/curl-everything-you-need-to-know/


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Web sec:
* CS253 - Web Security: <br>https://web.stanford.edu/class/cs253/

* Exces XSS: A comprehensive tutorial on cross-site-scripting: <br>https://excess-xss.com/

* Deserialization Attacks on Java:
  * https://foxglovesecurity.com/2015/11/06/what-do-weblogic-websphere-jboss-jenkins-opennms-and-your-application-have-in-common-this-vulnerability/
  * https://medium.com/swlh/hacking-java-deserialization-7625c8450334 

* IPPSEC's Videos on PHP deserialization:
  * https://www.youtube.com/watch?v=fHZKSCMWqF4
  * https://www.youtube.com/watch?v=HaW15aMzBUM&t=50

* Good Resource for Manual SQL injection: <br>https://sqlwiki.netspi.com/

* Master the art of Cross Site Scripting: <br>https://brutelogic.com.br/blog/

* List of XSS payloads: <br>http://www.xss-payloads.com

* XXE 3 hour workshop: <br>https://gosecure.github.io/xxe-workshop/


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Cryptography:
* Multiple crypto challenges:<br>https://cryptopals.com/

* Cryptography: <br>https://www.notion.so/Cryptography-4d846b9a6af44b9f995418d60f641a6a

* Quickly encoding, decoding, encryption, decryption, hashing:<br>https://medium.com/swlh/quickly-encoding-decoding-encryption-decryption-hashing-318f7b3ea11e

* CS255 stanford "Introduction to cryptography": <br>https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/

* Hamming codes part 1 ...: <br>https://www.youtube.com/watch?v=X8jsijhllIA

* Hamming codes part 2 ...: <br>https://www.youtube.com/watch?v=b3NxrZOu_CE


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Steganography:
* Steganography tools: <br>https://github.com/DominicBreuker/stego-toolkit

* Steganographic Decoder: <br>https://futureboy.us/stegano/decinput.html

* Steganographic Encoder: <br>https://futureboy.us/stegano/encinput.html

* Steganography Online[encode/decode]: <br>https://stylesuxx.github.io/steganography/

* Really good article on Steganography: <br>https://hackersonlineclub.com/steganography/

* Cheatsheet - Steganography 101: <br>https://pequalsnp-team.github.io/cheatsheet/steganography-101


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## OSINT:
* Collection of OSINT Tools: <br>https://osintframework.com/

* bellingcat - the home of online investigations: <br>https://www.bellingcat.com/

* Osint Curious OSINT Resource List: <br>https://docs.google.com/document/d/14li22wAG2Wh2y0UhgBjbqEvZJCDsNZY8vpUAJ_jJ5X8/edit#heading=h.5mxacuke75jk


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Binary exploitation:
* Cool playlist for introduction : <br>https://www.youtube.com/watch?v=iyAyN3GFM7A

* Nightmare: An intro to binary exploitation/reverse engineering course based around CTF challenges: <br>https://guyinatuxedo.github.io/

* Exploit education: <br>https://exploit.education/


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Networking:
* Networking tutorial: <br>https://www.youtube.com/playlist?list=PLowKtXNTBypH19whXTVoG3oKSuOcw_XeW


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Cloud sec:
* Hacking the Cloud: The Encyclopedia for Offensive Security in the Cloud: <br>https://hackingthe.cloud/


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Windows:
* Special privileges on windows and exploiting them to get a system shell: <br>https://2018.romhack.io/slides/RomHack%202018%20-%20Andrea%20Pierini%20-%20whoami%20priv%20-%20show%20me%20your%20Windows%20privileges%20and%20I%20will%20lead%20you%20to%20SYSTEM.pdf

* Playlist for Basics of Active Directory: <br>https://www.youtube.com/playlist?list=PL3B8L-z5QU-Yw80HOGXXUASBfv_K1WwO5


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Bug bounty:
* Awesome Bugbounty Writeups: <br>https://github.com/devanshbatham/Awesome-Bugbounty-Writeups

* All the DOD Sites Listed in Bug Programs, Open-Scope, Automation lai sajilo hola :joy: [dod-sites.txt](./dod-sites.txt)

* How to Get Into Bug Bounties - Part 01: <br>https://0xprial.com/how-to-get-into-bug-bounties-part-01/


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## General hacking resources:
* hacking-resources: <br>https://gist.github.com/selftaught/23943c6f04e59171cf11d625f220bf24

* A course bundle of ethical hacking lessons: <br>https://drive.google.com/drive/folders/0B39jsuKsL3G8VFcxaG1jQ3BDQjg

* Yet another bundle of ethical hacking lessons/courses, but larger collection than the previous: <br>https://drive.google.com/drive/folders/1Se-U7xWI7-cK8Ez4hyFax5DCaZVAxzjU


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

---

## Other cool contents:
* https://gtfobins.github.io/gtfobins/tar/

* If you don't understand what some linux command's do with all the flags and pipes added, this site explains it pretty nicely: <br>https://explainshell.com/

* This repo has a lot of resources that may be required during a ctf challenge: <br>https://github.com/JohnHammond/ctf-katana

* OSCP notes: <br>https://hackanythingfor.blogspot.com/2020/08/oscp-personal-notes.html?m=1

* InfoSec Write-ups: <br>https://medium.com/bugbountywriteup

* Reverse-shell: <br>https://resources.infosecinstitute.com/icmp-reverse-shell/#gref

* Linux | Windows Privilege Escalation Labs/Workshops/Slides: <br>https://github.com/sagishahar/lpeworkshop

* This is an online sqlmap powered tool that allows you to perform a fast SQLi check. Link: <br>https://suip.biz/?act=sqlmap

* Why you can't get a root shell with a script with suid bit set and owned by root? <br>https://www.youtube.com/watch?v=-wGtxJ8opa8

* Privilege Escalation with LXD group: <br>https://www.hackingarticles.in/lxd-privilege-escalation/

* Privilage escalation to the host from docker if docker.socks is mounted on your container: <br>https://thearkcon.com/static/wu/inception.pdf

* https://pop-eax.github.io/blog/posts/ctf-writeup/web/2020/08/01/h-cktivitycon-ctf-specialorder/

* https://captf.com/practice-ctf/

* Simple VU Capture The Flag lab: <br>https://kernal.eu/posts/vuctflab/

* Brute XSS - Master the art of Cross Site Scripting.: <br>https://brutelogic.com.br/

* Behind the scenes of HTTPS: How does HTTPS actually work?: <br>https://robertheaton.com/2014/03/27/how-does-https-actually-work/

* What is ctf and how to get started: <br>https://dev.to/atan/what-is-ctf-and-how-to-get-started-3f04

* CTF challenges: <br>https://ctflearn.com/challenge/1/browse

* How I Hacked Facebook Again! Unauthenticated RCE on MobileIron MDM: <br>https://blog.orange.tw/2020/09/how-i-hacked-facebook-again-mobileiron-mdm-rce.html

* From the person who is the owner of a  popular repo in github "Seclists". It will make you feel bad for sure, but worth reading:
        * How to Build a Cybersecurity Career [2019 Update] | Daniel Miessler: <br>https://danielmiessler.com/blog/build-successful-infosec-career/

* So You Want to Be a Hacker: 2021 Edition | By TheCyberMentor: <br>https://tcm-sec.com/so-you-want-to-be-a-hacker-2021-edition/

* How to Be an Ethical Hacker in 2021 | The Cyber Mentor: <br>https://www.youtube.com/watch?v=mdsChhW056A

* Bugs found in Facebook, writeups from @samm0uda: <br>https://ysamm.com/

* Ex-NSA hacker tells us how to get into hacking!: <br>https://www.youtube.com/watch?v=SFbV7sTSAlA

* A Collection of Tools | Rawsec's CyberSecurity Inventory: <br>https://inventory.raw.pm/

* The Confessions of the Hacker Who Saved the Internet: <br>https://www.wired.com/story/confessions-marcus-hutchins-hacker-who-saved-the-internet/

* We Hacked Apple for 3 Months: Here’s What We Found: <br>https://samcurry.net/hacking-apple/

* Collection of Github Repositories for 𝗛𝗮𝗰𝗸𝗶𝗻𝗴 / 𝗣𝗲𝗻𝘁𝗲𝘀𝘁𝗶𝗻𝗴 / 𝗕𝘂𝗴 𝗕𝗼𝘂𝗻𝘁𝘆.
    1. Book of Secret Knowledge = https://github.com/trimstray/the-book-of-secret-knowledge
    2. Awesome Hacking = https://github.com/Hack-with-Github/Awesome-Hacking
    3. Awesome Bug Bounty = https://github.com/djadmin/awesome-bug-bounty
    4. Awesome Penetration Testing = https://github.com/wtsxDev/Penetration-Testing
    5. Awesome Web Hacking = https://github.com/infoslack/awesome-web-hacking
    6. Awesome Hacking Resources = https://github.com/vitalysim/Awesome-Hacking-Resources
    7. Awesome Pentest = https://github.com/enaqx/awesome-pentest
    8. Awesome Red Teaming = https://github.com/yeyintminthuhtut/Awesome-Red-Teaming
    9. Awesome Web Security = https://github.com/qazbnm456/awesome-web-security
    10. Penetration Test Guide based on OWASP = https://github.com/Voorivex/pentest-guide
    11. Pentest Compilation = https://github.com/adon90/pentest_compilation
    12. Infosec Reference = https://github.com/rmusser01/Infosec_Reference

* iamrajivd/pentest: <br>https://github.com/iamrajivd/pentest

* CyberDefenders: Blue Team CTF Challenges: <br>https://cyberdefenders.org/labs/

* Free Tools | By SANS' Faculty: <br>https://www.sans.org/img/free-faculty-tools.pdf


*[Click here to go to top :arrow_up:](https://github.com/PCampus-InfoSec-Enthusiasts/learning-resources/#contents)*

.<br>
.<br>
.<br>
.<br>
*All the resources/links above are collected from 'RESOURCES' in our Discord Server; credits to the ones who shared them as well as to the ones who created them. Go to* [CONTRIBUTORS.md](./CONTRIBUTORS.md) *to see the list of contributors.*
