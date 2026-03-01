# Comptia-A-Plus-Labs
Practical labs and notes for my IT journey. Training to become a Cyber Professionalist.
# My-IT-Journey

## Lesson 1: MDM and Mobile devices

Today I finished Professer Messer's video on MDM.

### Learned: How to manage 100 devices on MDM.

### Key Concepts:

* Cloud sync, Data roaming, Remote wipe.

# Lab 1: MDM Configuration Lab 🚀

Today I learned about how a company controls 1000 of devices at the same time by taking Professor Messer's lecture and Miradore walkthrough.

## Key concepts learned:
* Enrollment: How to enroll the device via email or QR code.
* Profiles and Policies: How to apply rules ( disabling the camera, enabling the 6-digit password).
* Remote commands: How to control the devices remotely and wipe the data.
* BYOD and COPE: Learned the difference between Bring Your Own Device and Corporate owned,Personally Enabled.

## Tool Used:Miradore

## Policy stimulation:
  
<p align="center " ><img width="50%" height="1001" alt="Screenshot 2026-02-18 151716" src="https://github.com/user-attachments/assets/14c46077-7b0e-4ba5-8376-6f3e67ccbfc6" />
<img width="50%" height="479" alt="action log" src="https://github.com/user-attachments/assets/f517fd34-7a47-4dfb-b717-9336cfbc46ca" />
<img width="50%" height="472" alt="enroll device" src="https://github.com/user-attachments/assets/1d579969-fadf-41e5-a436-bad03f43c42f" />
<img width="50%" height="470" alt="infrastructure diagram" src="https://github.com/user-attachments/assets/93004d04-20e2-4635-9fe5-a4e763cba272" /> </p>

## Security Importance:

* Remote wipe: it allows the administrator to wipe the sensitive data from the company device in case of device theft or lost.
* Rooting or Jailbreaking: it is the situation when the user breaks the securrity policies implied by administrator which makes the vulnerabilties unpatched,allows malware to attack the system, fraud happenings, and data theft.
* Containerization: simply putting the sensitive data of company in a separate container in the phone. Work files cannot escape this container and peronal data cannot peak through the container. Keeping the Data privacy.

                                 ---------------------------------------------------------------

  # Lesson 2: Introduction to IP Internet Protocols

  ## Key Concepts Learned:
  
  # Addresses
  
  * IP Address: Your device unique address for transfer of data.
  * IPv4: Old system using 4 set of numbers, but it has ran out of the capacity of assigning address to devices.
  * IPv6: New system that assigns IP addresses to devices to connect to internet, has vast capacity, address contains letters and numbers and uses colon to separate set of numbers.

  # Transport Protocols

  * TCP Transmission Control Protocol: Reliable, usually slower than UDP, acknowledgement from the server that the data has been received, used for emails, webs file transfer, resends the missed packet of data.
  * UDP User Datagram Protocol: Unreliable, fast delivery speed, does not resend the missed data,  no acknowledgement, used for games, calls live streaming.

  # Network Helper Protocols

  * DHCP: Dynamic Host Configuration Protocol, used for assigning IP addresss to device by the router so they can connect to the internet.
  * TFTP: Trivial File Transfer Protocol, used for transfering files, basic and simple method of delivery.
  * HTTP: Hyper Text Transfer Protocol, basic way to visit websites.
  * HTTPS: Similar way to view websites but in a secured way.
  * SSH: Secure Shell used by IT perosns or admin to remote control a computer with maximum security.

    # Port Numbers

    * *Virtual doors* that tell your computer which service the data belongs.
    * Non Ephemeral ports: Mostly permanent, well known ports usually ranging from 0 to 1023.
    * Ephemeral ports: Assigned to clients as temporary ports, assigned in real time as the application is being used.
    * TCP and UDP have different ports, means a service running on port 8 of TCP will be different from the service running on port 80 of UDP. This is known as **Multiplexing**.

  ## Lab 2: IP configuration

  * I used the 'ipconfig/all' command to see how my device gets its digital address.
  **What I learned:**
- **IPv4 Address:** My device's unique local address.
- **DHCP Server:** Found the address of my router that assigned my IP.
- **Default Gateway:** The "exit door" for my internet traffic.
<p align="center"> <img width="50%" height="788" alt="Screenshot 2026-02-24 171517" src="https://github.com/user-attachments/assets/2812bd34-b136-4a46-8926-42915d3d6b6e" /></p>

 ## Lab 3: Active Connections (TCP & ports)
 
