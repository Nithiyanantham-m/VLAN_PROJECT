# COMPUTER NETWORKS ASSIGNEMENT 
# VLAN Configuration Lab Exercise

## Problem Statement

This lab Assignemt is designed to familiarize users with the benefits of Virtual LANs (VLANs) and guide them through the process of configuring a router and a switch to support VLANs in a Cisco networking environment.

### Protocols Used

1. **Router Configuration (R1):**
   - Protocol Used: SSH or Telnet

2. **Workstation Configuration (WS1 and WS2):**
   - Protocol Used: GUI or CLI (SSH or Telnet in a real-world scenario)

3. **Ping Testing:**
   - Protocol Used: ICMP

4. **Switch Configuration (SW1):**
   - Protocol Used: Cisco IOS CLI (SSH or Telnet)

5. **VLAN Configuration and Port Assignment:**
   - Protocol Used: Cisco IOS CLI (SSH or Telnet)

6. **Show Commands on Switch:**
   - Protocol Used: Cisco IOS CLI (SSH or Telnet)

7. **Ping Testing after VLAN Configuration:**
   - Protocol Used: ICMP

8. **Modify VLAN Configuration on Switch:**
   - Protocol Used: Cisco IOS CLI (SSH or Telnet)

9. **Show VLAN Port Assignments:**
   - Protocol Used: Cisco IOS CLI (SSH or Telnet)

10. **Assign Another Port to VLAN:**
    - Protocol Used: Cisco IOS CLI (SSH or Telnet)

11. **Ping Testing after Port Assignment:**
    - Protocol Used: ICMP

### Method Explanation

1. Connect to R1 and configure the IP address on the fastethernet interface.
2. Configure IP addresses and default gateways for workstations (WS1 and WS2).
3. Perform ping tests between devices.
4. Connect to SW1 and set up VLANs, starting with VLAN 20 for workstations.
5. Assign ports to VLANs, initially assigning port 1 for WS1 to VLAN 20.
6. Perform ping tests from WS2 to R1 and WS1.
7. Configure port 2 on SW1 for WS2 to be included in VLAN 20.
8. Repeat ping tests to verify connectivity changes.
9. Use show commands on SW1 to view VLAN port assignments.
10. Assign fastethernet 0/12 to VLAN 20 on SW1.
11. Perform additional ping tests to verify complete connectivity.

## How to Run

1. Follow the step-by-step instructions in the "Method Explanation" section.
2. Execute the provided commands on routers, workstations, and switches.
3. Verify connectivity using ping tests.
4. Refer to the show commands on the switch to view VLAN port assignments.

Feel free to customize this README template according to your preferences and specific details of the lab exercise. Good luck with your GitHub upload!
