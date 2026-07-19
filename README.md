**Day 1 – WhiteHat Company Training**

Today was my first day of training at WhiteHat Company. The session started with a warm welcome from the team, and we were introduced to the company, its mission, values, and work culture. It was a great opportunity to learn about how the organization operates and what is expected during the training.
The trainers also explained the complete 45-day training schedule, including the learning objectives, projects, assignments, and milestones that we will complete throughout the program. They gave us an overview of the technologies we will learn and the skills we are expected to develop.Overall, the first day was informative and motivating. I am excited to begin this learning journey and look forward to gaining new knowledge and practical experience during the training.

#Day 2 – Computer Networks, Topologies, Protocols, Ports, and OSI Model

On the second day of training, we learned the fundamentals of **Computer Networks**, different **network topologies**, **communication protocols**, **port numbers**, and the **OSI (Open Systems Interconnection) Model**. These concepts helped us understand how computers communicate and exchange data over a network.

** Computer Network**

A **computer network** is a collection of interconnected devices such as computers, servers, printers, and other hardware that communicate with each other to share data, resources, and services. Networks can be small (LAN) or large (WAN), depending on their coverage area.

---

## Network Topologies

A **network topology** refers to the physical or logical arrangement of devices in a network. Different topologies are used based on the requirements of performance, reliability, and cost.

### 1. Bus Topology

In a **Bus Topology**, all devices are connected to a single communication cable called the **backbone**.

**Advantages:**

* Easy to install and configure.
* Cost-effective because it requires less cable.
* Suitable for small networks.

**Disadvantages:**

* If the backbone cable fails, the entire network stops working.
* Performance decreases as more devices are added.
* Troubleshooting can be difficult.

---

### 2. Star Topology

In a **Star Topology**, every device is connected to a central device such as a **switch** or **hub**.

**Advantages:**

* Easy to manage and troubleshoot.
* Failure of one device does not affect others.
* Provides better performance and scalability.

**Disadvantages:**

* If the central switch or hub fails, the entire network becomes unavailable.
* Requires more cabling than Bus Topology.

---

### 3. Mesh Topology

In a **Mesh Topology**, every device is directly connected to every other device.

**Advantages:**

* Highly reliable because multiple paths are available.
* Excellent fault tolerance.
* High security and fast communication.

**Disadvantages:**

* Expensive due to the large number of cables.
* Complex installation and maintenance.

---

### 4. Ring Topology

In a **Ring Topology**, each device is connected to two neighboring devices, forming a circular structure.

**Advantages:**

* Data flows in an organized manner.
* Equal access for all devices.
* Performs well under moderate traffic.

**Disadvantages:**

* Failure of one device or cable can disrupt the entire network.
* Adding or removing devices can interrupt communication.

---

### 5. Tree Topology

A **Tree Topology** combines the features of **Bus** and **Star** topologies. It has a hierarchical structure with multiple star networks connected to a central backbone.

**Advantages:**

* Easy to expand.
* Supports large networks.
* Simplifies network management.

**Disadvantages:**

* Backbone failure affects the entire network.
* More expensive than Bus or Star topology.

---

### 6. Hybrid Topology

A **Hybrid Topology** is a combination of two or more different network topologies.

**Advantages:**

* Flexible and scalable.
* Highly reliable.
* Can be customized according to organizational needs.

**Disadvantages:**

* Complex design.
* Higher installation and maintenance costs.

---

# Day 3 Network Protocols

A **protocol** is a set of rules that defines how data is transmitted and received over a network. Protocols ensure reliable communication between devices.

Examples include:

* HTTP
* HTTPS
* FTP
* SMTP
* TCP
* UDP

---

# Port Numbers

A **port number** is a logical communication endpoint that allows multiple network services to run on the same device.

Some common port numbers are:

| Protocol | Port Number |
| -------- | ----------: |
| HTTP     |          80 |
| HTTPS    |         443 |
| FTP      |          21 |
| SSH      |          22 |
| SMTP     |          25 |
| DNS      |          53 |
| POP3     |         110 |
| IMAP     |         143 |

---

# TCP (Transmission Control Protocol)

**TCP** is a connection-oriented protocol that establishes a connection before transmitting data.

### Features:

* Reliable communication.
* Guarantees data delivery.
* Detects and retransmits lost packets.
* Maintains the correct order of data.
* Used in web browsing, email, and file transfers.

# UDP (User Datagram Protocol)

**UDP** is a connectionless protocol that sends data without establishing a connection.

### Features:

* Faster than TCP.
* Lower overhead.
* Does not guarantee data delivery.
* Suitable for real-time applications like video streaming, online gaming, and voice calls.

