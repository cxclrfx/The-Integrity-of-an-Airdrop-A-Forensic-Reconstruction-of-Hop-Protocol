# From Eligibility to Integrity
## A Blind Reconstruction of the Hop Airdrop

> **The candidate universe was frozen.  
> The official baseline was still closed.  
> Both analytical outputs were completed, hashed, and receipted before comparison began.**

**The Blockchain Casebook — Resolved File 002**  
**System:** AIE — Airdrop Integrity  
**Author:** `cxclrfx`  
**Version:** `1.0`  
**Date:** 23 August 2026  
**Status:** Frozen historical result / independent blind reconstruction

---

## Abstract

Airdrop integrity is often reduced to a final list:

```text
eligible
excluded
unresolved
```

But the difficult work begins before those labels exist.

A distribution team must determine whether thousands of apparently independent wallets represent:

- independent participants;
- repeated automation;
- coordinated wallet groups;
- infrastructure hubs;
- legitimate shared routes;
- or structures that remain unresolved.

This case study reconstructs a completed blind analysis of the public Hop airdrop topology corpus.

The experiment used the complete frozen historical universe of:

```text
43,058 addresses
6,057,473 directed public relationship rows
183 source files
5 networks
```

Two analytical runs were completed before the official Hop baseline was authorized or opened.

Run A used a comparator-aligned neutral topology representation without official labels, outcomes, memberships, comparator scores, or post-cutoff facts.

Run B deliberately removed the richer evidence fields and retained only a raw generic graph.

The contrast was decisive:

```text
Run A recovered 5,819 of 14,195 official exclusions
Run B recovered 0 of 14,195
```

This is not presented as perfect recovery.

It demonstrates something more useful:

> **A visible graph is not the same thing as sufficient evidence to understand the graph.**

The result also shows how a distribution can be reviewed privately after the candidate set is frozen and before the final allocation decision is released.

---

## 1. The problem behind an airdrop list

At the end of an airdrop process, a project may hold a table like:

```text
wallet
allocation
eligibility status
review status
```

That table is the output.

It is not the evidence.

Before distribution, the project still has to answer:

1. Which wallets belong to meaningful local structures?
2. Which connections are caused by exchanges, bridges, routers, contracts, or other infrastructure?
3. Which groups reproduce known farming patterns?
4. Which structures deserve exclusion?
5. Which structures are supported but not proven?
6. Which wallets must remain unresolved rather than being forced into a binary answer?
7. Can every decision be traced back to frozen evidence?

The Hop case was designed around those questions.

---

## 2. Frozen historical benchmark

The accepted experiment used the complete historical Hop benchmark universe:

| Object | Frozen value |
|---|---:|
| Addresses | **43,058** |
| Directed relationship rows | **6,057,473** |
| Source files | **183** |
| Networks | Ethereum, Arbitrum, Optimism, Polygon, Gnosis |
| Official excluded addresses | **14,195** |
| Official groups | **610** |

This repository reports the frozen historical benchmark.

Later repository snapshots may contain slightly different row or address counts. They are not substituted into this result.

The experiment measured complete-universe topology coverage, not complete raw-event coverage.

---

## 3. The blind sequence

The analysis followed a strict order:

```text
input frozen
→ run contract frozen
→ Run A completed
→ Run A output frozen
→ Run B completed
→ Run B output frozen
→ dual-freeze verified
→ baseline access authorized
→ official baseline opened
→ comparison and reconciliation
```

Exact chronology:

```text
dual-freeze verified:
2026-07-31T13:00:30.879286Z

baseline authorization:
2026-07-31T13:00:30.893327Z

baseline opened:
2026-07-31T13:01:28.720032Z
```

The accepted AIE core was reverified as:

```text
80 / 80 byte-identical
```

No AIE rerun, input change, threshold tuning, baseline rewrite, or external-data substitution occurred during final acceptance and reconciliation.

---

## 4. Run A — neutral topology with comparator-aligned public facts

Run A contained no official Hop labels, outcomes, group memberships, comparator scores, or post-cutoff facts.

It produced:

