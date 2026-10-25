# NEXARA — Public Laboratory Evidence

NEXARA is a software prototype developed by Titan Defense Technologies Inc. for heterogeneous message normalization, deterministic data fusion and resilient information exchange.

This repository provides laboratory evidence referenced in Titan’s proposal for the Canadian Department of National Defence’s IDEaS challenge, **RF Data Fusion for Command and Control**.

## Evidence documents

| Document | File | Scope |
|---|---|---|
| NEXARA Experimental NIEM 6 Mapping Results | [View results](nexara-step15-niem6.json) | Local semantic and provenance round-trip checks for JSON, XML and character-oriented inputs through an experimental NIEM 6-oriented mapping. |
| NEXARA Internal TRL 4 Laboratory Assessment | [View assessment](nexara-step16-trl4-assessment.json) | Titan’s internal assessment of the integrated software subsystem, its supporting evidence and remaining validation gaps. |
| NEXARA Laboratory Evaluator Submission Dossier | [View dossier](nexara-step14-submission-dossier.json) | Consolidated laboratory results, including 86 passing automated tests, an eight-stage simulated DDIL scenario and internal challenge-outcome traceability. |
| NEXARA Separate-Process Laboratory Validation | [View validation](nexara-step17-process-validation.json) | Two-process testing of offline changes, restart persistence, bidirectional synchronization, convergence, conflict preservation, provenance and idempotent retry. |

The laboratory evidence was generated on September 26, 2026, local time in Ontario, Canada. Machine-readable timestamps are recorded in UTC.

## Test environment and scope

Testing used synthetic, non-sensitive messages in a controlled software development environment.

The separate-process validation ran two operating-system processes on one computer, each with an independent SQLite data store. Communication used local process pipes, not a physical network or RF link.

Denied, Degraded, Intermittent and Low Bandwidth (DDIL) conditions were simulated. These results do not establish performance on military radios or operational tactical networks.

The evidence files identify their recorded timestamps, configurations, results and limitations. Laboratory measurements apply to the documented test conditions.

## Technology readiness

Titan self-assesses the integrated software subsystem at **TRL 4**, supported by laboratory integration and validation evidence.

This is an internal assessment. It is not an independent certification, government endorsement or confirmation of operational readiness.

## Standards status

The NIEM 6-oriented mapping is **experimental**. Successful local round trips demonstrate preservation of supported information within the tested implementation; they do not establish NIEM conformance.

Authoritative NIEM reference-schema and exchange-package validation and independent conformance review were not completed for the published experimental mapping.

MTF-oriented XML remains experimental. NCDF remains a design mapping. This repository does not claim certified compliance with NIEM, MTF-XML or NCDF.

## Interpretation of results

The submission dossier uses internal requirement-status labels. These describe Titan’s bounded laboratory checks, not an external determination that every Challenge outcome has been satisfied.

In particular:

- Authoritative standards conformance remains outstanding.
- External simulation or wargaming integration remains unvalidated.
- Monitoring event formatting does not establish a live connection to an external monitoring platform.
- Synthetic domain and service fixtures do not establish operational suitability across all domains.
- No DND/CAF operational validation or security accreditation is claimed.

## Repository contents

This repository contains evidence reports, not the NEXARA application or its source code. It is not a software distribution or installation package.

## Organization

**Titan Defense Technologies Inc.**  
Hamilton, Ontario, Canada
