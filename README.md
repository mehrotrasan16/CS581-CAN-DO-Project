# CS581-CAN-DO-Project

This is the page for our semester project for CS581 - Embedded Machine Learning. 

Sanket Mehrotra - Graduate Student - Department of Computer Science - Colorado State University - sanketm@colostate.edu

Kaustubh Jawanjal - Graduate Student - Electrical and Computer Engineering Department - CSU

### CAN DO - Controller Area Network (CAN) - Discrepancy/Divergence/Deviation Observer(TBD)

Controller Area Network (CAN) is a serial network technology that was originally designed for the automotive industry, especially for European cars, but has also become a popular bus in industrial automation as well as other applications. The CAN bus is primarily used in *embedded systems*, and as its name implies, is a network technology that provides fast communication among *microcontrollers* up to __real-time__ requirements, eliminating the need for the much more expensive and complex technology of a Dual-Ported RAM.

CAN messages are broadcast from a transmitter to the other nodes on a bus, and do not contain information about the source and destination address for validation. Therefore, an attacker can easily attack this network via injection or falsifying information to lead to system malfunctions

We thank the team at the Hacking Countermeasure Research lab, at the Korea University at Seoul for kindly sharing their published dataset of CAN network messages(with different types of simulated attacks)

### Refs:

[1] [Copper Hill Tech](https://copperhilltech.com/a-brief-introduction-to-controller-area-network/#:~:text=Controller%20Area%20Network%20(CAN)%20is,as%20well%20as%20other%20applications.)

[2] Hyunsung Lee, Seong Hoon Jeong and Huy Kang Kim, "OTIDS: A Novel Intrusion Detection System for In-vehicle Network by using Remote Frame", PST (Privacy, Security and Trust) 2017

[3] [CAN intrusion dataset](https://sites.google.com/a/hksecurity.net/ocslab/Dataset/CAN-intrusion-dataset)
