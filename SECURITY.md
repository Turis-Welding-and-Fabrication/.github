# Security and Sensitive Information

Turi's GitHub repositories are part of a real operating business. Treat them accordingly.

## Never commit

- passwords, API keys, private keys, tokens or recovery codes;
- banking or payment credentials;
- uncontrolled customer files or customer secrets;
- private employee records;
- production database dumps;
- raw private family/history media unless its repository and custody are explicitly approved;
- credentials copied from a workstation, controller or legacy machine;
- material that creates machine-control authority merely because it is technically reachable.

## If you find a secret

Do not open a public issue containing it.

Stop propagation, preserve enough non-secret evidence to identify the incident, notify the responsible Turi's/QuietWire steward through the established private channel, rotate/revoke the credential where authorized, and record the remediation without reproducing the secret.

## Machine and production safety

Repository access, remote access and software capability do not equal authority to alter production systems.

Observe and document before changing machine-adjacent or legacy systems. Production, customer, spending, publication and safety decisions remain separately governed.

## Evidence

When reporting a security or operational issue, distinguish:

1. direct observation;
2. source evidence;
3. derived interpretation;
4. proposed remediation.

Do not upgrade a suspicion into a fact merely because an automated system produced it.
