# Zscaler Public IP Whitelist

## Overview

This repository provides a regularly updated list of **Zscaler public IP addresses** that should be whitelisted on firewalls to ensure seamless connectivity to Zscaler services. The IP addresses are sourced directly from the official Zscaler configuration endpoint:

- [Zscaler IP Reference](https://config.zscaler.com/zscalertwo.net/cenr)

## Purpose

Many organizations use Zscaler for secure web gateway and cloud security. To allow traffic to flow through Zscaler, network firewalls must permit outbound connections to Zscaler’s public IP addresses. This repository makes it easy for network administrators to access and update their firewall rules with the latest Zscaler IPs.

## Source

All IP addresses in this repository are referenced from Zscaler’s official configuration service:

- **URL:** https://config.zscaler.com/zscalertwo.net/cenr

The data is periodically checked and updated to reflect any changes made by Zscaler.

## Usage

1. **Download the latest IP list** from this repository.
2. **Import or copy the IP addresses** into your firewall’s whitelist configuration.
3. **Allow outbound connections** to these IPs to ensure Zscaler services function correctly.

## Updating the IP List

Zscaler may update their public IP ranges periodically. To ensure your firewall rules remain effective:

- **Check this repository regularly** for updates.
- (Optional) Use the provided `update_script.sh` to fetch the latest IPs automatically.

## Contributing

If you notice outdated IPs or want to suggest improvements, feel free to open an issue or submit a pull request.

## Disclaimer

- This repository is **not affiliated with Zscaler**.
- Always verify IP addresses with the official Zscaler documentation before applying changes to production environments.
