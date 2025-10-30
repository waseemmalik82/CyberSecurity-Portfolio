# TryHackMe — How Websites Work

**Room:** https://tryhackme.com/room/howwebsiteswork  
**Completed by:** Waseemmalik82  
**Date:** YYYY-MM-DD

---

## Purpose
Learn the end-to-end flow of a website: DNS → CDN → server, and how browsers render pages.

## Key Concepts Learned
- DNS resolution flow and caching
- Role of CDN and caching headers
- Server response flow (routing, backend, DB)
- Basics of TLS handshake (overview)
- Common web assets and where to find them (HTML/CSS/JS)

## SOC / Analyst Relevance
- Understand sources of web logs (webserver, CDN, WAF)
- Investigate suspicious domains via DNS history and TLD anomalies
- Identify misconfigurations (exposed directories, missing security headers)

## Commands / Tools Used
- `nslookup` / `dig`
- Browser devtools (Network & Security tabs)
- curl / wget for simple checks

## Evidence / Proof
![How Websites Proof](./screenshots/how-websites-1.png)

## Lessons & Next Steps
- Combine HTTP knowledge with DNS and CDN behavior to improve detection rules
- Next lab: Putting It All Together