| Metric | Result |
|---|---:|
| Detected structures | **2,249** |
| Detected addresses | **12,919** |
| Official exclusions recovered | **5,819 / 14,195** |
| Official exclusions missed | **8,376** |
| Official-exclusion recall | **40.993308%** |
| Runtime | **1,514.500 seconds** |

The runtime corresponds to approximately:

```text
25.24 minutes
```

for a frozen corpus containing more than six million relationship rows.

The result is substantial and partial.

It is not described as:

- 100% recovery;
- a universal truth label;
- an automatic exclusion decision;
- proof that every detected address belongs to one controller.

---

## 5. Run B — raw-topology ablation

Run B imported the same:

```text
43,058 addresses
6,057,473 directed relationships
```

under unchanged accepted defaults.

But every row was deliberately reduced to:

```text
generic contract_call
empty method
generic topology asset
fixed time
zero amount
```

This removed:

- transaction identity;
- real time;
- amount;
- asset;
- method;
- verified contract role;
- trace facts.

Run B is therefore classified as:

```text
VALID_RAW_TOPOLOGY_ABLATION_ONLY
```

Its result:

| Metric | Result |
|---|---:|
| Official exclusions recovered | **0 / 14,195** |
| Detected addresses | **3** |
| Detected structures | **1** |
| Official groups recovered | **0 / 610** |
| Runtime | **1,462.563 seconds** |

Run B is not AIE's full native capability.

It is a controlled demonstration of what disappears when the evidence plane is reduced to a generic graph.

---

## 6. What the two runs reveal

Both runs saw the same address universe.

Both runs imported the same number of directed relationships.

Both runs completed normally under unchanged accepted defaults.

But their outcomes were radically different:

```text
same addresses
+ same relationship count
+ different evidence content
=
different recoverable structure
```

The lesson is operational:

> **The number of graph edges does not determine the quality of an airdrop-integrity review. The meaning attached to those edges matters.**

A useful review must preserve distinctions such as:

- who funded whom;
- when activity occurred;
- which asset moved;
- which method was used;
- whether an endpoint is infrastructure;
- whether several routes converge;
- whether a pattern repeats;
- whether evidence supports control, coordination, or only proximity.

---

## 7. Address-level comparison

Against Hop's published binary disposition, Run A produced:

```text
TP = 5,819
FP = 7,096
FN = 8,376
TN = 21,761
```

Derived metrics:

| Metric | Result |
|---|---:|
| Precision | **45.056136%** |
| Recall | **40.993308%** |
| False-positive rate | **24.590221%** |
| Specificity | **75.409779%** |
| Balanced accuracy | **58.201543%** |
| F1 | **42.928809%** |
| Lift over same-size random selection | **1.366507×** |
| Odds ratio | **2.130477** |
| Exact hypergeometric upper tail | **9.184385704305657197845454438790E-261** |

These values measure agreement with Hop's published disposition.

They do not convert the official baseline into universal truth.

A detected wallet that remained final-eligible is a disagreement or review candidate, not proof that the detected structure is false.

---

## 8. Group-level reconstruction

Across all 610 official groups:

| Recovery tier | Groups |
|---|---:|
| Exact full member set | **7** |
| 100% member recall | **12** |
| 90% to below 100% | **5** |
| 75% to below 90% | **18** |
| 50% to below 75% | **94** |
| Below 50% | **341** |
| Missed | **140** |

Exact member-set recovery is a subset of the 100%-recall tier.

Invalid, needs-more-information, unresolved, after-deadline, and other official issue states were preserved separately.

No invalid report was promoted into an accepted official-group recovery.

---

## 9. Additional structures and claim discipline

Before comparison, an additional structure was defined as:

> **A deduplicated detected structure with zero member overlap with every official Hop group used in the published baseline.**

Under that frozen definition:

### Run A

```text
420 TOPOLOGY_VALIDATED
579 UNRESOLVED
2 INSUFFICIENT_EVIDENCE
0 INDEPENDENTLY_CONFIRMED
0 CONTRADICTED
```

### Run B

```text
1 TOPOLOGY_VALIDATED
0 other candidates
```

### Combined

| Status | Count |
|---|---:|
| Independently confirmed | **0** |
| Topology-validated under preregistered criteria | **421** |
| Topology-supported candidates | **0** |
| Unresolved | **579** |
| Insufficient evidence | **2** |
| Contradicted | **0** |

