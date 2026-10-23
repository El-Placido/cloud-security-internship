# Cloud Security Internship

Hands-on internship project on cloud and server security, documented week by week.

## Week 1 goals: Setup, Linux, Git and server hardening

- Secure the AWS account with root MFA, an IAM admin user and a $10 budget alert
- Practice Linux files, permissions, users, services and packages on Ubuntu
- Generate SSH keys and connect to an EC2 instance
- Harden SSH: disable password login and direct root login, keep key login working
- Install fail2ban and observe it blocking repeated failed logins
- Use Git and GitHub with two-factor authentication: commit, push, branch and merge

## Repository contents

- `docs/sshd_config_hardened.txt`: hardened SSH settings from the EC2 server
- `docs/fail2ban-log-excerpt.txt`: log lines showing a blocked address
- `docs/linux-cheatsheet.md`: Linux command cheat sheet
- `screenshots/`: evidence for each task

## Tools EC2, Amazon Linux 2023, Ubuntu, OpenSSH, fail2ban (nftables), Git, GitHub
