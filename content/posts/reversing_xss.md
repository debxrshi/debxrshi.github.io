---
title: "Reversing_xss"
date: 2024-05-31T00:51:30+05:30
draft: false
tags:
    - web security
    - xss
    - notes
---

One search of "xss" will lead you to hundreds of payloads and bypasses. Everyone gives you the payload that happens to bypass Akamai Ghost or Cloudflare or any other filtering. You use the payload, git paid, ez W. But, why does one payload fail while other passes through enterprise grade WAFs and filtering? How do these people (and tools) come up with bypasses?

I was intrigued and here I'm dumping everything I uncovering while reverse engineering convulated WAF bypass XSS payloads.




