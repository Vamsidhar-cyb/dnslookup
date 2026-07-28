██████╗ ███╗   ██╗███████╗██╗      ██████╗  ██████╗ ██╗  ██╗██╗   ██╗██████╗
██╔══██╗████╗  ██║██╔════╝██║     ██╔═══██╗██╔═══██╗██║ ██╔╝██║   ██║██╔══██╗
██║  ██║██╔██╗ ██║███████╗██║     ██║   ██║██║   ██║█████╔╝ ██║   ██║██████╔╝
██║  ██║██║╚██╗██║╚════██║██║     ██║   ██║██║   ██║██╔═██╗ ██║   ██║██╔═══╝
██████╔╝██║ ╚████║███████║███████╗╚██████╔╝╚██████╔╝██║  ██╗╚██████╔╝██║
╚═════╝ ╚═╝  ╚═══╝╚══════╝╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚═╝
Cybersecurity Projects Python License: AGPLv3 PyPI

Professional DNS query CLI with Rich terminal output, reverse lookups, and WHOIS integration.

This is a quick overview — security theory, architecture, and full walkthroughs are in the learn modules.

Screenshots & demo →

What It Does
Query A, AAAA, MX, NS, TXT, CNAME, and SOA records with colored table output
Reverse DNS lookup to resolve IP addresses back to hostnames
Trace DNS resolution path from root servers to authoritative nameservers
Batch lookups with concurrent queries for processing domain lists
WHOIS integration for domain registration information
JSON export for scripting and pipeline integration
Quick Start
uv tool install dnslookup-cli
dnslookup query example.com
Tip

This project uses just as a command runner. Type just to see all available commands.

Install: curl -sSf https://just.systems/install.sh | bash -s -- --to ~/.local/bin

Commands
Command	Description
dnslookup query	Query DNS records for a domain with colored table output
dnslookup reverse	Resolve an IP address back to its hostname
dnslookup trace	Trace the DNS resolution path from root to authoritative servers
dnslookup batch	Query multiple domains concurrently from a file
dnslookup whois	Retrieve WHOIS registration information for a domain
Learn
This project includes step-by-step learning materials covering security theory, architecture, and implementation.

Module	Topic
00 - Overview	Prerequisites and quick start
01 - Concepts	Security theory and real-world breaches
02 - Architecture	System design and data flow
03 - Implementation	Code walkthrough
04 - Challenges	Extension ideas and exercises
License
AGPL 3.0