Separately:

```text
1,248 Run A structures
```

overlapped at least one official group and were excluded from the additional-structure count.

All 421 topology-validated additional structures were wholly inside Hop's published final-eligible plane.

They are not described as:

- confirmed Sybil groups;
- confirmed abuse;
- proof of common control.

Final-eligible overlap also does not prove they are false.

The correct public conclusion is:

```text
the structure is supported by the frozen topology rule
```

not:

```text
one person certainly controls every wallet
```

---

## 10. Cryptographic receipts

### Accepted system and run contract

```text
Accepted AIE core manifest
c6692c563e5bb25deebca5de4eab8eedcd051281464d9a08e1f5ee74922b82fa

Run contract
f4f5edf0e8a188412d6bca737bc663c8144d170486d4d20b23907de7ca776ba1
```

### Run A

```text
Input
0064ea13b7b2588af259f8ea67e7ee5cc4a99eaad98cb3ddd5683271a9a20964

Output manifest
7ccd0dcf939a36fb39c3647d4db5bd69a8c1b5a29f44093bf6b146ba4fc39ac3

Output tree
9a60e5c9ae07e1b257abb0f056cb5d0891ae3e591c3dc1f64e32feeb6a81bf48

Receipt
950c49b8dce1535fbf4b9420685ea8548b2e8b6053f7670d5a8c3cefcedd8d88
```

### Run B

```text
Input
19af8146d087d2c820895e4ad372ff04f473bd45b471ec3d1bccb47eeb0f0ebc

Output manifest
5ff55d29bd34572d8500220151464850c8ebd4ac3300e41d0a45b320194ecaa3

Output tree
95403950a4e1f0f3585fb79f294b04d639bd427bba3316b791d00f71029f75b0

Receipt
6e02ac69042b0b016ec63921e85c1a102a9e59e2113070bdac68968fa6a85318
```

### Opened baseline

```text
4801deec3159e403607dfd1e79f266e6a5e199b0e22498280a0bb760bc4c8931
```

### Public evidence assets

```text
AIE_HOP_FROZEN_ARTIFACT_WALKTHROUGH_PUBLIC_SHORT.mp4
SHA-256:
99ddb0ac218f06e1c01ce64863bca10afd7ad0b85ac4189febc2d56ddf664c62

AIE_HOP_FINAL_RELEASE_HANDOFF.zip
SHA-256:
627ea0e0f88f2f4a6823e0446d201f109dd10c181256ca8f1bbf64eb8043bee0
```

The exact UTC receipts remain inside the frozen evidence package.

---

## 11. Independent acceptance

Two completed reviews independently accepted:

- the 80/80 AIE core identity;
- the blind chronology;
- Run A and Run B address metrics;
- all 610 official-group tiers;
- the Run B ablation classification;
- the final additional-structure population rule.

They reported:

```text
0 material metric mismatches
```

The final reconciliation mechanically reproduced:

```text
Run A: 420 / 579 / 2
Run B: 1 topology-validated structure
```

No common-structure status mismatch remained.

---

## 12. What this case proves

This case establishes that:

1. A complete candidate universe can be frozen and processed under a reproducible evidence contract.
2. Analytical outputs can be completed and hashed before the official comparison baseline is opened.
3. A substantial portion of known Hop exclusions can be recovered from a neutral public topology representation.
4. Raw connectivity alone is insufficient.
5. Removing transaction, time, value, asset, method, role, and trace facts can collapse useful recovery to zero.
6. Official-group recovery, additional structures, unresolved structures, and insufficient evidence can remain separate.
7. The system can preserve exact provenance through manifests, receipts, hashes, and an immutable chronology.
8. Airdrop integrity does not require every wallet to be forced into an immediate binary decision.

---

## 13. What this case does not prove

This result does not establish:

- universal Sybil-detection accuracy;
- complete recovery of every Hop group;
- that every final-eligible disagreement is abusive;
- that every topology-validated group has one controller;
- that a topology-only result equals a full-event result;
- that every future airdrop has the same structure;
- that an address list alone always contains enough evidence.

