# Security Policy

We appreciate your time and effort in responsibly reporting any security vulnerabilities you may find on our blockchain or in the related tooling.

## Reporting a Vulnerability

**Please write an email to <security@concordium.com>.**

Do not create a public bug ticket mentioning the vulnerability or discuss it publically before we got the chance to fix it.

Your mail report should include the following information:
- **description of the vulnerability**
- **clear steps to reproduce**
- potential impact
- attack scenario (if any)
- affected components
- github username

We encourage you to use our [public key](#public-key) when sending sensitive information.

You'll receive a response to your email after we had time to carefully assess you report. If applicable, a new [security advisory](https://github.com/concordium-cl/sandbox/security/advisories) will be opened and all further communication will proceed there with you as invited collaborator.

Before writing to us, please check [scope](#scope), [out of scope](#out-of-scope), [eligibility](#eligibility) and previously published [security advisories](https://github.com/concordium-cl/sandbox/security/advisories).

:pray: **Thank you** :pray:


## Scope
- Concordium Node software
- Concordium Wallet Proxy Service
- Concordium Client
- Concordium Smart Contracts
- Concordium Mobile Reference Wallet (iOS / Android)
- Concordium Desktop Wallet


## Out of Scope
- Network dashboard
- Node dashboard
- Concordium websites https://concordium.com/ and https://developers.concordium.com/ and other infrastructure such as email
- Concordium Node Dashboard UI
- Concordium Network Dashboard UI


## Eligibility 

Generally speaking, we appreciate it very much for being informed about bugs that pose a significant vulnerability to the security or integrity of the Concordium Network. Anything which has the potential for financial loss or data breach is of highest interest, including:

- implementation bugs that can lead to financial loss
- access to our production servers
- unintended Remote Code Execution
- protocol bugs
- crash bug in Concordium Node (i.e. a bug that can crash the app by sending a special request, not by sending thousands requests)

However, we will not prioritize bugs of the following form: 

- SPF/DMARC records
- CORS headers on endpoints meant to be accessible from other domains
- issues with 3rd party services we use
- vulnerabilities in 3rd party libraries without working exploits against our apps/servers
- version disclosure
- lack of security headers
- cookies without the secure flag
- vulnerabilities on sites hosted by third parties unless they lead to a vulnerability on the main website
- vulnerabilities contingent on physical attack, social engineering, spamming, DDOS attack, etc
- vulnerabilities affecting outdated or unpatched browsers
- vulnerabilities in third party applications that make use of Concordium’s API


## Public Key
```
-----BEGIN PGP PUBLIC KEY BLOCK-----
```
