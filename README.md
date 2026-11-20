# Pi-hole Block Lists

[![Deploy](https://github.com/pitools/pihole-lists/actions/workflows/deploy.yml/badge.svg)](https://github.com/pitools/pihole-lists/actions/workflows/deploy.yml)

Lists of domains to block for your Pi-hole.

All the compiled lists ready for your Pi-hole live on [lists](https://github.com/pitools/pihole-lists/tree/lists) branch.

## Lists

- [18plus](https://raw.githubusercontent.com/pitools/pihole-lists/refs/heads/master/src/18plus) - The longest list of adult websites on the internet

## Adding a list

1. Choose a list on [lists](https://github.com/pitools/pihole-lists/tree/lists) branch
1. Click on the file you need
1. Click on `Raw` button to preview raw content
1. Copy the URL of this raw preview page
1. Go into your Pi-hole dashboard -> Lists
1. In the `Add a new subscribed list` section at the top, paste the link into address URL input
1. Add comment and group assignment if needed
1. Click red `Add blocklist` button
1. Go into your CLI and type `pihole -g` to re-apply your lists
