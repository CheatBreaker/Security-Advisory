# Security Advisory
This repository contains important security information regarding CheatBreaker.

## General Information
* CheatBreaker is **NOT** currently available to the public. We highly recommend that you do NOT download any files claiming to be CheatBreaker. Many people have created viruses and other malicious programs while pretending to be our official software.
* We do **NOT** have "paid versions" of CheatBreaker, nor do we provide means for anyone to obtain it for real money. If somebody is trying to sell you CheatBreaker, it's a scam.

## Files and Cryptographic Signatures
* Real CheatBreaker files are cryptographically signed and **timestamped**. This ensures that the files you are running actually came from us.
* When you run a legitimate CheatBreaker executable, you will see that the file is signed by CheatBreaker, LLC:


![Signed Executable](https://i.imgur.com/MrsHXHF.png)


![Certificate Info](https://i.imgur.com/whMsnPt.png)


![Certificate Details](https://i.imgur.com/OjEeMKv.png)

**Serial Number:** 0d9760c0d3af1246f8dc151117ac2495

**Fingerprint:** 20379d97dcbe9795c57411e16cb6a79affc8efcb

If a file claiming to be CheatBreaker does not have this cryptographic signature, you can absolutely, positively, **guarantee** that the file is not ours. CheatBreaker does not currently have any other codesigning certificates.

## Other Security Issues
A security vulnerability in Windows' [ECC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography) validation has been discovered ([CVE-2020-0601](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-0601)). This makes it possible for an attacker to spoof an Authenticode signature. You can read the U.S. Government's assessment of this vulnerability [here](https://media.defense.gov/2020/Jan/14/2002234275/-1/-1/0/CSA-WINDOWS-10-CRYPT-LIB-20190114.PDF). To protect yourself, please be sure to update to the latest version of Windows and that you have all of the latest security updates.

## Social Media Accounts
* The only Twitter accounts operated by us are: @CheatBreaker and @AskCheatBreaker.
* We do not have a Discord or use any other social media platforms.

## Reporting
If you find that people are distributing files without the CheatBreaker signature, are selling or attempting to sell CheatBreaker software or source-code, or are unlawfully using our brand to distribute viruses, please e-mail security@cheatbreaker.com with all of the relevant details. We take such reports extremely seriously and will thoroughly investigate every report.
