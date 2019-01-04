Some midnight commander tweaks.

- mcedit.menu.diff would be applied to /etc/mc/mcedit.menu
- Syntax.diff would be applied to either ~/.config/mc/mcedit/Syntax if it exists,
otherwise to /usr/share/mc/syntax/Syntax
- copy nft.syntax into the /usr/share/mc/syntax directory. This provides syntax highlighting
for nftables configuration files.