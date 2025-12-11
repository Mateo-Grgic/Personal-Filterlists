# Personal Filter Lists

> **Note:** These are my personal uBlock Origin filter lists, built for my specific browsing habits and use cases. The **Personal-Cosmetic-Filterlist** and **Unified** list are very opinionated. Probably don't use them unless you know what they contain. The other lists should be safe for general use.

My personal filter lists for uBlock Origin, plus one hosts file for UNIX `/etc/hosts` blocking. 

## Should You Use These?

### Use these if:

- You're already running uBlock Origin in Medium/Hard Mode
- You want additional blocking beyond default lists
- You're comfortable troubleshooting site breakage

### Don't use these if:

- You want "set it and forget it" blocking
- You need maximum site compatibility
- You're new to custom filter lists
- You're just adding tonnes of lists without thinking much about each  

## What's Included

### Individual Lists

| List | Purpose | Use This If... |
|------|---------|----------------|
| **Advertisements.txt** | Blocks common ad-serving domains and removes ad placeholders/stubs from websites | You want ad blocking beyond default uBlock lists |
| **Hosts.txt** | Blocks trackers & analytics (heavy on Firefox telemetry blocking) | You want network-level blocking via `/etc/hosts` |
| **Personal-Cosmetic-Filterlist.txt** | Hides 'annoying' UI elements on sites I visit (very aggressive and opinionated) | You want to see what I block cosmetically (not recommended for general use) |
| **Shorteners.txt** | Bypasses URL shorteners and strips tracking parameters from URLs | You want cleaner URLs and fewer redirects |
| **Trackers.txt** | Blocks common analytics, trackers, and telemetry | You want tracker blocking beyond default uBlock lists |
| **Unbreak** | Unbreaks some websites & website features | You probably only need this if you're using my unified/privacy lists | 

### Unified Lists

| List | Contains | Use This If... |
|------|----------|----------------|
| **Privacy.txt** | Advertisements + Hosts + Shorteners + Trackers + Unbreak | You want all my blocking lists without cosmetic filters |
| **Unified.txt** | Everything (all individual lists above) | You want my complete filter setup (includes aggressive cosmetic filters) |

## Raw URLs
- Advertisements - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Advertisements.txt
- Hosts - https://raw.githubusercontent.com/meojg/Personal-Filterlists/refs/heads/main/Hosts.txt
- Personal Cosmetic Filterlists - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Personal-Cosmetic-Filterlist.txt
- Shorteners - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Shorteners.txt
- Trackers - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Trackers.txt
- Privacy - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Privacy.txt
- Unbreak - https://raw.githubusercontent.com/meojg/Personal-Filterlists/refs/heads/main/Unbreak.txt
- Unified - https://raw.githubusercontent.com/meojg/Personal-Filterlists/main/Unified.txt
