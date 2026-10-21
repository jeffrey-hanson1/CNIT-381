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

## Week 8: OSPF by Hand, Then Automated

**What I did:** This week, I used Cisco Modeling Labs (CML) to configure OSPF manually on two routers. After verifying that the routers could communicate, I ran an Ansible playbook that automated the loopback and OSPF configurations. I also created my own backup.yaml playbook to back up the running configurations from both routers and save them in a backups folder.

**What I learned:** I learned how OSPF allows routers to communicate and share routing information with each other. I also learned how Ansible can automate configurations instead of having to enter commands manually on each router. This lab helped me better understand how automation can save time, reduce mistakes, and make managing multiple network devices easier. I also got more experience troubleshooting SSH connections and working with GitHub.
