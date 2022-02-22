# BofAllTheThings
Creating a repository with all public Beacon Object Files (BoFs)

The idea is to collect all the Beacon Object Files (BoF ) projects that are out there (similar to my SharpAllTheThings project) that can be used in Cobalt Strike as inline execute command. Credit the name to the amazing PayloadAllTheThings github repo (https://github.com/swisskyrepo/PayloadsAllTheThings)

### BOF Collections
1. TrustedSec BOFS
   * BOFS - arp, adcs_enum, adcs_enum_com, adcs_enum_com2, adv_audit_policies, cacls, dir, driversigs, enum_filter_driver, enumLocalSessions, env, findLoadedModule, get_password_policy, ipconfig, ldapsearch, listdns, listmods, listpipes, netstat, netuser, netuse_add, netuse_delete, netuse_list, netview, netGroupList, netGroupListMembers, netLocalGroupList, netLocalGroupListMembers, nslookup, reg_query, reg_query_recursive, routeprint, schtasksenum, schtasksquery, sc_enum, sc_qc, sc_qfailure, sc_qtriggerinfo, sc_query, sc_qdescription, tasklist, whoami, windowlist, wmi_query, netsession, resources, uptime, vssenum
   * Credit - https://twitter.com/ajpc500
   * Link - https://github.com/trustedsec/CS-Situational-Awareness-BOF
2. ajpc500 BOFs Collection
   * BOFS - ETW Patching, Syscalls shellcode injection, API Function Utility, Spawn and Syscalls Shellcode Injection, Spawn and Syscalls Shellcode Injection (NtQuereApcThread), Static Syscalls Shellcode Injection, Static syscalls Process Dump,  curl
   * Credit - https://twitter.com/ajpc500
   * Link - https://github.com/ajpc500/BOFs

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
3. Firewall_Enumerator_BOF - This is meant as a supplement to interact with the Windows firewall via COM interfaces.
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/Firewall_Walker_BOF
4. Process Protection Level Enumerator BOF - A Syscall-only BOF file intended to grab process protection attributes, limited to a handful that Red Team operators and pentesters would commonly be interested in.
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/Process_Protection_Level_BOF

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
6. Self_Deletion_BOF - BOF implementation of the research by @jonasLyk for executable self deletion. 
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/Self_Deletion_BOF
7. Toggle_Token_Privileges_BOF - An (almost) syscall-only BOF file intended to either add or remove token privileges within the context of your current process.
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/Toggle_Token_Privileges_BOF

### Credential Access
1. Cobalt-Clip - Cobalt-Clip is clipboard add-on for Cobalt Strike to interact with the victim's clipboard. With Cobalt-Clip you can dump, edit and monitor the content of a clipboard.
   * Credit - https://github.com/DallasFR
   * Link - https://github.com/DallasFR/Cobalt-Clip
2. PPLDump BOF - A fully-fledged BOF to dump an arbitrary protected process.
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/PPLDump_BOF
   
### Lateral Movement
1. DCOM Lateral Movement -  quick PoC that uses DCOM (ShellWindows) via beacon object files for lateral movement.
   * Credit - https://twitter.com/Yas_o_h
   * Link - https://github.com/Yaxser/CobaltStrike-BOF
2. WMI Lateral Movement -  quick PoC that uses WMI (Win32_Process and Event Subscription) via beacon object files for lateral movement.
   * Credit - https://twitter.com/Yas_o_h
   * Link - https://github.com/Yaxser/CobaltStrike-BOF

### Exfiltration

### Other Projects
1. DLL Exports Extraction BOF - As the name suggests
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/DLL-Exports-Extraction-BOF
2. DLL Hijack Search Order BOF - As the name suggests
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/DLL-Hijack-Search-Order-BOF
3. PE Import Enumerator BOF - As the name suggests
   * Credit - https://github.com/EspressoCake
   * Link - https://github.com/EspressoCake/DLL_Imports_BOF

### BOF Builders
1. BOF Template - This repository is meant to host the core files needed to create a Beacon Object File for use with Cobalt Strike. 
   * Credit - https://twitter.com/joevest
   * Link - https://github.com/Cobalt-Strike/bof_template
2. BOF-Builder - C# .Net 5.0 project to build BOF (Beacon Object Files) in mass based on them all being in a folder directory struct somewhere.
   * Credit - https://twitter.com/Ceramicskate0
   * Link - https://github.com/ceramicskate0/BOF-Builder
3. Visual-Studio-BOF-template - baseline template that can be reused to develop BOFs with Visual Studio without having to worry about dynamic function resolution syntax, stripping symbols, compiler configurations, C++ name mangling, or unexpected runtime errors
   * Credit - https://securify.nl/
   * Link - https://github.com/securifybv/Visual-Studio-BOF-template
