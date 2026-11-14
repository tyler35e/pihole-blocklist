# pihole-blocklist

Custom block and allow rules for a home Pi-hole.

| File | Add to Pi-hole as | Entry format |
|---|---|---|
| `blocklist.txt` | Blocklist | `\|\|example.com^` |
| `allowlist.txt` | Allowlist | `@@\|\|example.com^` |

Entries in that form cover the domain and all its subdomains. Pi-hole picks up
changes the next time gravity updates (`pihole -g`).

`blocklist.txt` also carries a dated copy of Pi-hole's default list, the
[StevenBlack unified hosts list](https://github.com/StevenBlack/hosts) (MIT
licence), as exact domains.

Raw URLs to subscribe to:

- `https://raw.githubusercontent.com/tyler35e/pihole-blocklist/main/blocklist.txt`
- `https://raw.githubusercontent.com/tyler35e/pihole-blocklist/main/allowlist.txt`
