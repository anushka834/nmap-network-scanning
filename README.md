# NMAP Network Scanning Project

## Objective
To perform a basic network scan of the local machine using Nmap and identify open ports, services, and operating system information.

## What is Nmap?
Nmap (Network Mapper) is a network scanning tool used to discover hosts, ports, services, and operating system information on a network.

## Importance of Network Scanning
Network scanning helps identify active hosts, open ports, running services, and possible security weaknesses.

## Commands Used
1. nmap 127.0.0.1
2. nmap -sV 127.0.0.1
3. sudo nmap -O 127.0.0.1
4. cat_nmap_scan_results.txt

## Target
127.0.0.1 (Localhost)

## Result
The localhost was found to be up. All 1000 scanned TCP ports were closed. Service/version detection was performed, but no open services were identified. OS detection could not determine specific OS details.

## Ethical Guidelines
Nmap should only be used on systems and networks where you have permission to perform security testing.

## Conclusion
Nmap successfully performed the required network scans. The results showed that no open TCP ports were detected on the local machine during the scan.
