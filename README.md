# SMC.py
Sample Python Script to used to add new hosts to a Forcepoint NGFW firewall.

This script adds new hosts and creates a new firewall rule that allows a single source either RDP or SSH access to that host.

Also accomidates the fact that a host might be an existing 'bastion' host, and be managed by an existing group and affiliated rule.

This is, of course, very institution specific, but it's meant to serve as an example of how one might work in Python with the SMC REST API.
