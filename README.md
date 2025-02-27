# osTicketing-project
# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Installation Step by step </h1>

I setup an Azure Virtual Machine (VM) setup for labuser1. The VM is currently running Windows 10 Pro in the West US 3 (Zone 1) region and is part of the VMTTEST-LAB resource group under Azure subscription 1. It was configured with a Standard D2s v3 size, featuring 2 vCPUs and 8 GiB of memory, making it suitable for moderate workloads. In terms of networking, it has a public IP address of 20.168.1.46 and a private IP address of 10.0.0.4, operating within the labuser1-vnet/default virtual network. The VM was, running version 2.7.14191.1139, and hibernation disabled. From the Azure portal, we have several management options available, including connecting, restarting, stopping, deleting, and configuring networking settings. Overall, this VM is fully operational and ready for use."

<img width="1440" alt="Virtual machine setup in Azure" src="https://github.com/user-attachments/assets/c12ea0b1-ecec-4aad-959b-d1505c393da4" />

<h2>Video Demonstration</h2>

This is a video demonstration on how the osTicket was installed and exaples of ticket creation and resolution



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (Pro)

<h2>List of Prerequisites performed </h2>

- Install Operating systems
- Install webserver
- Install PHP and Required Extensions
- Install MySQL
- Create a Database for osTicket
  
<h2>Installation Steps</h2>


OS AND WEBSERVER INSTALLATION

<img width="1440" alt="Virtual machine setup in Azure" src="https://github.com/user-attachments/assets/481ef1fe-a7d7-435f-8776-4119dba41840" />


PING VM PRIVATE IP ADDRESS

<img width="861" alt="Screen Shot 2025-02-26 at 5 03 51 PM" src="https://github.com/user-attachments/assets/6719823a-6350-4d32-9435-042b66fe3494" />


OS TICKET HOME

<img width="1440" alt="Screen Shot 2025-02-27 at 3 33 36 PM" src="https://github.com/user-attachments/assets/262387cc-0ee2-4765-b246-8d5e2cf4446c" />


REGISTER PHP MANAGER

<img width="1440" alt="Screen Shot 2025-02-27 at 3 33 56 PM" src="https://github.com/user-attachments/assets/2dfb2c6f-2c08-4a95-9b7b-323581b4caa2" />


MYSQL INSTALLATION

<img width="1440" alt="Screen Shot 2025-02-27 at 3 41 28 PM" src="https://github.com/user-attachments/assets/ea5aa63c-c4f8-46b8-b6f2-65d4696c1751" />


osTICKET INSTALLED

<img width="1220" alt="Screen Shot 2025-02-26 at 6 03 14 PM" src="https://github.com/user-attachments/assets/5553dda1-fbda-4aa6-8765-bbcfb5e1395e" />

ENABLE EXTENSIONS IN PHP MANAGER

<img width="921" alt="Screen Shot 2025-02-26 at 5 53 01 PM" src="https://github.com/user-attachments/assets/2b1af299-eb75-4c8d-be70-0a6779cc39c6" />


<img width="1290" alt="Screen Shot 2025-02-26 at 8 47 00 PM" src="https://github.com/user-attachments/assets/a829dfbd-0129-4e31-9672-02b4ac316485" />

CONFIGURE USERS/CUSTOMERS

<img width="1250" alt="Screen Shot 2025-02-26 at 8 48 31 PM" src="https://github.com/user-attachments/assets/c42213c7-ae1e-49dd-b975-b1c34815d5d6" />


CONFIGURE HELP TOPICS

<img width="1255" alt="Screen Shot 2025-02-26 at 8 57 24 PM" src="https://github.com/user-attachments/assets/8a4e3718-a388-4415-897f-d23a581b96f6" />


ADDING NEW USER

<img width="1218" alt="Screen Shot 2025-02-26 at 8 42 35 PM" src="https://github.com/user-attachments/assets/6738d74c-157b-4238-98da-e8e55a07687a" />


TICKET CREATION BY USER

<img width="1143" alt="Screen Shot 2025-02-26 at 9 25 13 PM" src="https://github.com/user-attachments/assets/5434b128-1380-4410-85cc-23d2f9ca08c2" />


TICKET SUBMITTED

<img width="1178" alt="Screen Shot 2025-02-26 at 9 41 20 PM" src="https://github.com/user-attachments/assets/bffb07a6-69fc-4023-8437-b6a6a5428b9c" />



RESOLVED TICKET

<img width="1179" alt="Screen Shot 2025-02-26 at 9 46 55 PM" src="https://github.com/user-attachments/assets/7d387c48-4433-4360-bc39-8c7aa297436d" />
