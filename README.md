# Frecon 

## Overview

This project is designed to help security researchers and penetration testers discover subdomains, enumerate endpoints, and filter IP addresses of targets, specifically identifying those not behind CDNs. It leverages multiple APIs, brute force techniques, and archival data to provide comprehensive asset discovery.

## Features

- **Subdomain Discovery**: Utilize APIs and DNS brute force methods to find subdomains.
- **Endpoint Enumeration**: Use archived data to list potential endpoints.
- **IP Filtering**: Identify and list IP addresses that are not protected by CDNs.
- **Service Discovery**: Sending HTTP requests on ports 443, 80, 8080, and 8000 to full service discovery.
- **Coming Soon**

## Workflow
1. **Selecting Target**: You can join our [discord channel](https://discord.gg/baJ4C7BsXK) to create a thread to add a new domain, if your asset gets over 50 upvotes, the asset will be added to the workflow for 1 month.
2. **Passive Enumeration**:
   - [Subfinder](https://github.com/projectdiscovery/subfinder)
   - [Findomain](https://github.com/Findomain/Findomain)
   - [Assetfinder](https://github.com/tomnomnom/assetfinder)
   - [Anubis](https://github.com/jonluca/Anubis)
   - [Vita](https://github.com/junnlikestea/vita)
3. **DNS Brute Force**:
   - [Assetnote Wordlists](https://wordlists.assetnote.io/)
   - [PureDNS](https://github.com/d3mondev/puredns)
   - [MassDNS](https://github.com/blechschmidt/massdns)
   - [Resolvers](https://github.com/trickest/resolvers)
4. **Service Discovery**:
   - [Httpx](https://github.com/projectdiscovery/httpx)
6. **Endpoint Enumeration**:
   - [Katana](https://github.com/projectdiscovery/katana)
   - [Waybackurls](https://github.com/tomnomnom/waybackurls)
   - [Uro](https://github.com/s0md3v/uro)
7. **IP Filtering**:
   - [DNSX](https://github.com/projectdiscovery/dnsx)
   - [Cut-CDN](https://github.com/ImAyrix/cut-cdn)

## Contribution
All contributions/ideas/suggestions are welcome! If you want to add/edit a target/workflow, feel free to send us a PR, tweet at us @m7arm4n, or join the conversation on [Discord](https://discord.gg/baJ4C7BsXK).

version 0.1
