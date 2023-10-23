# Object of Conformity: Verifiable Identifier

## Verifiable Identifier

* A **verifiable identitifier (VID)** is an address or identifier that is verifiably bound to at least one set of cryptographic keys that are discoverable via an **associated disovery protocol**


## Object of Conformity Criteria

1. A VID must be resolvable securely to obtain the current public key(s) needed to verify that the VID owner controls the VID.
2. A VID must be resolvable securely to obtain the current network endpoint(s) for establishing a ToIP connection with the entity identified by the VID.
3. A VID does not need to change (i.e., remain the same) when the controller’s key(s) are rotated or network endpoint(s) are updated.
4. A VID must support at least one defined **out-of-band (OOBI)** process for initial setup.
5. A VID must support at least one **digital signature scheme**
6. A VID must support at least one **encryption method**

## Reliable System Criteria

* A VID is used to issue **electronic transferable record (ETR)** and enable the independent verification of:

  * Criterion 1: Same Information
  * Criterion 2: Singularity
  * Criterion 3: Control
  * Criterion 4: Integrity
  * Criterion 5: Reliable System

## References

1. [ToIP Trust Spanning Protocol for Muggles](https://docs.google.com/presentation/d/1dgaTwxRubnpj7M83840mz53_iJfwEkajndrBBEQthgU/edit#slide=id.gc6f919934_0_20)
2. [MID-YEAR PROGRESS REPORT ON THE TOIP TRUST SPANNING PROTOCOL](https://trustoverip.org/blog/2023/08/31/mid-year-progress-report-on-the-toip-trust-spanning-protocol/)