---

# Difference Between TCP and UDP

| TCP                         | UDP                              |
| --------------------------- | -------------------------------- |
| Connection-oriented         | Connectionless                   |
| Reliable                    | Less reliable                    |
| Slower                      | Faster                           |
| Error checking and recovery | No recovery mechanism            |
| Used for web, email, FTP    | Used for streaming, gaming, VoIP |

---

# OSI (Open Systems Interconnection) Model

The **OSI Model** is a seven-layer framework that explains how data travels from one device to another over a network.

### Layer 7 – Application Layer

* Closest to the end user.
* Provides network services to applications.
* Examples: HTTP, HTTPS, FTP, SMTP.

### Layer 6 – Presentation Layer

* Translates data between different formats.
* Handles encryption, decryption, and data compression.

### Layer 5 – Session Layer

* Establishes, manages, and terminates communication sessions between devices.

### Layer 4 – Transport Layer

* Ensures reliable data delivery.
* Performs segmentation, flow control, and error recovery.
* Protocols: TCP and UDP.

### Layer 3 – Network Layer

* Determines the best path for data transmission.
* Handles logical addressing using IP addresses.
* Device: Router.

### Layer 2 – Data Link Layer

* Transfers data between devices on the same network.
* Uses MAC addresses.
* Detects transmission errors.
* Device: Switch.

### Layer 1 – Physical Layer

* Responsible for transmitting raw bits over physical media.
* Includes cables, connectors, hubs, and electrical signals.

# Day 3 – Subnetting and Hosts

Today, I learned the fundamentals of **Subnetting** and **Hosts**, which are essential concepts in computer networking and CCNA.

## What is an IP Address?

An IP (Internet Protocol) address is a unique identifier assigned to every device connected to a network. An IPv4 address consists of 32 bits divided into four octets (e.g., `192.168.1.10`).

## Network ID and Host ID

An IP address is divided into two parts:

* **Network ID** – Identifies the network.
* **Host ID** – Identifies the specific device within that network.

The subnet mask determines which portion of the IP address belongs to the network and which belongs to the host.

## What is a Host?

A host is any device connected to a network, such as:

* Computer
* Laptop
* Mobile phone
* Printer
* Server
* Router

Each host requires a unique IP address to communicate within the network.

## Subnet Mask and CIDR

A subnet mask separates the network portion from the host portion of an IP address.

Example:

* Subnet Mask: `255.255.255.0`
* CIDR Notation: `/24`

CIDR notation indicates how many bits are allocated to the network portion of the IP address.

## What is Subnetting?

Subnetting is the process of dividing a large network into multiple smaller networks called **subnets**. It helps improve network performance, enhances security, and makes IP address management more efficient.

For example, a `/24` network can be divided into four `/26` subnets, with each subnet supporting 62 usable host addresses.

## Host Calculation

The number of usable hosts in a subnet is calculated using the formula:

**Usable Hosts = 2^(Host Bits) − 2**

The subtraction of 2 accounts for:

* The **Network Address** (first IP address)
* The **Broadcast Address** (last IP address)

These addresses cannot be assigned to hosts.

## Network and Broadcast Addresses

* **Network Address:** The first IP address in a subnet that identifies the subnet itself.
* **Broadcast Address:** The last IP address in a subnet used to send data to all devices within that subnet.
* **Usable Host Range:** All IP addresses between the network and broadcast addresses.

## Common CIDR Values

| CIDR | Total IP Addresses | Usable Hosts |
| ---- | -----------------: | -----------: |
| /24  |                256 |          254 |
| /25  |                128 |          126 |
| /26  |                 64 |           62 |
| /27  |                 32 |           30 |
| /28  |                 16 |           14 |
| /29  |                  8 |            6 |
| /30  |                  4 |            2 |

# Day 4 - Hashing, Encryption & Encoding

## Introduction

Today I learned three important concepts used in cybersecurity and software development:

* **Hashing**
* **Encryption**
* **Encoding**

Although these terms are often used interchangeably, they serve completely different purposes.

---

# 1. Hashing

## Definition

Hashing is the process of converting data of any size into a fixed-size string called a **hash value** or **digest** using a mathematical algorithm.

Hashing is a **one-way process**, meaning the original data cannot be recovered from the hash.

### Example

Original Text:

```text
Hello123
```

SHA-256 Hash:

```text
6f5902ac237024bdd0c176cb93063dc4...
```

Even changing one character completely changes the hash.

Example:

```text
Hello123
```

and

```text
hello123
```

produce completely different hashes.

---

## Characteristics

* One-way process
* Fixed output length
* Fast to generate
* Same input always gives same output
* Small input changes create a completely different hash

