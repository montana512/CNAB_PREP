# NETWORKING

+ FILL IN THE BLANK
<img width="689" height="268" alt="image" src="https://github.com/user-attachments/assets/15a8078b-4568-499c-a1cd-c9849019a987" />

  + `192.168.1.1`



+ WHAT IS GPG?

  + `GNU Privacy Guard is free encryption software`
 
*`GNU Privacy Guard (GPG)` is a `free, open-source software tool used for encrypting, decrypting, and signing data`. It's based on the `OpenPGP standard` and is often used for secure communication, verifying the integrity of files, and managing digital signatures. Because it is free, it is widely available as an alternative to proprietary encryption technologies.*

<br>
<br>
<br>
<br>

+ WHAT LAYER OF THE OSI MODEL DO WIRELESS ACCESS POINTS RESIDE?

  + APPLICATION LAYER
      
  + PRESENTATION LAYER
      
  + SESSION LAYER
      
  + TRANSPORT LAYER
      
  + NETWORK LAYER
      
  + DATA LINK LAYER - X
      
  + PHYSICAL LAYER

  + `DATA LINK LAYER`
 
<br>
<br>
<br>
<br>

+ WHAT ABILITIES DOES `SNMP` (SIMPLE NETWORK MANAGEMENT PROTOCOL) HAVE?

  + `MONITOR NETWORK DEVICE STATUS, REMOTELY CONFIGURE DEVICES, SET UP "TRAPS" TO SEND NOTIFICATIONS TO A CENTRAL SERVER WHEN CERTAIN EVENTS OCCUR.`
 
*SNMP (Simple Network Management Protocol) is a protocol designed for network management. It allows administrators to monitor the status of network devices like routers, switches, servers, and printers. Beyond just monitoring, SNMP also provides the ability to configure these devices remotely, changing settings and parameters as needed. A key feature of SNMP is the use of "traps," which are notifications sent by devices to a central server when certain events occur, such as a device going offline or exceeding a threshold. This proactive alerting helps in quickly identifying and resolving network issues.*

<br>
<br>
<br>
<br>

+ IF YOU NEED TO SUPPORT WINDOWS CLIENTS USING UNIX SERVERS, YOU WILL PROBABLY USE?

  + `SAMBA`
 
*`Samba` is a suite of applications that implements the `Server Message Block (SMB) protocol` on Unix-like systems, allowing them to share files and printers with Windows-based computers. `Windows uses SMB for network file sharing`, so `Samba` acts as a `bridge`, enabling seamless integration between Windows clients and Unix servers. Without Samba or a similar solution, Windows machines would not be able to easily access resources hosted on Unix servers.*

<br>
<br>
<br>
<br>

+ WHAT IS ANOTHER TERM FOR SYMMETRIC ENCRYPTION?

  + `SINGLE-KEY ENCRYPTION`
 
*Symmetric encryption is called `single-key` encryption because the same key is used for both encrypting and decrypting the data. This is in contrast to asymmetric encryption, where one key encrypts and a different key decrypts.*

<br>
<br>
<br>
<br>

+ 802.1D IS ____ AND IS LAYER 2 OF THE OSI MODEL.

  + `SPANNIN TREE PROTOCOL (STP)`
 
*The `IEEE 802.1D standard` defines the `Spanning Tree Protocol (STP)`. STP is a network protocol that `prevents loops` in a network topology. It operates at `Layer 2 (the Data Link Layer)` of the OSI model. By implementing STP, network administrators can ensure a loop-free logical topology for Ethernet networks, which is crucial for maintaining network stability and `preventing broadcast storms`.*

<br>
<br>
<br>
<br>

+ SOURCE ADDRESS TABLE LOCATED ATHE THE SWITCH/BRIDGE DOES WHAT?

  + `MAPS MAC ADDRESSES TO SWITCH PORTS`
 
<br>
<br>
<br>
<br>

