# Object of Conformity: Verifiable Identifier

## Verifiable Identifier

* A **verifiable ident
ifier (VID)** is an address or identifier that is verifiably bound to at least one set of cryptographic keys that are discoverable via an **associated disovery protocol.**

* A VID does not necessarily need to change (i.e., can remain the same) when the controller’s key(s) are rotated or network endpoint(s) are updated.

* An **associated discovery protocol** for VIDS allows entities to locate, retrieve, and authenticate public identifiers and system endpoints associated with a particular VID. The discovery protocol ensures the integrity and authenticity of the identifier information through cryptographic proofs and is intended to reduce potential spoofing or fraudulent activities, and to promotes a seamless, secure exchange of information among peers without relying on central authorities or intermediaries.

* VIDs may be issued via a **centralized** or **decentralized** system. This distinction should have no bearing on the assessing the technical format of the VID. However, the centralized/decentralized distinction may have implications on the management, recognition or use of the VID within a certain context. This context should be well understood as it may impact the overall assessment.

* Decentralizeds VIDs may be further distinguished as **non-autonomous identifiers** or **autonomous identifiers**. As in the previous point, this may or may not have implications on the assessment.

* A VID may be implemented using a variety of schemes, standards and specifications.

## Object of Conformity Criteria

A VID must have the following characteristics:

1. A VID must be resolvable securely to obtain the current public key(s) needed to verify that the VID owner controls the VID.
2. A VID must be resolvable securely to obtain the current network endpoint(s) for establishing a ToIP connection with the entity identified by the VID.
3. A VID must provide an indication that its keys have changed and the previous keys are no longer valid for new transactions.

4. A VID must support at least one defined **out-of-band (OOBI)** process for initial setup.
5. A VID must support at least one **digital signature scheme**.
6. A VID must support at least one **encryption method**.
7. A VID must support at least one **associated discovery protocol**.

## Reliable System Criteria

An **electronic transferable record (ETR)** that incorporates a VID may exist independently of the system of issuance.  

A VID must be used in the issuance of an ETR to enable independent verification outside of the system of issuance.

In evaluating the reliability of a VID the following requirements based on the [general reliability criteria](./obj-criterion.md) will be applied:

1. **Criterion 1: Same Information:** The VID must confirm that the information is the same as what originated from the system of issuance.  
2. **Criterion 2: Singularity:** The VID must confirm that the information originates from an authoritative record.
3. **Criterion 3: Control:** The VID must demonstrate that the ETR is under exclusive control.
4. **Criterion 4: Integrity** The VID must be confirm the integrity of the ETR, including any authorized changes to the ETR.
5. **Criterion 5: Reliable System** The VID must demonstrate that it originates from a reliable system used in conjunction with ETR system of issuance.

## References

1. [ToIP Trust Spanning Protocol for Muggles](https://docs.google.com/presentation/d/1dgaTwxRubnpj7M83840mz53_iJfwEkajndrBBEQthgU/edit#slide=id.gc6f919934_0_20)
2. [MID-YEAR PROGRESS REPORT ON THE TOIP TRUST SPANNING PROTOCOL](https://trustoverip.org/blog/2023/08/31/mid-year-progress-report-on-the-toip-trust-spanning-protocol/)