---

## Common Hashing Algorithms

* MD5 (Not secure)
* SHA-1 (Deprecated)
* SHA-256
* SHA-512
* bcrypt
* Argon2

---

## Uses of Hashing

### Password Storage

Instead of storing passwords directly:

Wrong

```text
Password = hello123
```

Correct

```text
Password Hash = SHA256(hello123)
```

When the user logs in:

1. User enters password.
2. System hashes the entered password.
3. Compares it with the stored hash.
4. If both match, access is granted.

---

### File Integrity

When downloading software, companies provide a hash.

Example:

```
setup.exe

SHA256:
A2D93F4...
```

After downloading:

* Generate the file hash.
* Compare it with the provided hash.
* If both match, the file has not been modified.

---

### Digital Signatures

Hashing is used before creating digital signatures because hashing is faster than signing large files directly.

---

## Advantages

* Fast
* Secure verification
* Detects data changes
* Fixed-size output

---

## Disadvantages

* Cannot recover original data
* Weak algorithms like MD5 and SHA-1 are vulnerable to attacks

---

# 2. Encryption

## Definition

Encryption converts readable data (**plaintext**) into unreadable data (**ciphertext**) using a key.

Unlike hashing, encryption is **reversible**.

The original data can be recovered using the correct decryption key.

---

## Process

```
Plain Text
      ↓
Encryption Algorithm + Key
      ↓
Cipher Text
      ↓
Decryption Key
      ↓
Original Plain Text
```

---

## Example

Plain Text:

```
My Password = hello123
```

Encrypted:

```
Xf92@ad89#Lm
```

After decryption:

```
My Password = hello123
```

---

## Types of Encryption

### Symmetric Encryption

Uses the **same key** for encryption and decryption.

Examples:

* AES
* DES
* Blowfish

Advantages:

* Very fast
* Suitable for encrypting large amounts of data

Disadvantages:

* Key must be shared securely.

---

### Asymmetric Encryption

Uses **two keys**:

* Public Key
* Private Key

Examples:

* RSA
* ECC

Advantages:

* Secure key exchange
* Digital signatures

Disadvantages:

* Slower than symmetric encryption

---

## Uses of Encryption

* HTTPS websites
* Online banking
* WhatsApp messages
* VPNs
* Secure emails
* Cloud storage

---

## Advantages

* Protects confidential data
* Data can be recovered with the correct key
* Prevents unauthorized access

---

## Disadvantages

* Requires secure key management
* Can be slower than hashing

---

# 3. Encoding

## Definition

Encoding converts data into another format so that different systems can store or transmit it correctly.

Encoding is **not** a security mechanism.

It is easily reversible.

---

## Example

Text:

```
Hello
```

Base64 Encoding:

```
SGVsbG8=
```

Base64 Decoding:

```
Hello
```

---

## Common Encoding Methods

* Base64
* ASCII
* Unicode
* UTF-8
* URL Encoding

---

## Uses of Encoding

* Sending email attachments
* Storing binary data as text
* Web URLs
* APIs
* JSON data transfer

---

## Advantages

* Easy data transfer
* Compatible across different systems
* Prevents data corruption during transmission

---

## Disadvantages

* Provides no security
* Anyone can decode the data

---

# Difference Between Hashing, Encryption and Encoding

| Feature    | Hashing              | Encryption              | Encoding           |
| ---------- | -------------------- | ----------------------- | ------------------ |
| Purpose    | Verify integrity     | Protect confidentiality | Change data format |
| Reversible | No                   | Yes                     | Yes                |
| Uses Key   | No                   | Yes                     | No                 |
| Security   | Yes                  | Yes                     | No                 |
| Main Use   | Passwords, Integrity | Secure Communication    | Data Transmission  |

---

# Real-Life Examples

## Hashing

Instagram stores user passwords as hashes instead of plain text.

---

## Encryption

When you visit an HTTPS website, the communication between your browser and the server is encrypted.

---

## Encoding

When sending an image through email, it is often encoded using Base64 before transmission.

---

# Key Takeaways

* **Hashing** is used for password storage and verifying data integrity. It is a one-way process.
* **Encryption** protects sensitive information and allows authorized users to recover the original data using a key.
* **Encoding** changes the format of data for storage or transmission and is not meant for security.
* Although all three transform data, their purposes are completely different.

**Day 5**
Revision of subneting topics and done practice.

**Day 6**
PD class and Debate compition

**Day 7**
Project work and revision of previous topics.

**Day 8**
Test of all the previously done topics.

**Day 9**
revision of subnetting topics


