Linux Server Monitoring & Troubleshooting

Project Overview

This project demonstrates hands-on Linux system administration skills, including server health monitoring, resource utilization analysis, process management, service troubleshooting, network monitoring, and log analysis.

Objectives

- Monitor Linux server health and performance.
- Analyze CPU, RAM, and disk utilization.
- Manage and troubleshoot Linux processes.
- Monitor and manage system services.
- Perform network connectivity troubleshooting.
- Analyze system logs and identify errors.
- Automate health checks using a Bash script.

Technologies & Tools

- Linux (Ubuntu)
- Bash Shell Scripting
- systemctl
- journalctl
- top and ps
- df, du, free
- ip, ping, ss

Project Tasks

1. System Information & Health Check

- Hostname and OS information
- System uptime
- CPU information

2. CPU Monitoring

- Monitor CPU utilization
- Identify CPU-intensive processes

3. Memory Monitoring

- Check RAM usage using `free -h`
- Analyze memory details using `/proc/meminfo`

4. Disk & Filesystem Monitoring

- Check disk utilization using `df -h`
- Inspect disk partitions using `lsblk`
- Analyze directory sizes using `du`
- Practice directory creation and deletion using `mkdir` and `rmdir`

5. Process Monitoring & Management

- Monitor processes using `ps` and `top`
- Identify resource-consuming processes
- Manage background processes
- Terminate processes using `kill`

6. Service Monitoring

- Check service status using `systemctl`
- Start, stop, and restart services
- Verify failed services

7. Network Monitoring & Troubleshooting

- Check network interfaces using `ip`
- Test connectivity using `ping`
- Monitor listening ports using `ss`

8. Log Analysis & Troubleshooting

- Analyze system logs using `journalctl`
- Identify system errors
- Inspect boot logs and error messages

9. Bash Monitoring Script

Created a Bash script (`monitor.sh`) to generate a Linux server health report containing:
- Hostname and date
- System uptime
- Disk utilization
- Memory utilization
- CPU load
- Top CPU and memory-consuming processes
- Network IP address

Screenshots

All project screenshots are available in the `Screenshots/` directory.

Key Learning Outcomes

- Linux system administration
- Server performance monitoring
- Process and service management
- Network troubleshooting
- Log analysis
- Bash scripting and automation

Author

Abhishek Khanna