+ FILL IN THE BLANK BELOW
<img width="686" height="437" alt="image" src="https://github.com/user-attachments/assets/fa2dcdf7-2b60-4e0f-8f7b-7f8b88ac2aae" />

  + `-6`
 
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# OPERATING SYSTEMS

+ IN WINDOWS, WHAT COMMAND WOULD YOU USE TO SHARE A FOLDER WITH SOMEONE?

  + `net share`
 
*The `net share` command in Windows is used to manage shared resources on a network. It allows you to share folders or printers, making them accessible to other users on the network. The basic syntax is `net share <sharename>=<drive:path>`. For example, to share a folder named "Data" located at "C:\Data" with the share name "DataShare", you would use the command `net share DataShare=C:\Data`. You can also add options to control permissions and access.*

<br>
<br>
<br>
<br>

+ In UNIX, what does the `whereis` command return?

  + `THE ABSOLUTE PATH OF A BINARY`
 
*The whereis command in UNIX is a quick way to locate the binary, source code, and manual page files for a specific command. For example, if you type whereis ls, it will show you where the ls executable is located (e.g., /bin/ls), as well as the locations of its source file (if available) and its manual page. This is helpful for understanding where programs are installed and for accessing their documentation.*

<br>
<br>
<br>
<br>

+ WHAT KEY IS USED TO SIGN A MESSAGE DIGEST TO TURN IT INTO A DIGITAL SIGNATURE?

  + `SIGNERS PRIVATE KEY`
 
<br>
<br>
<br>
<br>

+ In UNIX, what is the PATH variable? → PATH holds the directories in which the operating system looks for the commands you execute at the command line.

  + `PATH HOLDS THE DIRECTORIES IN WHICH THE OPERATING SYSTEM LOOKS FOR THE COMMANDS YOU EXECUTE AT THE COMMAND LINE`
 
<br>
<br>
<br>
<br>

+ IN UNIX, WHAT DOES THE `file` COMMAND DO?

  + `IDENTIFIES THE FILE TYPE BY LOOKING INSIDE THE FILE AT THE FILE HEADER, NOT THE FILE EXTENSION`
 
*The `file` command in UNIX is a utility used to determine the type of a file. Unlike some operating systems that rely heavily on file extensions to identify file types, file examines the file's content, specifically the `magic number` or `file header`. This header contains information about the file's structure and format, allowing file to accurately identify the file type, regardless of its extension (or lack thereof). This is more reliable than depending on the file extension, which can be easily changed or omitted.*

<br>
<br>
<br>
<br>

+ WHAT DOES THE WHO COMMAND DO IN UNIX?

  + `READS THE /var/log/utmp FILE AND REVEALS ACTIVE USER SESSIONS`
 
*The `who` command is a basic Unix command that displays information about currently logged-in users. It retrieves this information by reading the `/var/log/utmp` file, which keeps track of user login sessions. The output typically includes the `username, terminal line, login time, and sometimes the remote host from which the user is connected`. It's a quick way to see who is currently using the system.*

<br>
<br>
<br>
<br>

+ IN UNIX WHAT IS THE `/etc/nsswitch.conf` file?

  + `THE ORDER IN WHICH TO CONTACT DIFFERENT NAME SERVICES`
 
*The `/etc/nsswitch.conf` file is a configuration file that specifies the order in which the system should consult various naming and directory services to resolve names and other information. This includes things like hostnames, user accounts, groups, and services. The file allows administrators to customize the sources and the order in which they are queried, providing flexibility in managing how a system resolves names and retrieves information from different databases or services. `For example, you can specify whether the system should first check the local /etc/hosts file before querying a DNS server for hostname resolution.`*

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# FUNDAMENTALS AND THEORY OF COMPUTING

+ FILL IN THE BLANK BELOW
<img width="475" height="345" alt="image" src="https://github.com/user-attachments/assets/9b4bf210-91b4-4f65-8065-415f9ef2e191" />

  + `MASS STORAGE`
 
<br>
<br>
<br>
<br>

+ 