**Day 10**
During today's training session, we downloaded and installed Cisco Packet Tracer on our systems. We also learned the basic installation process and its purpose in networking.


**Day 11**
– Cisco Packet Tracer: Network Connection and Device Configuration

During today's training session, we learned how to create a basic network topology in Cisco Packet Tracer using PCs, a Switch, and a Router. We connected the devices using the appropriate cables and established communication between them.

We also learned how to configure the following devices:

PCs: Assigned IP addresses, subnet masks, and default gateways.
Switch: Performed basic switch configuration, including setting the hostname and accessing configuration mode.
Router: Configured interfaces with IP addresses, enabled the interfaces, and performed basic router configuration.

After completing the configurations, we tested the network connectivity using the ping command and verified that the devices were communicating successfully.


**Day 12**
There are Interbatch compegtition on saturday, Debate, coding quiz and i participate in coding quiz.

**Day 13**
On this day we configure V lan and sends message from one PC to another PC. Also configure the router and server.

**Day 14** 
Leave

I was on leave today and did not attend the training session. Therefore, I did not participate in any practical activities or learning tasks on this day.


**Day 15 **
– Switch Configuration and Basic Commands

During today's training session, we learned about the basic configuration of a network switch in Cisco Packet Tracer. We practiced accessing the switch through the Command Line Interface (CLI) and executed various basic commands.

The commands covered included:

Entering privileged EXEC mode (enable)


Entering global configuration mode (configure terminal)

Setting the switch hostname (hostname)

Configuring console password

Configuring enable password

Saving the configuration (copy running-config startup-config)

Viewing the current configuration (show running-config)

Displaying VLAN information (show vlan brief)

**Day 16**

Kali Linux Installation and Basic Commands

During today's training session, we learned how to download and install Kali Linux. The installation process and system requirements were explained, and we successfully set up Kali Linux on our systems.

After the installation, we practiced some basic Linux commands, including:

pwd – Display the current working directory.

ls – List files and directories.

cd – Change the current directory.

mkdir – Create a new directory.

rmdir – Remove an empty directory.

touch – Create a new file.

cp – Copy files and directories.

mv – Move or rename files.

rm – Delete files.

cat – Display the contents of a file.

clear – Clear the terminal screen.

**Day 17**

– OWASP Top 10 and Basic Kali Linux Commands

During today's training session, we were introduced to the OWASP Top 10, which lists the most critical web application security risks. The trainer explained the purpose of OWASP and discussed common vulnerabilities such as:

Broken Access Control

Cryptographic Failures

Injection

Insecure Design

Security Misconfiguration

Vulnerable and Outdated Components

Identification and Authentication Failures

Software and Data Integrity Failures

Security Logging and Monitoring Failures

Server-Side Request Forgery (SSRF)

We also practiced some basic Kali Linux commands, including:

pwd – Display the current directory.

ls – List files and folders.

cd – Change the directory.

mkdir – Create a new directory.

touch – Create a new file.

cat – Display the contents of a file.

clear – Clear the terminal screen.

ifconfig / ip a – Display network interface information.

**Day 18 **

PD class 

**Day 19**

– Introduction to Metasploit Framework and Basic Commands

During today's training session, we learned about the Metasploit Framework, one of the most widely used penetration testing tools for identifying and validating security vulnerabilities in a controlled and authorized environment.

The trainer explained the purpose of Metasploit, its interface, and the basic workflow used during security assessments. We also practiced several basic Metasploit commands, including:


msfconsole – Start the Metasploit Framework.

help – Display available commands.

search – Search for exploit, auxiliary, or payload modules.

use – Select a module to work with.

show options – Display the required options for the selected module.

set – Set the value of a required option (such as target host or port).

show payloads – Display compatible payloads.

set payload – Select a payload for the module.

run or exploit – Execute the selected module.

back – Return to the previous menu.

info – Display detailed information about the selected module.

sessions – View active sessions.

exit – Close the Metasploit console.

The importance of using Metasploit only in authorized and legal penetration testing environments was also emphasized.

**Day 20**

– Wireshark and Packet Sniffing

During today's training session, we learned about Wireshark, a network protocol analyzer used to capture and analyze network traffic. The trainer explained the concept of packet sniffing and demonstrated how Wireshark captures data packets transmitted over a network.

We also learned how to:

Launch Wireshark and select a network interface.
Start and stop packet capture.
Capture live network traffic.
Apply basic filters (such as http, tcp, udp, icmp, and dns) to analyze specific packets.
Examine packet details, including source IP address, destination IP address, protocol, and packet contents.
Save and reopen captured packet files for later analysis.

The trainer also discussed the importance of using Wireshark responsibly and only on networks where monitoring is authorized.

