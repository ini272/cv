# Professinal Experience

**DevOps Engineer**
*RISE | Visual Effects Studios*


**System Administrator**
*RISE | Visual Effects Studios*
02/2017 – 11/2018, 05/2019 – present

- Managing the company's ~800 Linux workstations and render nodes using Puppet
to keep the desired system state and Kickstart files for provisioning, thus 
automating IP address management, DNS records, and enrollment to the identity
management system
- Racking up and deploying physical nodes serving as virtual workstations to meet
the demand for remote work
- Monitoring critical servers resource utilization using InfluxDB and Grafana for
virtualization, furthermore ingesting data from several PDUs in the local server
room, throwing alerts upon reaching certain limits
- Lead the transition from the main storage cluster using BeeGFS to a more
performant and redundant solution using GPFS, in collaboration with an external
vendor
- Introduced a high availability cluster hosting infrastructure services using Ceph as
the distributed file system and Proxmox as the hypervisor, deprecating the former
single node VirtualBox hosts, therefore increasing redundancy, eliminating a
single point of failure, and providing a path for OS and software updates with low
downtime
- Onboarding new IT colleagues: Informing them about ticketing procedures,
location-specific servers, configuration management, etc.


**System Administrator - Internship**
*Storm Postproduction B.V*
12/2018 – 04/2019
- Installed and maintained the hardware and network infrastructure of new office
space including the setup of physical workstations, basic Linux file server, local
switch, subnet configuration, and a VPN tunnel to the main office network

# Education
**Bachelor of Science, International course of media informatics**
*University of Applied Sciences Berlin*
10/2014 – 03/2020

- Thesis title: *Improving system architecture through high availability principles*\
Discusses the demand for reliable infrastructure in modern times, highlighting the
importance of including HA in the design process of system architecture and its
effect on business and technological aspects

# Technology

- Configuration/Server management: Puppet + Foreman, Ansible, Gitlab CI/CD
- Language: Bash, Python
- Virtualization: Docker, Proxmox (KVM/LXC)
- Monitoring: Grafana-InfluxDB-Telegraf, CheckMK, Graylog
- OS: CentOS 7, Debian 9-12, AlmaLinux/Rocky 9
- Filesystems: GPFS, Ceph, BeeGFS, ZFS