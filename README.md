**Day 1 – WhiteHat Company Training**

Today was my first day of training at WhiteHat Company. The session started with a warm welcome from the team, and we were introduced to the company, its mission, values, and work culture. It was a great opportunity to learn about how the organization operates and what is expected during the training.
The trainers also explained the complete 45-day training schedule, including the learning objectives, projects, assignments, and milestones that we will complete throughout the program. They gave us an overview of the technologies we will learn and the skills we are expected to develop.Overall, the first day was informative and motivating. I am excited to begin this learning journey and look forward to gaining new knowledge and practical experience during the training.

# Day 2 – Computer Networks, Topologies, Protocols, Ports, and OSI Model

On the second day of training, we learned the fundamentals of **Computer Networks**, different **network topologies**, **communication protocols**, **port numbers**, and the **OSI (Open Systems Interconnection) Model**. These concepts helped us understand how computers communicate and exchange data over a network.

## Computer Network

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

# Network Protocols

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

## Conclusion

Day 2 provided a strong foundation in networking concepts. We learned how different network topologies are structured, how protocols and port numbers enable communication, the differences between TCP and UDP, and how the seven layers of the OSI Model work together to ensure efficient and reliable data transmission across networks.
