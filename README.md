# Personal Filter Lists

My personal filter lists for uBlock Origin (and AdGuard Home). My cosmetic list is designed to make websites usably minimalist, and tracker list is designed to increase privacy. I highly recommend you do not use the cosmetic list, tracker list should be fine for general use.

## Warning: This List WILL Break Sites

**Do not use this list unless:**
- You understand how uBlock Origin filter lists work
- You know how to diagnose and disable problematic filters
- You accept full responsibility for any breakage
- You will NOT blame uBlock Origin developers for issues caused by this list

**This is a personal, experimental filter list.** It is not maintained by the uBlock Origin team. If sites break, it's on you to fix it, not the uBO developers.

## How to Import (Advanced Users Only)

**uBlock Origin:**
1. Dashboard → **Filter lists** → **Custom** section 
2. Click **Import** and paste the raw GitHub URL for the list you want
3. **Apply changes**
4. You're done, lists will automatically update 

## What's Included

**General Tracker Filterlist Rules:** Tracker blocking, analytics, fingerprinting scripts, Telemetry, URL parameters, and Canadian-specific tracking domains not covered by default lists.

**Cosmetic Filterlist Rules:** Cookie banners, newsletter popups, anti-adblock nags, social media widgets, and other annoyances. (very strict)

## Should You Use These?

**Probably not as direct imports.** These lists are:
- Tailored to my browsing habits and websites I visit
- Include some Canadian-specific entries
- Extremely opinionated about what counts as "annoyances"

**Better approach:** Use as inspiration to build your own lists, or test them and remove rules that break sites you care about. Don't blindly import filter lists, understand what you're blocking.

## Maintenance

- Updated irregularly as I encounter new tracking/annoyances
- Tested with uBlock Origin on LibreWolf 143+
- Tracker list designed for the advanced capabilities of uBlock Origin, but 70% of filters should work with an intelligent network-level blocker, like AdGuard Home.

## License

MIT License - Use freely, no attribution required (but appreciated).
