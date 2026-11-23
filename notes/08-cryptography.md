# 08 — Cryptography

## Obligation (plain language)

Entities must implement policies and procedures regarding the use of cryptography and, where appropriate, encryption, to protect the confidentiality and integrity of data and communications.

## Control questions

- Is there a cryptography / encryption policy?
- What data is required to be encrypted at rest and in transit?
- How are cryptographic keys managed (generation, storage, rotation, destruction)?
- Are outdated algorithms and protocols prohibited and actively removed?
- Who approves exceptions to encryption requirements?

## Example evidence

- Cryptography or encryption policy
- Standards for TLS, disk encryption, and key management
- Inventory of systems handling sensitive data and their encryption status
- Key management procedures or HSM / vault usage evidence
- Results of configuration reviews (e.g. TLS scans)

## Common gaps

- Policy exists but legacy systems still use weak protocols
- Keys stored insecurely or shared
- No inventory of where sensitive data actually lives