The input plane determines the strongest claim that can be made.

---

## 14. How a pre-distribution review works

A project does not need to transfer its entire distribution process to several external vendors.

A controlled review can be performed after the candidate set is frozen and before the final distribution decision.

### Stage 1 — Freeze the review object

The project supplies or authorizes access to:

```text
candidate wallet list
proposed allocations
eligibility rules
snapshot timestamp
chain and contract boundaries
approved exclusions / exceptions, if any
normalized relationship or event data
```

Every accepted input is hashed and recorded.

### Stage 2 — Validate the data package

Checks include:

```text
schema
address normalization
duplicates
missing rows
chain separation
time boundary
source provenance
allocation totals
data completeness
```

### Stage 3 — Execute the integrity review

The review produces:

```text
known-pattern recovery
candidate structures
address evidence
group evidence
accepted relationships
rejected relationships
unresolved structures
insufficient-evidence structures
allocation-impact scenarios
```

### Stage 4 — Freeze the output

The complete output is hashed before:

- the project's internal labels are opened;
- exclusions are finalized;
- the Merkle root is generated;
- claims are opened;
- or the final distribution is published.

### Stage 5 — Deliver the decision package

The project receives:

```text
review summary
wallet-level decisions
group-level evidence
unresolved list
exception list
provenance manifest
hash receipts
reproducibility record
```

The project retains final decision authority.

---

## 15. What input is actually required

A list of wallet addresses is enough to define the candidate universe.

It is not always enough for the strongest analysis.

### Minimum viable review

```text
frozen wallet list
allocations
eligibility rules
snapshot boundary
relationship export or authorized data source
```

### Stronger full-event review

Add:

```text
transaction identity
real timestamps
amounts
assets
methods
verified contract roles
trace facts
funding and sweep routes
claim and post-claim events
```

The Hop ablation demonstrates why this distinction matters.

A generic graph may show that addresses are connected.

Richer event evidence is what helps determine why they are connected and whether the connection is relevant to distribution integrity.

---

## 16. Delivery models

### One-time confidential review

A project submits one frozen distribution package and receives one complete result.

### Rapid pre-distribution review

A project reserves a review window, freezes its candidate package, and receives the result before the final allocation is published.

The actual turnaround depends on:

- number of wallets;
- event volume;
- number of chains;
- input normalization;
- completeness of the evidence package;
- requested review depth.

The accepted Hop Run A execution itself completed in approximately 25.24 minutes after the corpus was already frozen and ready.

Collection, schema repair, source reconciliation, and final human review are separate from execution time.

### Private institutional deployment

A project or infrastructure provider can operate a closed deployment through one trusted operator under an agreed scope.

The public case study does not disclose private implementation details.

---

## 17. Reproducibility challenge

Recompute the result from:

- frozen input hashes;
- output manifests;
- run receipts;
- structure-member hashes;
- the published official-group baseline;
- the explicit zero-overlap rule.

A valid challenge should identify a specific reproducible disagreement in:

```text
address count
group tier
status
scope decision
receipt
hash
chronology
```

A general disagreement without a reproducible counterexample does not alter the frozen result.

---

## 18. Public sources

- Hop airdrop repository:  
  https://github.com/hop-protocol/hop-airdrop
- Hop Protocol:  
  https://hop.exchange/
- Public comparison methods and evidence are described in this repository.
- Raw private paths, credentials, environment metadata, and private internal research methods are not published.

---

## 19. Publication, rights, and contact

This repository contains an independent technical analysis of publicly available Hop airdrop data and frozen evidence artifacts.

Hop Protocol and its public datasets belong to their respective authors and maintainers. This work does not claim authorship of the Hop airdrop or its official exclusion process.

No open-source license is granted for this article in version 1.0.

Copyright remains with the author.

Organizations interested in:

- confidential pre-distribution review;
- rapid review of a frozen candidate set;
- independent verification;
- private deployment;
- or integration with an identity, eligibility, or distribution system

may open a GitHub issue without including private wallet lists, personal data, unpublished vulnerabilities, credentials, or confidential campaign material.

Sensitive engagement details should move to a private channel after initial contact.

---

**Copyright © 2026 cxclrfx. All rights reserved.**
