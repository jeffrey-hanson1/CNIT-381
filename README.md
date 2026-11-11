# CNIT-381 — Weekly Labs
Weekly labs for CNIT 381.

## Week 1
Created the repository, configured Git, cloned it locally, and made my first commit.

## Week 2
Practiced team Git collaboration with a partner: feature branches, pull
requests, code review, and resolving a merge conflict on a shared network
inventory site.

Practiced team Git collaboration using VS Code and Git commands: feature
branches, commits, pushes, pull requests, code review, squash merging,
and resolving a merge conflict while building the UW-Stout CNIT
Cybersecurity Technology Hub.

## Week 3
Containerized a duplicate-IP checker with Docker and published the image to Docker Hub.

## Week 4
Built a network config pipeline: an intent file plus a generator, containerized,
with CI/CD that regenerates and validates the configs on every change.

## Week 5
Called the GitHub REST API from Python to read my repo and create an issue.

## Week 6
Built an IP address plan checker using Python and YAML to validate VLANs, subnets, gateways, and host requirements. Containerized the checker with Docker and automated testing with GitHub Actions. Used the GitHub REST API to automatically create an issue when errors were detected, then fixed all four errors through a pull request and achieved passing CI checks.

Repository: https://github.com/jeffrey-hanson1/ip-plan-check

## Week 8:

**What I did:** This week, I used Cisco Modeling Labs (CML) to configure OSPF manually on two routers. After verifying that the routers could communicate, I ran an Ansible playbook that automated the loopback and OSPF configurations. I also created my own backup.yaml playbook to back up the running configurations from both routers and save them in a backups folder.

**What I learned:** I learned how OSPF allows routers to communicate and share routing information with each other. I also learned how Ansible can automate configurations instead of having to enter commands manually on each router. This lab helped me better understand how automation can save time, reduce mistakes, and make managing multiple network devices easier. I also got more experience troubleshooting SSH connections and working with GitHub.

## Week 9 – Build a Network and Automate It End to End

In Week 9, I built a network in Cisco Modeling Labs (CML) using two routers, one switch, and an Ubuntu Ansible control node.

I configured management IP addresses and SSH access, then created four Ansible playbooks to automate loopback interfaces, EIGRP routing, login banners, and configuration backups.

I verified EIGRP neighbor connectivity, successfully pinged between router loopbacks, and confirmed Ansible idempotency with `changed=0` on a second run.

**Week 9 GitHub Repository:** https://github.com/jeffrey-hanson1/cnit381-week9

## Week 10 - Ansible with CSR1000v

In Week 10, I used the DEVASC Ubuntu virtual machine and Ansible to automate tasks on a Cisco CSR1000v router in VirtualBox.

I configured SSH connectivity and created an Ansible playbook to automatically back up the router's running configuration. I then created a second playbook to configure IPv6 addressing on GigabitEthernet1.

I verified the IPv6 configuration using `show ipv6 interface brief` and confirmed that both playbooks executed successfully without any failed tasks.

**Week 10 GitHub Repository:** https://github.com/jeffrey-hanson1/cnit381-week10


## Week 11 - RESTCONF Network Automation

In Week 11, I used the DEVASC Ubuntu virtual machine, Postman, and Python to automate network management tasks on a Cisco Catalyst 3650 switch using RESTCONF.

I configured network connectivity between the virtual machine and switch, verified RESTCONF access, and used Postman to send GET requests to retrieve interface information.

I then used a RESTCONF PUT request to create Loopback1 with the IPv4 address `10.1.1.1/24`. I verified the configuration using a GET request and received successful HTTP responses.

Finally, I created a Python script using the `requests` library to retrieve switch interface configurations automatically. I also used an environment variable to keep the switch password out of the source code.

**Week 11 GitHub Repository:** https://github.com/jeffrey-hanson1/cnit381-week11 

