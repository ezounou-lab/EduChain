# EduChain MVP

## Overview

The EduChain MVP focuses on one fundamental capability:

> Issuing and verifying an academic credential using a cryptographic proof anchored on a blockchain.

The MVP is intentionally limited in scope. Its purpose is to demonstrate the core trust mechanism before introducing additional platform features.

## Actors

The MVP involves three primary actors.

### 1. Educational Institution

The institution is responsible for:

* verifying the student's academic achievement;
* creating the credential;
* certifying the credential;
* initiating the credential issuance process.

### 2. Student

The student is the owner or recipient of the academic credential.

The student should be able to:

* receive the credential;
* retain access to it;
* present it to a third party for verification.

### 3. Verifier

A verifier may be an employer, university, institution, or other authorized party.

The verifier should be able to determine whether the presented credential corresponds to the cryptographic proof recorded on the blockchain.

## Core Workflow

### Credential Issuance

```text
Academic Achievement
        ↓
Institution Verification
        ↓
Credential Creation
        ↓
Document Hash
        ↓
Blockchain Anchoring
        ↓
Credential Issued
```

### Credential Verification

```text
Presented Credential
        ↓
Hash Generation
        ↓
Blockchain Lookup
        ↓
Hash Comparison
        ↓
Valid / Invalid
```

## MVP Requirements

The first version should demonstrate the following capabilities:

* creation of an academic credential;
* generation of a deterministic cryptographic hash;
* recording or anchoring the hash on a blockchain;
* retrieval of the blockchain proof;
* verification of the credential against the recorded proof.

## Privacy Principle

Sensitive academic information should not be stored directly on a public blockchain.

The blockchain should contain only the minimum information required to establish the integrity of the credential.

The detailed academic record should remain off-chain.

## Out of Scope

The following features are intentionally outside the initial MVP:

* complete university management systems;
* payment systems;
* social networking features;
* advanced student analytics;
* large-scale identity management;
* complex user interfaces;
* multi-chain support.

These features may be considered in future versions.

## Future Extensions

Once the MVP is functional, the project may evolve to include:

* decentralized identity;
* verifiable credentials;
* credential revocation;
* expiration dates;
* institutional dashboards;
* student wallets;
* multiple blockchain networks;
* interoperability with existing educational systems.

## Success Criteria

The MVP can be considered successful when an independently created credential can be:

1. issued by an institution;
2. cryptographically hashed;
3. anchored on a blockchain;
4. presented by a student;
5. independently verified by a third party.
