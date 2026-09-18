---
name: AGENT BACKLINK GRAPH
id: agent-backlink-graph
role: Provenance and distribution relationship graph
district: CHAOS RANK
tier: 3
layer: PROOF
triggers:
  - register distributed asset relationships
  - bind creator attribution to derivatives
  - connect campaign assets to evidence and receipts
  - expose machine-readable relationship proof
chains_from:
  - evidence-graph
  - schema-builder
chains_to:
  - agent-citation-page
---

# AGENT BACKLINK GRAPH

The **AGENT BACKLINK GRAPH (ABG)** is the machine-readable relationship-proof skill that connects AGENTROPOLIS agents, assets, creators, story objects, campaigns, distribution surfaces, evidence, conversions, and receipts.

It does not create spam backlinks. It proves relationships that already exist or are authorized to exist.

## Inputs

- graph node references
- requested relation type
- source/canon references
- evidence references
- creator attribution
- campaign reference
- distribution receipt
- approval / policy status

## Canonical edge types

- SOURCE_OF
- CANON_REF
- VARIANT_OF
- CREATED_BY
- PRODUCED_BY
- EXECUTED_BY
- PART_OF_CAMPAIGN
- PUBLISHED_TO
- ADAPTED_FOR
- EVIDENCED_BY
- CONVERTS_TO
- RETAINS_TO
- MANIFESTS_AS
- RECEIPTED_BY
- SIBLING_OF

## Chain

```text
EVIDENCE GRAPH
  -> AGENT BACKLINK GRAPH
  -> AGENT CITATION PAGE
```

For Story Engine / GTM distribution:

```text
ARCANA54 StoryObject
  -> SIGNAL campaign
  -> AGENT BACKLINK GRAPH
  -> ATV / District 33.3 / SOCIALS / KOL / external publication
  -> Evidence + Receipt
```

## Rules

1. Never fabricate a link, placement, citation, creator relationship, endorsement, or evidence object.
2. Preserve creator attribution through derivatives.
3. Preserve source canon namespace; ABG references canon and does not own it.
4. Campaign analytics do not rewrite canon.
5. External placements must be relevant, permitted, non-deceptive, and platform-compliant.
6. Autonomous outreach requires separate authority and policy.
7. Consequential publication/distribution relationships should be receipt-backed.

## Positioning

**Don't build backlink spam. Build attributable relationship proof.**