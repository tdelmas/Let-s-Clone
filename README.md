It's a work in progress. Pull requests and Issues are welcomed.

# Let's Clone

How to spread Certificate Authorities like Let's Encrypt

# Why

[Why do we need more open certificates authorities](/WHY.md)

# Differences

Alternatives to Let's Encrypt could offer a different service:

- Be under another jurisdiction
- Have a different policy, for example regarding Phishing and Malware (https://letsencrypt.org/2015/10/29/phishing-and-malware.html)
- Could impose OCSP Must Staple to improve privacy and reduce costs (~152 FQDN represent 5.5B OCSP requests per day [source](https://letsencrypt.org/2018/12/31/looking-forward-to-2019.html))
- Could provide a fallback
- Could be open only for some tlds
- Could have no custom rate limits
- Could require the CAA DNS entry
- Could require the DNSSEC/HSTS+preload/...
- Support: could have a support in the local languages, and/or a paid one.
- Restrict possible challenges (ex. only DNS with DNSSEC)

# How

[HOW](/HOW.md)

# Finances

[Example of Let's Encrypt](/FINANCES.md)

|Category|Budget (per year)|
|---|---|
|Staffing|2M USD|
|Hardware|0.2M USD|
|Hosting|0.2M USD|
|Auditing|0.3M USD|
|Legal/Administrative|0.3M USD|
|Total|3M USD|

# CA stores and programs

[CA stores and programs](/CA_STORES.md)
