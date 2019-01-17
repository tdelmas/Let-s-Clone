It's a work in progress, Pull requests and Issues are welcomed.

# Let's Clone

How to spread Certificate Authorities like Let's Encrypt

# Why

[Why do we need more open certificates autorities](/WHY.md)

# Differences

Alternatives to Let's Encrypt could offert a different service:

- Be under another jurisdiction
- Could impose OCSP Must stapple to improve privacy and reduce costs (~152 FQDN represent 5.5B OCSP requests [source](https://letsencrypt.org/2018/12/31/looking-forward-to-2019.html))
- Could provide a fallback
- Could be open only for some tlds
- Could have no custom rates limits
- Support: could have a support in the local languages, and/or a paid one.

# How

## Finances

[Example of Let's Encrypt](/FINANCES.md)

|Category|Budget|
|---|---|
|Staffing|2M USD|
|Hardware|0.2M USD|
|Hosting|0.2M USD|
|Auditing|0.3M USD|
|Legal/Administrative|0.3M USD|
|Total|3M USD|

## Infrastructure
## Code hosting
## CT logs
## Key storage
## Software
## People
## Legal
## Audits
## CA stores and programs

### Windows

https://social.technet.microsoft.com/wiki/contents/articles/31633.microsoft-trusted-root-program-requirements.aspx

### Android

Cf. https://www.chromium.org/Home/chromium-security/root-ca-policy

### Chrome

https://www.chromium.org/Home/chromium-security/root-ca-policy

### Apple

https://www.apple.com/certificateauthority/ca_program.html

### Firefox / Mozilla

https://www.mozilla.org/en-US/about/governance/policies/security-group/certs/policy/

### Debian / Ubuntu

https://tracker.debian.org/pkg/ca-certificates

https://launchpad.net/ubuntu/+source/ca-certificates

### Java (Oracle's Java SE Root CA Program)

https://www.oracle.com/technetwork/java/javase/javasecarootcertsprogram-1876540.html

### Others

## CABForum

Baseline Requirements: https://cabforum.org/baseline-requirements-documents/
## Bootstrap cross sign
