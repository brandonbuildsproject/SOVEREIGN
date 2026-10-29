# SOVEREIGN — Project overview

**Portfolio revision:** 29 October 2026  
**Type:** Independently developed Apple-platform security research workspace  
**Repository role:** Visual documentation only. Private source and operations are intentionally excluded.

## Purpose

SOVEREIGN organises systematic research into platform behaviour, security boundaries and reproducible observations. Its research workflow is built around scoping, controlled testing, evidence retention and independent review rather than unsupported exploit claims.

The screenshots were freshly captured on 29 October 2026 from the latest accepted v2.8.7rc1 interface using a separate, empty test workspace. Later numbered experiments do not represent a newer released user interface.

The private lab contains research tools and experiments not supplied in this repository. The public illustrations show navigation, research planning and evidence workflows, but there are no accessible test controls, binaries, source code, API keys or backend services.

## Research areas

**Native and application-level research.** Controlled synthetic inputs are used to exercise original test harnesses and selected Apple framework APIs. Different host and device configurations are treated separately.

**Evidence and integrity.** Research records include timestamps, source and binary fingerprints, bounded execution records, positive/negative controls and independent checks. A completed test is not, by itself, a security vulnerability.

**Reliability and safety.** An environment failure is reported as an environment failure. For example, native macOS research results are not extrapolated to an iPhone simulator or physical iOS device without corresponding verification.

**Human review.** Severity, programme eligibility and disclosure decisions require additional manual assessment. No automatic Apple vulnerability report is sent by the private lab or by this public repository.

## Current status

Research is ongoing. Several bounded macOS native-input and image-preview campaigns have completed with reproducible outcomes. They have not established an exploitable zero-click or zero-day vulnerability. Current iOS Simulator testing remains restricted by a known first-boot migration problem in the research environment.

## For research-programme reviewers

This repository can be used to understand the project's intent, architecture at a high level, interface style and verification philosophy. It cannot be used to inspect unpublished vulnerabilities, operate the private tool or reproduce confidential research.

The owner can provide appropriate additional evidence via the official authorised review or disclosure process, subject to scope and privacy checks. The existence of this portfolio does not establish eligibility for any bounty or device programme.
