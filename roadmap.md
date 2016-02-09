#Namecoin Roadmap
###Abbreviations
__TBD__ : to be discussed  
__F__ : [forum link](https://forum.namecoin.org)  
__G__ : [Github link](https://github.com/namecoin)  
__O__ : other link  
! : urgent  
__bold__ : important  
   
- - - -  
   
- Core (Client / Protocol)
    - Namecoin Core
        - Namecoin Core is the intended replacement for NamecoinQ.
        - Deterministic Builds for Windows and OS X
            - Gitian will in theory work out of the box for this.
            - Need to get volunteers to run Gitian builds.
                - Joseph Bisch and midnightmagic helped during the OpenSSL Consensus Bug response.
                - See if they're willing to continue doing this.
                - Jeremy doesn't have a Gitian setup anymore due to OS incompatibilities.
        - Alert Keys
            - Right now the alert key used in the Namecoin network is Vincent Durham's key.
            - Need to replace it with a key held by current developers.
            - Need to figure out exactly who should hold the key.
    - Strategic changes / Hardforks
        - ! merged mining format (BIP9) [__F__](https://forum.namecoin.info/viewtopic.php?f=5&t=2466)
        - name db hash
        - fees (also destroying coins)
            - find consensus
        - value size (520 bytes limitation)
        - Bitcoin compatibility
        - dust

- __Core GUI__
    - Port Name Tab [__F__](https://forum.namecoin.info/viewtopic.php?f=2&t=2479)
    - nameGUI (ANTPY) [__F__](https://forum.namecoin.info/viewtopic.php?f=9&t=2309)

- Application
    - Namecoin Bundle (__TBD__; client, NMCtrl, resolver installation)
    - Light Resolving
        - API server (experimental version is online) [__F__](https://forum.namecoin.info/viewtopic.php?f=9&t=2227)
        - PoW secured API server [__F__](https://forum.namecoin.info/viewtopic.php?f=5&t=2223)
        - SPV [bounty](https://forum.namecoin.info/viewtopic.php?f=18&t=2281) [__F__](https://forum.namecoin.info/viewtopic.php?f=18&t=2273) 
    - NMControl
        - TLS
            - new DNS server (__TBD__)
            - via local proxy (prototype available) [__F__](https://forum.namecoin.info/viewtopic.php?f=9&t=2436)
        - API mode (prototype available) [__F__](https://forum.namecoin.info/viewtopic.php?f=8&t=2174)
        - Tor support (__TBD__)
        - Tor browser support (__TBD__)
        - __i2p support__ (__TBD__)
        - __redirection to legacy domains__ (__TBD__; coolsite.bit --> coolsite.freedomainhoster.com; easy with proxy)
        - improve http GUI name browser (experimental version available) [__F__](https://forum.namecoin.info/viewtopic.php?f=8&t=2174)

- Documentation & Communication
    - Improve the wiki
        - done? Port missing pages from the old wiki
        - done? Beginner's manual ("getting started")
        - __List of resources__ (tools / libs / code snippets)
        - __Merged-mining instructions__
    - Define, implement and foster communication channels

 - Marketing & Recruiting
    - Make __httpS://namecoin.ORG__ standard URL
    - Use [new logo](https://github.com/namecoin/namecoin-graphics) everywhere (bitcointalk, twitter, blog)
    - Get more websites on .bit (maybe as an additional shortcut domain?)

- Ongoing Tasks
    - Maintenance
        - Server
        - Website
        - Wiki
        - Forum (software update!)
    - Namecoin Core Bitcoin downstream
    - Donations
    - Bounties [__F__](https://forum.namecoin.info/viewforum.php?f=18)
    - Funding (__TBD__)

- Projects / Research / New Applications
    - All releases via Github (__TBD__)
    - Standardize tools
        - python rpc to core
        - nameprocess
    - __URI Scheme for names__ [__F__](https://forum.namecoin.info/viewtopic.php?f=5&t=1905)
    - Create and read IDs (NMControl / nameGUI)
    - __WOT__ [__F__](https://forum.namecoin.info/viewtopic.php?f=5&t=1522)
    - DHT / external data storage (__TBD__)
    - File signing [bounty](https://forum.namecoin.info/viewtopic.php?f=18&t=2281) [**F**](https://forum.namecoin.org/viewtopic.php?f=2&t=1059)
        - maybe combine with timestamping (__TBD__)
        - NMControl / nameGUI (__TBD__)
    - Timestamping
    - Even further Bitmessage integration (replace all by IDs? __TBD__) [bounty](https://forum.namecoin.info/viewtopic.php?f=18&t=2281)
    - Full eMail client integration (PGP / ECC)
    - Electrum integration (should be relatively easy to do)
    - give more weight to names by sending NMC to them [__F__](https://forum.namecoin.info/viewtopic.php?f=2&t=1422)
    - revocation (__TBD__)
    - name_update without privkey (__TBD__)
    - P2Pool sharechain implementation [**F**](https://github.com/p2pool/p2pool/issues/265)
    - Torrent Tracking [__F__](https://forum.namecoin.info/viewtopic.php?f=5&t=1381)
    - Namecoin Local PGP Keyserver (early version available) [__F__](https://forum.namecoin.info/viewtopic.php?f=9&t=2476)
