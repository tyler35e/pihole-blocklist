# pihole-blocklist

Custom block and allow rules for a home Pi-hole.

| File | Add to Pi-hole as | Entry format |
|---|---|---|
| `blocklist.txt` | Blocklist | `\|\|example.com^` |
| `allowlist.txt` | Allowlist | `@@\|\|example.com^` |

Each entry covers the domain and all its subdomains. Pi-hole picks up changes
the next time gravity updates (`pihole -g`).

Raw URLs to subscribe to:

- `https://raw.githubusercontent.com/tyler35e/pihole-blocklist/main/blocklist.txt`
- `https://raw.githubusercontent.com/tyler35e/pihole-blocklist/main/allowlist.txt`
