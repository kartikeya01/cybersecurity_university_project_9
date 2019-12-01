# Brief writeup about experiment

```Summary: Setup a honeypot and intercept some attempted attacks in the wild.```

In this assignment, you will stand up a basic honeypot and demonstrate its effectiveness at detecting and/or collecting data about an attack. Guided instructions for doing this using specific software are provided below, but you are free to take any approach you wish that demonstrates the following basic principles:

Successful configuration and deployment of a network-accessible honeypot server with two primary features:
* An attack surface that is vulnerable or exposed in some way to network-based attacks
* A network security feature such as an IDS configured to detect and log such attacks
* Illustration of at least one attack against the honeypot that can be detected or logged in a way that captures information about the attack or the attacker


# Which Honeypot(s) did you deploy

| Name                   | Hostname         | Honeypot | Attacks |
|------------------------|------------------|----------|---------|
| mhn-honeypot-1-dionaea | mhn-honeypot-1   | dionaea  | 1,653   |
| mhn-honeypot-2-dionaea | mhn-honeypot-2   | dionaea  | 4,231   |
| mhn-honeypot-3-dionaea | mhn-honeypot-3   | dionaea  | 2,001   |

# Did you encounter any issues

Had some issues setting up MHN Honeypot VM using GCP (Windows)

# A summary of the data collected: number of attacks, number of malware samples, etc.

## TOP 5 Attacker IPs:

* 173.77.241.134 (700)
* 192.155.98.197 (481)
* 91.126.146.225 (123)
* 68.183.16.108 (111)
* 104.248.29.221 (54)

## TOP 5 Attacked Ports:

* 23 (725)
* 5060 (488)
* 8080 (401)
* 8088 (54)
* 445 (21)

# Any unresolved questions raised by the data collected

N/A
