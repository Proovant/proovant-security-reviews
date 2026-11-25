# Cloak Security Review

Proovant conducted an AI-assisted security review of Cloak, a sealed-bid auction and shielded-pool protocol.

## Review Results

- 12 findings reported
- 8 findings fixed
- 1 finding mitigated
- 3 findings left as they were: by design, accepted, or testnet-only

## Example Finding: CL-01

A bidder could manipulate the tie-break lottery by choosing which sealed bids to open.

The issue was fixed by the project team and Proovant retested the fix.

## Methodology

The review used specialised AI analysis, adversarial validation, and Foundry-based proof-of-concept testing.

Findings were documented with their impact, reproduction details, and remediation guidance.

## More Information

Read the published case study on [Proovant](https://www.proovant.com/).

[Back to all Proovant security reviews](../README.md)
