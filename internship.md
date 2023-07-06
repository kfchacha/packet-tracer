# RADEON NETWORKING PROJECT.

## CONTRIBUTORS.

1. Kenyatta Chacha.
2. Mutugi Craig Mutegi.

## PROJECT DESCRIPTION.

Radeon Company Ltd., a distinguished and prestigious US-owned establishment specializing in the domains of Banking and Insurance, has embarked upon an ambitious strategic venture to extend its exceptional services across the expansive and diverse African continent. In this remarkable pursuit, the company has meticulously chosen Nairobi, the vibrant and bustling capital city of Kenya, as the ideal locale to inaugurate its maiden branch within this promising region.

With the foresight to establish a solid foundation and ensure seamless operations, Radeon Company Ltd. has demonstrated its unwavering commitment by securing an eminent four-story edifice nestled within the heart of Nairobi. This carefully selected abode shall serve as the epicenter of the company's forthcoming operations, reflecting its enduring dedication to unparalleled service delivery and customer satisfaction.

In order to achieve optimal efficiency, steadfast connectivity, and uncompromising reliability, Radeon Company Ltd. aspires to tap into the unparalleled knowledge and ingenuity of a select group of accomplished final-year students hailing from a prestigious local university. Entrusted with the momentous responsibility of designing and implementing the intricate network infrastructure, these exceptional students are poised to harness their technical acumen and innovative prowess to shape a network that perfectly aligns with the exacting requirements of the esteemed company.

To fulfill this momentous undertaking, it is incumbent upon the designated students to meticulously assimilate and internalize the multifaceted demands articulated by Radeon Company Ltd. With a profound understanding of these imperatives, the aspiring network architects shall deftly craft an all-encompassing design that seamlessly integrates the company's myriad operational facets and propels them towards resounding success.

The network design and implementation process shall be executed with the utmost precision and meticulousness, taking into account the company's expansive scope and intricate operational workflows. Employing industry best practices, cutting-edge technologies, and a holistic approach, the students shall endeavor to fashion a network infrastructure that epitomizes reliability, security, scalability, and adaptability.

A comprehensive analysis of the company's requirements, conducted with unwavering diligence, shall provide the students with valuable insights into the exacting needs and aspirations of Radeon Company Ltd. This rigorous examination encompasses an in-depth evaluation of the network's bandwidth and throughput requirements, security protocols, data storage and retrieval mechanisms, voice and video communication systems, inter-departmental connectivity, virtual private networks (VPNs), and disaster recovery strategies.

Drawing upon a vast repertoire of technical skills, the students shall deftly configure and integrate a myriad of networking components, including robust routers, state-of-the-art switches, versatile firewalls, high-speed data links, and advanced security measures. The network's architecture shall be thoughtfully crafted to facilitate seamless communication and collaboration between the company's various departments, bolstering operational efficiency and fostering a synergistic work environment.

Emphasizing the paramount importance of data security and privacy, the students shall implement cutting-edge encryption protocols, multifactor authentication mechanisms, and intrusion detection and prevention systems. These indispensable security measures shall fortify the network against potential threats, safeguard sensitive information, and uphold the company's unwavering commitment to maintaining the highest standards of integrity and confidentiality.

Furthermore, the network infrastructure shall be architected to exhibit unparalleled scalability, providing a robust foundation upon which future expansion and growth can be effortlessly accommodated. Leveraging the power of virtualization technologies, such as virtual LANs (VLANs) and virtual private networks (VPNs), the students shall engineer a flexible and adaptable network that seamlessly caters to the evolving needs and aspirations of Radeon Company Ltd.

In recognition of the potential risks and uncertainties inherent in any business endeavor, the students shall proactively devise and implement comprehensive disaster recovery strategies. These protocols shall entail regular data backups, redundancy mechanisms, failover systems, and well-defined recovery procedures, ensuring business continuity in the face of unforeseen adversities and safeguarding the company's

valuable resources and critical operations.

The implementation of the network design shall be meticulously executed, adhering to industry-leading standards and best practices. Rigorous testing and validation procedures shall be undertaken to ensure the seamless integration of various components, optimal performance, and adherence to stringent quality benchmarks. The students shall collaborate closely with the company's IT team, sharing their expertise, insights, and recommendations to refine and enhance the network design, fostering a cohesive partnership aimed at achieving excellence.

