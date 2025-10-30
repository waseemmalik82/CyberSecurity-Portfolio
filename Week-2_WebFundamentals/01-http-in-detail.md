# TryHackMe — HTTP in Detail

**Room:** https://tryhackme.com/room/httpindetail  
**Completed by:** Waseemmalik82  
**Date:** YYYY-MM-DD

---

## Purpose
Understand HTTP protocol internals: requests, responses, status codes, headers, methods.

## Key Concepts Learned
- HTTP request/response lifecycle
- Methods: GET, POST, PUT, DELETE
- Status codes (2xx, 3xx, 4xx, 5xx)
- Important headers (Host, User-Agent, Content-Type, Authorization)
- Difference between HTTP and HTTPS (TLS/SSL basics)

## SOC / Analyst Relevance
- How malicious actors abuse HTTP (bad headers, malicious payloads)
- What to look for in web traffic logs (suspicious POSTs, abnormal user agents)
- How to map alerts in SIEM to HTTP anomalies

## Commands / Tools Used
- Browser devtools (Network tab)
- Wireshark (optional capture)
- curl examples: `curl -I https://example.com` / `curl -X POST -d "data" https://example.com/api`

## Evidence / Proof
(Upload screenshot(s) into `screenshots/` and reference them here)
![HTTP Proof](./screenshots/http-detail-1.png)

> Note: Do NOT include flags or full challenge answers.

## Lessons & Next Steps
- Practice parsing HTTP in Wireshark and SIEM logs
- Next lab: How Websites Work
