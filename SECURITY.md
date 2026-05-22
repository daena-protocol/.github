# Security Policy

## Reporting a vulnerability

If you believe you have discovered a security vulnerability in any Daena Protocol repository — in the specification, the reference SDK, the CLI, the renderer, or the verifier — please report it privately so we can address it before public disclosure.

**Email:** security@daena-protocol.org

Please include:

- A description of the vulnerability and its potential impact
- Steps to reproduce, or a proof of concept
- The repository and commit / version affected
- Whether you intend to publicly disclose, and on what timeline

We will acknowledge your report within 3 business days, work with you on a fix, and credit you in the resulting security advisory unless you prefer to remain anonymous.

## Scope

Security reports are welcomed for, among other things:

- Cryptographic weaknesses in the signing or verification specification
- Implementation flaws in the reference SDK, CLI, renderer, or verifier
- Injection or privilege-escalation flaws in render hints
- Replay, downgrade, or signature-stripping attacks against the protocol
- Privacy leaks in QUERY, ACT, SUBSCRIBE, or VERIFY verb implementations

Reports about third-party services that *use* Daena should be directed to those services' maintainers.

## Disclosure

We follow coordinated disclosure. We will not pursue legal action against good-faith security researchers who follow this policy.
