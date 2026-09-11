# Pi-hole Block Lists

Lists of domains to block for your Pi-hole.

All the compiled lists ready for your Pi-hole live on [lists](https://codeberg.org/lab-zero/pihole-lists/src/branch/lists) branch.

## Lists

- [18plus](https://codeberg.org/lab-zero/pihole-lists/raw/branch/lists/18plus) - The longest list of adult websites on the internet

## Adding a list

1. Choose a list in [lists](https://codeberg.org/lab-zero/pihole-lists/src/branch/master/lists) directory
2. Click on it and choose `Raw` preview
3. Copy the URL of this raw preview page
4. Go into your Pi-hole dashboard -> Lists
5. In the `Add a new subscribed list` section at the top, paste the link into address URL input
6. Add comment and group assignment if needed
7. Click red "Add blocklist" button
8. Go into your CLI and type `pihole -g` to re-apply your lists
