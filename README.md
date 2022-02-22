# BofAllTheThings
Creating a repository with all public Beacon Object Files (BoFs)

The idea is to collect all the Beacon Object Files (BoF ) projects that are out there (similar to my SharpAllTheThings project) that can be used in Cobalt Strike as inline execute command. Credit the name to the amazing PayloadAllTheThings github repo (https://github.com/swisskyrepo/PayloadsAllTheThings)

### Execution
1. tgtdelegation - obtain a usable TGT for the current user and does not require elevated privileges on the host
   * Credit - https://twitter.com/33y0re
   * Link - https://github.com/connormcgarr/tgtdelegation

### Situational Awareness
1. FindObjects-BOF - A Cobalt Strike Beacon Object File (BOF) project which uses direct system calls to enumerate processes for specific modules or process handles.
   * Credit - https://twitter.com/Cneelis
   * Link - https://github.com/outflanknl/FindObjects-BOF
2. DLL Image Resource Version Enumeration BOF - As the name suggest
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/DLL_Version_Enumeration_BOF
 
### Persistence
 
### Privilege Escalation

### Defense Evasion
1. WdToggle - A Proof of Concept Cobalt Strike Beacon Object File which uses direct system calls to enable WDigest credential caching and circumvent Credential Guard (if enabled).
   * Credit - https://twitter.com/Cneelis
   * Link - https://github.com/outflanknl/WdToggle
2. InlineWhispers2 - Tool for working with Direct System Calls in Cobalt Strike's Beacon Object Files (BOF) via Syswhispers2.
   * Credit - https://twitter.com/Sh0ckFR
   * Link - https://github.com/Sh0ckFR/InlineWhispers2
3. HOLLOW - Beacon Object File (BOF) that spawns an arbitrary process from beacons memory in a suspended state, inject shellcode, hijack main thread with APC, and execute shellcode; using the Early Bird injection
   * Credit - https://twitter.com/0xBoku
   * Link - https://github.com/boku7/HOLLOW
4. secinject - Beacon Object File (BOF) that leverages Native APIs to achieve process injection through memory section mapping.
   * Credit - https://twitter.com/apokryptein
   * Link - https://github.com/apokryptein/secinject
5. unhook-bof - This is a Beacon Object File to refresh DLLs and remove their hooks. The code is from Cylance's Universal Unhooking research.
   * Credit - https://twitter.com/joevest
   * Link - https://github.com/Cobalt-Strike/unhook-bof

### Credential Access
1. Cobalt-Clip - Cobalt-Clip is clipboard add-on for Cobalt Strike to interact with the victim's clipboard. With Cobalt-Clip you can dump, edit and monitor the content of a clipboard.
   * Credit - https://github.com/DallasFR
   * Link - https://github.com/DallasFR/Cobalt-Clip
   
### Lateral Movement
    
### Exfiltration

### Other projects
1. BOF Template - This repository is meant to host the core files needed to create a Beacon Object File for use with Cobalt Strike. 
   * Credit - https://twitter.com/joevest
   * Link - https://github.com/Cobalt-Strike/bof_template
2. BOF-Builder - C# .Net 5.0 project to build BOF (Beacon Object Files) in mass based on them all being in a folder directory struct somewhere.
   * Credit - https://twitter.com/Ceramicskate0
   * Link - https://github.com/ceramicskate0/BOF-Builder
