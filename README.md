Crypto Projects that Might not Suck
===================================

This document originated with an informal survey of Twitter and several mailing lists asking for nominations for crypto projects that "didn't suck". Over 100 nominations were received and culled down to this list. Projects marked with an "☢" symbol are relatively new and considered experimental. Apologies to project creators who are omitted. Corrections are welcome via pull request.


End User Tool Summary
---------------------
This is a quick summary of tools that are generally recommended for end users. See the [EFF's Surveillance Self Defense guides](https://ssd.eff.org/en) or  [Press Freedom Foundation's Encryption Works](https://freedom.press/encryption-works) guide for more information.

* [GPG](https://www.gnupg.org/): Email encryption. 
   * [EFF PGP Intro](https://ssd.eff.org/en/module/introduction-public-key-cryptography-and-pgp)
   * [Windows PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-windows-pc)
   * [Mac PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-mac-os-x)
   * [Linux PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-linux)
* [Signal](https://whispersystems.org/): Encrypted messaging & voice calls
   * [Signal Source](https://github.com/WhisperSystems?utf8=%E2%9C%93&query=Signal)
   * EFF Signal Guide for [Android](https://ssd.eff.org/en/module/how-use-signal-android) or [iOS](https://ssd.eff.org/en/module/how-use-signal-ios) 
* [OTR](https://otr.cypherpunks.ca/): Encrypted instant messaging. 
   * [Windows OTR Installation](https://ssd.eff.org/en/module/how-use-otr-windows)
   * [Mac OS X OTR Installation](https://ssd.eff.org/en/module/how-use-otr-mac)
* [Tor](https://www.torproject.org/): Protect from network surveillance 
   * [Windows Tor Installation](https://ssd.eff.org/en/module/how-use-tor-windows)
   * [Mac OS X Tor Installation](https://ssd.eff.org/en/module/how-use-tor-mac-os-x)

The People’s Choice
-------------------
* Open Whisper Systems: https://whispersystems.org/
    * Moxie Marlinspike (@moxie) & open source community
* Signal: Encrypted messaging & phone calls for iPhone and Android
    * Calls: ZRTP for key agreement, SRTP for call encryption
    * Messaging: OTR-like forward security & Axolotl key ratcheting by @trevp__
    * https://github.com/WhisperSystems?utf8=%E2%9C%93&query=Signal

Honorable Mentions
-----------------
* ☢ Networking and Crypto Library (NaCl): http://nacl.cr.yp.to/
    * Easy to use, high speed XSalsa20, Poly1305, Curve25519, etc
    * No dynamic memory allocation or data-dependent branches
    * DJ Bernstein (@hashbreaker), Tanja Lange (@hyperelliptic),  Peter Schwabe (@cryptojedi)
* ☢ libsodium: https://github.com/jedisct1/libsodium
    * Portable, cross-compatible NaCL
    * OpenDNS & Frank Denis (@jedisct1)
* ☢ curve25519-donna: https://code.google.com/p/curve25519-donna/
    * 64-bit implementation of just curve25519
    * Adam Langley (@agl__)

The Old Standbys
----------------
* Gnu Privacy Guard (GPG): https://www.gnupg.org/
    * GPGTools for OS X Mail: https://gpgtools.org/
    * GPG4win for Windows: http://gpg4win.org/
    * Enigmail for Thunderbird: https://www.enigmail.net/home/index.php
* OpenSSH: http://www.openssh.com/
* Tor: https://www.torproject.org/
* Off-the-Record (OTR): https://otr.cypherpunks.ca
    * Ian Goldberg, David Goulet (@ev0ke42), Jake Applebaum (@ioerror), & Jurre van Bergen (@DrWhax)
    * Pidgin's Off-the-Record plugin: https://otr.cypherpunks.ca/index.php#downloads
    * Adium has native integration: https://adium.im/
    * ☢ Invisible.im: New project XMPP/OTR using Tor Hidden services

The SSL Libraries
-----------------
* OpenSSL: Seriously. https://www.openssl.org/
* ☢ LibreSSL: http://www.libressl.org/
    * Hilarious code reviews
    * OpenBSD team and Bob Beck (@bob_beck)
* ☢ BoringSSL: https://boringssl.googlesource.com/boringssl/
    * Google’s OpenSSL fork by Adam Langley (@agl__)

JavaScript Crypto Libraries
---------------------------
* Stanford JS Crypto Lib (SJCL): https://crypto.stanford.edu/sjcl/
    * Emily Stark, Mike Hamburg, & Dan Boneh
    * Used in several products, e.g. Crypton.io
* ☢ Microsoft JS Crypto Library
    * 800 MB of test vectors for 9000 lines of code
    * Non-commercial and research license only

Browser Crypto
--------------
* ☢ End-to-End: https://code.google.com/p/end-to-end/
    * OpenPGP in a Chrome Extension
    * Google, Drew Hintz (@DrewHintz) & Eduardo Vela (@sirdarckcat)
* ☢ WebCrypto: http://www.w3.org/TR/WebCryptoAPI/
    * Native crypto support in the browser
    * Used for PKI by PKIjs.org.
    * Ryan Sleevi (@sleevi_) / Google & Mark Watson / Netflix

Online Storage
--------------
* Tahoe-LAFS: https://tahoe-lafs.org/
    * Distributed, provider-independent cloud storage
    * Least Authority Systems, Zooko (@zooko), et al.
* Tarsnap: http://tarsnap.com
    * Client-side encryption; must build from source
    * Commercial service archives on S3
    * Colin Percival (@cperciva)

Libraries and Frameworks
------------------------

* Crypto++: http://www.cryptopp.com/
    * Long-lived C++ crypto library by Wei Dai
* go.crypto: http://golang.org/pkg/crypto/
* Keyczar: http://keyczar.org
    * Simple crypto library wrapper for Java, Python, and C++
    * Google, Ben Laurie (@benl), Steve Weis (@sweis), many others
* ☢ Cryptography.io: https://cryptography.io/
    * Attempt to build a good Python crypto library
    * Paul Kehrer (@reaperhulk) & Alex Gaynor (@alex_gaynor)
* ☢ ECClib: http://research.microsoft.com/en-us/projects/nums/
    * Microsoft Research & Patrick Longa (@PatrickLonga)

Messaging and Publishing
------------------------
* ☢ Pond: https://pond.imperialviolet.org/ 
    * Forward secure, asynchronous messaging
    * Adam Langley (@agl__)
* ☢ Cryptosphere: http://cryptosphere.org/
    * Peer-to-peer content publishing
    * Tony Arcieri (@bascule)

Community Efforts
-----------------
* Open Crypto Audit Project (OCAP): https://opencryptoaudit.org/
    * Audited TrueCrypt. Great technical advisory board.
* Better Crypto: https://bettercrypto.org/
    * Community-generated guidelines for applied crypto hardening
* Crypto Coding Standard: https://cryptocoding.net/
* ☢ Password Hashing Competition: https://password-hashing.net/
    * Community-driven contest for password hashing replacement
* ☢ Safe Curves: http://safecurves.cr.yp.to/
    * Criteria to ensure elliptic-curve crypto security
    * DJ Bernstein (@hashbreaker) & Tanja Lange (@hyperelliptic)

Experimental Toolkits
---------------------
* ☢ Advanced Crypto Software Collection: http://hms.isi.jhu.edu/acsc/
* ☢ Relic Toolkit: https://github.com/relic-toolkit/relic
    * Bilinear maps, pairing-based crypto, ID-based crypto
    * Implemented in C
    * Diego Aranha (@dfaranha) and C.P. L. Gouvêa
* ☢ CHARM: http://www.charm-crypto.com/
    * Tool for rapid cryptographic prototyping
    * Bilinear maps, multiparty protocol engine, non-interactive ZK
    * Python with native C modules
    * JHU ISI: J. Ayo Akinyele (@ja_akinyele), et al.

Certificate and Key Management Tools
------------------------------------
* ☢ Let's Encrypt: Open source certificate authority & free service
    * Available as a service (Fall 2015): https://letsencrypt.org/
    * Go source code: https://github.com/letsencrypt/letsencrypt
* ☢ CFSSL: https://github.com/cloudflare/cfssl 
    * Command line tool and an HTTP API server for signing, verifying, and bundling TLS certificates
    * Implemented in Go
* ☢ Red October: https://github.com/cloudflare/redoctober
    * Encryption and decryption server enforcing a two-person rule
    * Implemented in Go
* ☢ KeyWhiz: https://github.com/square/keywhiz
    * A system for distributing and managing secrets
    * Implemented in Java
* ☢ Vault: https://github.com/hashicorp/vault
    * A tool for managing secrets
    * Implemented in Go

Verification & Automation Tools
-------------------------------
* ☢ Cryptol: http://cryptol.net/
    * Domain-specific language for specifying crypto algorithms
    * Galois Inc. & Adam C. Foltzer (@acfoltzer)
    * Works with Software Analaysis Workbench (SAW): https://galois.com/project/software-analysis-workbench/
* ☢ AutoTools: https://github.com/JHUISI/auto-tools
    * Python tools for transforming cryptographic primitives in different and interesting ways
    * JHU ISI: J. Ayo Akinyele (@ja_akinyele), et al.
* ☢ EasyCrypto: https://www.easycrypt.info/trac/
    * Computer-Aided Cryptographic Proofs
* ☢ Tamarin Security Protocol Verification: https://github.com/tamarin-prover/tamarin-prover
* ☢ gfverif: http://gfverif.cryptojedi.org/
    * Fast and easy verification of finite-field arithmetic
  
Miscellaneous Project
---------------------
* ☢ spiped: http://www.tarsnap.com/spiped.html
    * Secure pipe daemon
    * Similar to ‘ssh -L’ but requires pre-established secret
    * Colin Percival (@cperciva)
* ☢ libsnark: https://github.com/scipr-lab/libsnark
    * C++ library for zero-knowledge proof system with succinct proofs
    * Eli Ben-Sasson, Alessandro Chiesa, Eran Tromer, and Madars Virza
* ☢ libmacaroons: https://github.com/rescrv/libmacaroons
    * Decentralized authentication for distributed systems
    * Paper: Chalmers/Brown/Google; Code: Robert Escriva (@rescrv)

Learning and Resources
-----------------
* Matasano Crypto Challenges (@tqbf): http://cryptopals.com/
* Thomas Ptacek's Cryptographic "Right Answers": https://gist.github.com/tqbf/be58d2d39690c3b366ad
* Underhanded Crypto Contest: https://underhandedcrypto.com
* Modern Crypto mailing lists (@trevp__): https://moderncrypto.org/
* CryptoBib bibliography (@daeinar): http://cryptobib.di.ens.fr/init/default/index
* 52 Things People Should Know To Do Cryptography: http://www.cs.bris.ac.uk/Research/CryptographySecurity/knowledge.html
* Crypto101 Introductory course: https://www.crypto101.io/
* Dan Boneh's Coursera Cryptography course: https://www.coursera.org/course/crypto
* Dan Boneh & Victor Shoup's "A Graduate Course in Applied Cryptography": https://crypto.stanford.edu/~dabo/cryptobook/draft_0_2.pdf
