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
        - Deterministic Builds for Windows (Gitian)
        - Alert Keys
    - Strategic changes / Hardforks
        - name db hash
        - fees (also destroying coins)
            - find consensus
        - value size (520 bytes limitation)
        - Bitcoin compatibility
        - dust

- __Core GUI__
    - nameGUI (__TBD__)
        - test
        - Bundle with client
        - data entry
        - nametrade / ANTPY
        - lookup data interfacing (or open NMControl httpBrowser; __TBD__)
    - Port Name Tab (__TBD__)
    - Alternatives (__TBD__; Armory, Electrum)

- Application
    - Namecoin Bundle (__TBD__; client, NMCtrl, resolver installation)
    - Light Resolving
        - API server (experimental version is online)
        - Semi-safe SPV via merkle tree and blockheaders
        - SPV
    - NMControl
        - __Release__
        - TLS
        - API mode (experimental version works)
        - Tor support (__TBD__)
        - Tor browser support (__TBD__)
        - __i2p support__ (__TBD__)
        - __redirection to legacy domains__ (__TBD__; coolsite.bit --> coolsite.freedomainhoster.com) 
        - improve http GUI name browser (__TBD__)

- Documentation & Communication
    - Improve the wiki
        - done? Port missing pages from the old wiki
        - done? Beginner's manual ("getting started")
        - __List of resources__ (tools / libs / code snippets)
        - __Merged-mining instructions__
    - Define, implement and foster communication channels

 - Marketing & Recruiting
    - Make __httpS://namecoin.org__ standard URL
    - Use new logo everywhere (bitcointalk, twitter, blog)
    - Get more websites on .bit (maybe as an additional shortcut domain?)

- Ongoing Tasks
    - Maintenance
        - Server
        - Website
        - Wiki
        - Forum (software update!)
    - Namecoin Core Bitcoin downstream
    - Donations
    - Bounties
    - Funding (__TBD__)

- Projects / Research / New Applications
    - All releases via Github (__TBD__)
    - Standardize tools
        - python rpc to core
        - nameprocess
    - URI Scheme for names
    - Create and read IDs (NMControl / nameGUI)
    - __WOT__
    - DHT (__TBD__)
    - File signing [**F**](https://forum.namecoin.org/viewtopic.php?f=2&t=1059)
        - maybe combine with timestamping (__TBD__)
        - NMControl / nameGUI (__TBD__)
    - Timestamping
    - Even further Bitmessage integration (replace all by IDs? __TBD__)
    - Full eMail client integration (PGP / ECC)
    - Electrum integration (should be relatively easy to do)
    - give more weight to names by sending NMC to them
    - revocation (__TBD__)
    - name_update without privkey (__TBD__)
    - P2Pool sharechain implementation [**F**](https://github.com/p2pool/p2pool/issues/265)
