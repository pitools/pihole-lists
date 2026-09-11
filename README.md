# Pi-hole Block Lists

Lists of domains to block for your Pi-hole.

All the compiled lists ready for your Pi-hole live on [lists](https://codeberg.org/lab-zero/pihole-lists/src/branch/lists) branch.

## Lists

- [18plus](https://codeberg.org/lab-zero/pihole-lists/raw/branch/lists/18plus) - The longest list of adult websites on the internet

## Adding a list

1. Choose a list on [lists](https://codeberg.org/lab-zero/pihole-lists/src/branch/lists) branch
1. Click on it to choose
1. Click on it and choose `Raw` preview button
1. Copy the URL of this raw preview page
1. Go into your Pi-hole dashboard -> Lists
1. In the `Add a new subscribed list` section at the top, paste the link into address URL input
1. Add comment and group assignment if needed
1. Click red "Add blocklist" button
1. Go into your CLI and type `pihole -g` to re-apply your lists
