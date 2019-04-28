---
title: "SSL Cert"
reference_version: b5d61efa1ca257bd1d15768453d12cb8
---
Our SSL Certificate is required to connect via the latest releases of the osu! client (only version of osu! allowed on our server to begin with).

### Manually installing our SSL Certificate

This means that your hosts file has most likely successfully been redirected via the hosts file, but your certificate is somehow not working. Please check [here](https://c.ppy.sh/) and refer to the possibilities below:

A. Page unsafe warning
Fix: This means the certificate is infact invalid/not working. If this happens, please install [this certificate](/static/ca.crt),
like [so](/static/cert_guide.gif).

B. osu!Bancho page
Fix: This means your hosts file actually was not written, or redirection is not working in some way, but somehow your osu! is still being redirected? Move to the #help channel of our [Discord](https://discord.gg/5cBtMPW).