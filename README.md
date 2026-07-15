# bash-recon-tool
an effective bash script that automates full Nmap & gobuster scan. 

## Features

- Checks user input
- Runs a fast Nmap scan (-F)
- Saves output to a text file
- Finds open ports based on the scan
- runs a second nmap scan and finds web ports
- does a gobuster scan on the web ports

## Requirements

- Bash
- Nmap
- gobuster

## Example Output

```
starting recon on...
pinging...
running quick Nmap scan...
finished full recon scan.
gobuster scan finished, results saved to...
``` 
