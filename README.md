# Comptia-A-Plus-Labs
Practical labs and notes for my IT journey. Training to become a Cyber Professionalist.
# My-IT-Journey

## Lesson 1: MDM and Mobile devices

Today I finished Professer Messer's video on MDM.

### Learned: How to manage 100 devices on MDM.

### Key Concepts:

* Cloud sync, Data roaming, Remote wipe.

# Lab 1: MDM Configuration Lab

Today I learned about how a company controls 1000 of devices at the same time by taking Professor Messer's lecture and Miradore walkthrough.

## Key concepts learned:
* Enrollment: How to enroll the device via email or QR code.
* Profiles and Policies: How to apply rules ( disabling the camera, enabling the 6-digit password).
* Remote commands: How to control the devices remotely and wipe the data.
* BYOD and COPE: Learned the difference between Bring Your Own Device and Corporate owned,Personally Enabled.

## Tool Used:Miradore

## Policy stimulation:
  
<img width="1900" height="1001" alt="Screenshot 2026-02-18 151716" src="https://github.com/user-attachments/assets/14c46077-7b0e-4ba5-8376-6f3e67ccbfc6" />
<img width="954" height="479" alt="action log" src="https://github.com/user-attachments/assets/f517fd34-7a47-4dfb-b717-9336cfbc46ca" />
<img width="953" height="472" alt="enroll device" src="https://github.com/user-attachments/assets/1d579969-fadf-41e5-a436-bad03f43c42f" />
<img width="950" height="470" alt="infrastructure diagram" src="https://github.com/user-attachments/assets/93004d04-20e2-4635-9fe5-a4e763cba272" />

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
<img width="1297" height="788" alt="Screenshot 2026-02-24 171517" src="https://github.com/user-attachments/assets/2812bd34-b136-4a46-8926-42915d3d6b6e" />

 ## Lab 3: Active Connections (TCP & ports)
 
- I used the `netstat -n` command to see live connections from my computer.
**What I observed:**
- **Proto (TCP):** Saw how reliable connections are established.
- **Local vs Foreign Address:** Understood how my computer talks to global servers.
- **Common Ports:** - Port `443`: Secure web traffic (HTTPS).
    - Port `5228/5222`: Google/Messaging background services
<img width="1000" height="515" alt="Screenshot 2026-02-24 172511" src="https://github.com/user-attachments/assets/40ea4780-7d2f-4ff7-a945-7f4462088d98" />

    ---------------       *LEARNING AND GROWING EVERYDAY*         --------------

 


