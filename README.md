# task-4-firewall

# Firewall Internship Task

## Objective
The objective of this task is to configure Windows Firewall to block insecure Telnet traffic on port 23 and allow secure SSH traffic on port 22, and to test these rules.

## Steps Performed

1. Opened **Windows Defender Firewall with Advanced Security**.
2. Created an inbound rule to **block TCP port 23** (Telnet).
3. Created an inbound rule to **allow TCP port 22** (SSH).
4. Enabled Telnet client on Windows to test the block rule.
5. Tested the Telnet block by running `telnet localhost 23` in Command Prompt — connection failed as expected.
6. (Optional) Tested SSH allow rule if an SSH server was available.
7. Removed the test firewall rules to restore original settings.

## Commands Used

- `telnet localhost 23` — tested Telnet port block.
- Enabled Telnet Client via Windows Features.
- (Optional) `ssh localhost` — tested SSH port allow.

## Screenshots

- Screenshot showing the **Block Telnet Port 23** firewall rule.
- Screenshot showing the **Allow SSH Port 22** firewall rule.
- Screenshot of Command Prompt showing Telnet connection failure.

## Summary

This task demonstrated basic firewall management skills by blocking insecure Telnet traffic and allowing secure SSH traffic. It also showed how to test firewall rules and restore firewall settings.

---