- I used the `netstat -n` command to see live connections from my computer.
**What I observed:**
- **Proto (TCP):** Saw how reliable connections are established.
- **Local vs Foreign Address:** Understood how my computer talks to global servers.
- **Common Ports:** - Port `443`: Secure web traffic (HTTPS).
    - Port `5228/5222`: Google/Messaging background services
<p align="center"> <img width="50%" height="515" alt="Screenshot 2026-02-24 172511" src="https://github.com/user-attachments/assets/40ea4780-7d2f-4ff7-a945-7f4462088d98" /></p>

 ## Commands Learned:

  | Command | Purpose |
  | :----- | :----- |
  | `ipconfig/all` | Shows full IP details |
  | `netstat -n` | Shows Active connections|
  | `nslookup google` | Shows the address of Google |

 ## Task List

 - [X] Lab 1: IP Configuration
 - [x] Lab 2: Active Connections
 - [x] Concepts: IP,transport protocols,port numbers.


    ---------------       *LEARNING AND GROWING EVERYDAY*         --------------

## Lesson 3: Common Ports

Today, I learned about different well-known ports. To understand networking, it is crucial to know the **virtual doors** the source and the destination is using to transfer data smoothly. Ports ensure that the data transfer between two devices happens with accuracy. The port specific for receiving and sending emails, web browsers, assigning IP addresses to devices and much more other functions.


| Common Ports | Number | Function |
| :------- | :------ | :----- |
| FTP | 20/21 | File transfer between computers |
| HTTP | 80 | Unencrypted connection of web browser to web server |
| HTTPS | 443 | Secured connection Encrypted |
| SSH | 22 | Terminal connection for remote control with security |
| Telnet | 23 | For controling other device but unencrypted |
| DHCP | 67/68 | Assigning IP addresses to devices |
| SMTP | 25 | For sending emails |
| POP3 | 110 | For receiving emails |
| IMAP | 143 | For receiving multiple emails |
| DNS | 53 | Giving IP address to names |
| SNMP | 161/162 | For checking the devices in network system |
| LDAP | 389 | Query directories, logins |
| RDP | 3389 | Remote access to other device's screen |

  ## Lab 4:  Testing Port 80 HTTP in Packet Tracer

  I also did a lab to put my learning into action.
  - I connected a PC  and a server with a Copper cross cable.
  - I configured IP address to PC and server.
  - Went to desktop>web browser in PC, entered the IP of server.
  - BOOM!!! the server connected.
  - Also used the simulation mode to see the network NETWORKING.


   <p align="center"> <img width="50%" height="1071" alt="Screenshot 2026-02-25 210435" src="https://github.com/user-attachments/assets/6e056a6c-217d-43f6-ae22-c0f043184169" /></p>

   <p align="center"> <img width="50%" height="726" alt="Screenshot 2026-02-25 210521" src="https://github.com/user-attachments/assets/10b9c20f-2fe4-4887-b070-05214940865d" /> </p>


   --------------------- **Mindset of "I am stuck" to "I will figure it out."** ---------------------------

 ## Lesson 4: Network devices 

 Today, I learned about different network devices, their purpose and use. We use many devices for network communications such as routers, switch, firewall, SOHO(Small Office,Home Office) and sometimes devices with combined functionality.

 | Network Devices🚀 | Intro + Function |
 | :----- | :------ |
 | Router | Allows data traffic between different networks based on IP address. |
 | Switch | Allows data traffic based on MAC address |
 | Access point | Bridge between wired connection and wireless connection. |
 | Firewall | Security wall allowing or disallowing data traffic based on IP address, port numbers or protocols. |
 | Power Over Ethernet POE | provides network connection and power to the device with one single cable. |
 | Hub | Multi-port repeater, copies traffic between port, less efficient. |
 | Cable Modem | Single wire multiple transmission, uses Coaxial cable, DOCSIS. | 
 | DSL Modem | Digital Subscriber Line, uses telephone lines for communication. |
 | ONT | Optical Network Terminal, converts light signals from fibre optic to electric signal for devices. |
 | NIC | Network Interface Card allows connection of computer to network by converting digital signals into radio or light signals.|

 <p align="center"> TO BE CONTINUED.........🔜 </p>


