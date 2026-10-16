# Challenge Investigation Report

## Question 1: User Identity
* Answer: I am student. My home folder is /home/student.
* Commands: whoami, pwd

## Question 2: Server Version
* Answer: Server hostname is ubuntu-lab01 running Ubuntu 24.04.3 LTS.
* Commands: hostname, cat /etc/os-release

## Question 3: Available Resources
* Answer: RAM total is 1.9Gi, Storage available space is 4.0G.
* Commands: free -h, df -h /

## Question 4: Login Baselines
* Answer: Profiles configured for bash are root, student.
* Commands: grep "bash" /etc/passwd

## Question 5: Total Running Tasks
* Answer: 220 active baseline entries are cataloged.
* Commands: ps aux | wc -l

## Question 6: Account Lifetime Tracking
* Answer: User was added under system process PID 2779 and removed following step audit executions.
* Commands: sudo grep lab5user /var/log/auth.log
