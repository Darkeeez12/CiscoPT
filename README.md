# CiscoPT

This project presents a comprehensive, multi-floor campus LAN network infrastructure designed and simulated using Cisco Packet Tracer. The objective was to create a scalable and robust network to support a diverse user base, including academic staff, administrative personnel, and students.

Key Features:
- Star-Topology Design: The network utilizes a star-topology, linking individual departmental switches to a centralized core switch and router to ensure efficient data flow and management.

- Hybrid IP Addressing: A hybrid addressing scheme was implemented, featuring manual static IPs for every network devices (mainly PCs) and a dynamically managed DHCP pool for end-user devices and two dummy PC, optimizing both control and scalability.

- On-Premises Services: On-premises servers (including DHCP, Apache web, and SMTP/IMAP mail) were deployed to provide essential network services, ensuring seamless service discovery and high availability within the campus environment.

- Network Validation: The design was carefully tested and validated through Packet Tracer simulations, confirming stable connectivity without any device left alone, minimal packet loss, and consistent low latency across the network.

Technologies Used:
- Cisco Packet Tracer
- Cisco Switches & Routers
- DHCP
- Apache web server
- SMTP/IMAP mail server
