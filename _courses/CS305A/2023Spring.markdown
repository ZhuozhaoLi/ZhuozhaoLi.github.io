---
layout: page
title: CS305A Computer Networks
description: "2023 Spring Syllabus"
---


##### **Instructors**

[Zhuozhao Li](https://zhuozhaoli.github.io/), 李卓钊
- Office: RM 516, South Tower, CoE Building (工学院南楼516)
- Office hour: Friday 3:00-5:00PM, or email to schedule an appointment.


Qing Wang, 王晴 (Lab)

##### **Course Descriptions**

Using the Internet as a vehicle, this course introduces the underlying concepts and principles of modern computer networks, with emphasis on protocols, architectures, and implementation issues. We will teach how to implement network applications (e.g., e-mail, FTP) using the existing network protocols and architectures and how/why these protocols and architectures work by using the layered organization of the Internet in a top-down fashion: application, transport, network, data link, and physical layers. The course will also cover advanced topics such as software-defined networking and wireless and mobile networks.

##### **Course Materials**

- Textbook: Computer Networking: A Top Down Approach, J. Kurose & K. Ross, Pearson, 8th Edition, 2020
<img style="float: right;" src="/assets/img/textbook-8th-edition.jpg" alt="drawing" width="150"/>

- All the lecture and lab slides


##### **Course Workloads**

There will be three Q&A homework, two programming assignments, one project, one midterm, and one final examination. 

##### **Grading Policy** (Tentative)

<!--- The grading policy may subject to minor changes depending on the overall performance.-->

- Homework and programming assignments, 15%

- Attendance and lab practice, 10%

- Project, 15%

- Midterm exam, 30%

- Final exam, 30%

##### **Academic Integrity/Academic Dishonesty**

I expect students to be honest and not cheat on their assignments, project, or exams. 
Please refer to the [plagiarism policy](/assets/Plagiarism_Policy.pdf) (**IMPORTANT!!! Please READ carefully!!!**) of CSE department for more details.
You MUST sign the commitment letter and submit on the Sakai/Blackboard system.

##### **Course Policies**

- No late assignment will be accepted.
- Unless some special situations (e.g., medical leave) which will be reviewed by all the instructors.
- The following excuses will NOT be approved for late submissions: computer crashes, disk crashes, accidental file deletions, lab computer unavailability, and the like. There will be no reply for this sort of late assignment submission requests.

##### **[Schedule](#schedule) (Tentative)** {#schedule}

<style>
td, th {
  border: 1px solid #ddd;
  padding: 8px;
  font-size: 5pt;
}

tr:nth-child(even){background-color: #f2f2f2;}

tr:hover {background-color: #ddd;}

th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #a6a6a6;
  color: white;
}
</style>

Please refer to Sakai for the lecture and lab materials.

Acronyms: HW = Homework, PA = Programming Assignment, PROJ = Project



| **Week** |           **Date**          | **Contents**                                                                                                                                                                                  |      **Events**     |
|:--------:|:---------------------------:|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------:|
| 1        | Feb. 15, 2023               | [Lecture] Course overview<br>[Lab] Introduction to common tools of network monitoring and diagnosis                                                                                           |                     |
| 2        | Feb. 22, 2023               | [Lecture] Introduction to Internet, networks, and protocols (textbook: Chapter 1)<br>[Lab] Introduction to Python and Wireshark                                                               |                     |
| 3        | Mar. 1, 2023                | [Lecture] Application layer 1 (textbook: Chapter 2.1-2.3): <br>principles of application-layer protocols, WWW, HTTP<br>[Lab] Introduction HTTP                                                |                     |
| 4        | Mar. 8, 2023                | [Lecture] Application layer 2 (textbook: Chapter 2.4-2.5): DNS, Email<br>[Lab] Advanced HTTP and socket programming                                                                           | HW1 out             |
| 5        | Mar. 15, 2023               | [Lecture] Application layer 3: P2P, Video streaming, socket programming<br>[Lab] Introduction to DNS                                                                                          | PA1 out             |
| 6        | Mar. 22, 2023               | [Lecture] Transport layer 1 (textbook: Chapter 3.1-3.3): <br>transport-layer services and principles, multiplexing and demultiplexing applications, UDP<br>[Lab] Introduction to CDN          | HW1 due             |
| 7        | Mar. 29, 2023               | [Lecture] Transport layer 2 (textbook: Chapter 3.4-3.5): <br>reliable of data transfer, TCP<br>[Lab] Introduction to TCP and UDP                                                              | PA1 due<br>HW2 out  |
| 8        | Apr. 12, 2023               | [Lecture] Transport layer 3 (textbook: Chapter 3.6-3.7): <br>flow control, congestion control<br>[Lab] Introduction to WebSocket and TLS                                                       |                     |
| 9        | Apr. 19, 2023               | [Lecture] Midterm exam. Exact time to be decided.<br>[Lab] Introduction to DHCP and packet tracer                                                                                             | HW2 due             |
| 10       | Apr. 23, 2023               | [Lecture] Network layer-data plane 1 (textbook: Chapter 4.1-4.2)<br>[Lab] Introduction to routing                                                                                             | PA2 out<br>PROJ out |
| 11       | Apr. 26, 2023               | [Lecture] Network layer-data plane 2 (textbook: Chapter 4.3-4.4): <br>Internet Protocol, generalized forwarding, SDN<br>[Lab] Introduction to IP and ICMP                                     |                     |
| 12       | May 6, 2023<br>(Labor Days) | [Lecture] Network layer-control plane 1 (textbook: Chapter 5.1-5.4): <br>Link-State, Distance-Vector, OSPF, BGP<br>[Lab] Introduction to NAT, RIP, OSPF                                       | PA2 due             |
| 13       | May 10, 2023                | [Lecture] Network layer-control plane 2 (textbook: Chapter 5.5-5.7): <br>SDN control plane, ICMP, SNMP<br>[Lab] Introduction to MAC, ARP and Switch                                           | HW3 out             |
| 14       | May 17, 2023                | [Lecture] Link layer, LANs 1: <br>error detection, correction, multiple access protocols<br>[Lab] Layer 3 switch                                                                              |                     |
| 15       | May 24, 2023                | [Lecture] Link layer, LANs 2 (textbook: Chapter 6.4-6.7)<br>[Lab] Router (H3C MSR810/830/360-4)                                                                                               | HW3 due             |
| 16       | May 31, 2023                | [Lecture] Wireless and mobile network, Review<br>[Lab] Project presentation                                                                                                                   | PROJ DUE            |