In conclusion, as esteemed representatives of Radeon Company Ltd., the students entrusted with the task of designing and implementing the network infrastructure for the company's inaugural branch in Nairobi, Kenya, bear the weight of a monumental responsibility. Their expertise, dedication, and meticulous attention to detail shall pave the way for a robust, secure, and scalable network infrastructure that underpins the company's success in the African market. By leveraging their technical acumen, innovative spirit, and commitment to excellence, the students shall shape a network that embodies the essence of reliability, connectivity, and operational efficiency, cementing Radeon Company Ltd.'s position as a pioneering force in the realms of Banking and Insurance.

### LIST OF DEVICES USED IN THIS PROJECT.

1. 3 servers namely: DHCP, HTTP, and email server.
2. 2 Admin PC'S
3. Personal computers and printers for each department.
4. Multilayer switches
5. Routers
6. Access points.

### TECHNOLOGIES IMPLEMENTED.

1. Creating a network topology using Cisco Packet Tracer.
2. Hierarchical Network Design.
3. Connecting Networking devices with Correct cabling.
4. Configuring Basic device settings.
5. Creating VLANs and assigning ports VLAN numbers.
6. Subnetting and IP Addressing.
7. Configuring Inter-VLAN Routing on the Multilayer switches (Switch Virtual Interface).
8. Configuring Dedicated DHCP Server device to provide dynamic IP allocation.
9. Configuring SSH for secure Remote access.
10. Configuring OSPF as the routing protocol.
11. Configuring switchport security or Port-Security on the switches.
12. Configuring WLAN or wireless network (Cisco Access Point).
13. Host Device Configurations.
14. Test and Verifying Network Communication.

### REQUIREMENTS.

- Use a software modeling tool to visualize the network topology (Use Hierarchical Network Design)
- Software Modelling Tools: MS Visio, Visual Paradigm, or Draw.io for modeling network design.
Use any of the following network simulation software to implement the above topology.
- Simulation software: Cisco Packet tracer or GNS3 for design and implementation.
- Use O.S.P.F ( Open Shortest Path First) as the routing protocol to advertise routes.
- Each department is required to have a wireless network for the users.
- Each department except the server room will be anticipated to have around 60 users both wired and wireless users.
- Host devices in the network are required to obtain IPv4 addresses automatically.
- Devices in all the departments are required to communicate with each other.
- Create HTTP, and E-mail servers.
- All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.
- Configure SSH in all the routers for remote login.
- Configure the basic configuration of the devices: Hostnames, Line Console and Enable passwords, Banner messages Disable domain IP lookup, encrypt all configured passwords.
- Each department should be in a different VLAN and subnetwork; VLANs you will use in your case, e.g. 10, 20, 30… etc..
- Planning of IP Addresses: You have been given 192.168.10.0 as the base address for this network. Do subnetting based on the number of hosts in every department as provided above. Identify subnet mask, useable IP address range, and broadcast address for each subnet.
- End Device Configurations: Configure all the end devices in the network with the appropriate IP address based on the calculations above.
- Configure port-security: Use sticky command to obtain MAC Address and Violation mode of the shutdown.
- Test and Verifying Network Communication.
  
  ### IMPLEMENTATION.
   
   We executed this project as per the floor plan of the main building with switches on each floor establishing communication to the routers thus enabling cross network communication. This is achieved through multi-layer switches because they can perform routing functions at high speeds and inspect deeper into the protocol description unit. This is useful in networks where there is a need for faster routing and switching.

   #### CONFIGURATION STEPS.

   1. basic settings to all devices plus ssh on the routers plus 13 switches.
   2. VLANS assignments plus all access and trunk reports.
   3. Switchport security to all 13 networks.
   4. Subnetting and I.P addressing.
   5. OSPF on all routers and switches.
   6. Static IP addressing to server room devices
   7. DHCP server configurations.
   8. Inter- VLAN routing on all switches and ip dhcp helper addresses.
   9. Wireless network configurations.
   10. Verifying and Testing the network.
   
   ### CONSTRAINTS.

   The constraints that were faced during development include lack of knowledge about networking protocols such as OSPF which was introduced later than others like TCP
   You, being very cautious, decide to simulate the topology on Cisco Packet Tracer in order to optimally design the network considering the number of devices (switches, routers etc.) used to maximize the profit margins of your company. 

   ### DESIGNED NETWORK.
   #### 1. CISCO PACKET TRACER
   This is the cisco packet tracer representation.

   ![Network diagram](network.png)
   #### 2. MICROSOFT REPRESENTATION.
   Here's how we designed our Microsoft Visio presentation using hierarchical network design methodology :



