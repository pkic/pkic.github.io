---
authors:
- Jeremy Rowley
date: "2013-11-14T21:00:21+00:00"
dsq_thread_id:
- 1963595351
keywords:
- malware
- ca/browser forum
- identity
- code signing
- https
tags:
- Malware
- CA/Browser Forum
- Identity
- Code Signing
- SSL/TLS
title: Improving Code Signing


---
Previously, we discussed how code signing certificates play a key role in the trust framework by proving the authenticity of software. As mentioned, code signing certificates act as a certification that the software was unmodified after publication. Although current code signing practices greatly reduce the threats of malware and adware embedded in signed objects, the sophistication of threats has risen and there is a need for improvement. When code signing was new, skilled criminal hackers were the exception and script kiddies were the norm. Now, the skill level and sophistication of criminal networks, and even nation states, have advanced to the point where customized malware is being used to penetrate company networks, steal valuable information, and even tamper with sensitive infrastructure.

Recognizing the need to stay ahead of these increasing threats and the important role that digital code signing can play in protecting the software distribution ecosystem, members of the CA/Browser Forum formed a working group aimed at improving global code signing practices and standards. During initial meetings, the Code Signing Working Group (working group) identified several areas in need of improvement:

  1. **Improving key storage practices and private key protection.** Many attacks succeed simply by accessing the software publisher’s private keys, especially those of large organizations. By signing code with a stolen key, attackers can easily trick end users into installing malware, because the software has the appearance of legitimacy. The increased sophistication of social engineering and similarly targeted threats make the protection of keys even more difficult, but more needed. As such, the working group is exploring ways to improve key storage and further educate end-users on key storage best practices.
  2. **Better identity vetting.** Establishing minimum standards for issuing code signing certificates will decrease the number of threats by ensuring the entity responsible for the code is sufficiently identified. Although most CAs already follow strict identity vetting practices, a few incidences have shown a need to codify this practice and strengthen the standard. In addition to helping users understand the source of the code, better identity practices can assist law enforcement in finding and stopping malicious parties. New identity standards will better confirm the location and identity of each signer, letting everyone know who is responsible for the code. 
  3. **Better threat detection.** Part of the working group’s recommendations on combatting malware includes improved processes for sharing information among issuers. Currently, a malware signer whose previous certificate was revoked can approach additional CAs until a certificate is issued, without those CAs being aware of the recent malfeasance. New information sharing mechanisms will help alert CAs about bad actors looking for a certificate and disseminate information on malware. In addition to information sharing, the working group is looking at ways to ensure that code is scanned for malware before signing and additional safe-guards are in place to protect high-risk targets. 
  4. **Technical improvements.** New developments in the industry are being applied to code signing certificates and included as part of minimum standards, including better key sizes and more secure hash algorithms. These improvements are focused on preventing brute force and similar attacks. 

In later blog posts, we plan to discuss each of these four categories in more detail. Meanwhile, participation in the CA/B Forum Code Signing Working Group is open to anyone interested and willing to sign the CA/Browser Forum’s intellectual property rights (IPR) agreement available at [https://www.cabforum.org](https://www.cabforum.org).