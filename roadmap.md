#Namecoin Roadmap
- Core (Client / Protocol)
    - Namecoin Core
        - Deterministic Builds for Windows (Gitian)
        - Alert Keys
    - Strategic changes / Hardforks
        - name db hash
        - fees (also destroying coins)
            - find consensus
        - value size
        - Bitcoin compatibility
        - dust

- __Core GUI__
    - Get consensus on how to proceed.
    - 3 suggested options
    - Phelix's nameGUI?
        - test
        - Bundle with client
        - data entry
        - nametrade/ANTPY
        - lookup data interfacing (or open NMControl httpBrowser?)
    - Port Namecoin-Qt Name Tab to Namecoin Core?
        - moa offered an unspecified bounty for this
    - Alternative wallets? 
        - Armory
            - FSM is sponsoring some bounties
        - Electrum

- Application
    - ? Namecoin Bundle (Client, NMCtrl, resolver installation)
    - Light Resolving
        - API server (experimental version is online)
        - Semi safe SVP via merkle tree and blockheaders
        - SPV
    - NMControl
        - TLS
            - new DNS server
        - API mode (experimental version works)
        - Tor support?
        - Tor browser support?
        - __i2p support__?
        - __redirection to legacy domains__ (coolsite.bit --> coolsite.freedomainhoster.com)  ???
        - improve http GUI name browser?

- Documentation & Communication
    - Improve the wiki
        - done? Port missing pages from the old wiki
        - done? Beginner manual ("getting started")
        - __List of resources__ (tools / libs / code snippets)
        - __Mining instructions__
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
        - Forum (update!)
    - Namecoin Core Bitcoin downstream
    - Donations
    - Bounties
    - Funding?

- Projects / Research / New Applications
    - All releases via Github?
    - Standardize tools
        - python rpc to core
        - nameprocess
    - URI Scheme for names
    - create and read IDs (NMControl?  / nameGUI?)
    - __WOT__
    - DHT?
    - File signing [**F**](https://forum.namecoin.org/viewtopic.php?f=2&t=1059)
        - maybe combine with timestamping?
        - NMControl / nameGUI?
    - Timestamping
    - Even further Bitmessage integration (replace all by IDs?)
    - Full eMail client integration (PGP / ECC)
    - Electrum integration (should be relatively easy to do)
    - give more weight to names by sending NMC to them
    - revocation?
    - name_update without privkey???
    - ...

##Legend
__bold__ : important  
! : urgent  
? : to be discussed further  
__F__ : [forum link](https://forum.namecoin.org)  
__G__ : [Github link](https://github.com/namecoin)  
__O__ : other link  
