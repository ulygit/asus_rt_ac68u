# Cloudflare Dynamic DNS Update Script for ASUS RT-AC68U

The ASUS RT-AC68U router with the Asuswrt-Merlin custom firmware adds support for custom dynamic DNS providers. This is great for Cloudflare users because, although Cloudflare is not one of the built-in providers, we can add support for it. This script does exactly that.

Features include:
  - Support for querying your Cloudflare DNS zone to determine record IDs
  - Handling of Merlin firmware success/failure callbacks
  - Logging of JSON responses for later inspection, and
  - Configurable rate-limiting to comply with Cloudflare API TOS

## How to Configure

### Prerequisites
You should have your Merlin-enabled ASUS RT-AC68U router configured for your network with Internet access.

### Configuration Overview
