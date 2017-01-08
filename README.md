# **[Work In Progress]** AMWA NMOS Automated Testing

A framework for automated testing of implementations of AMWA Networked Media Open Specifications (NMOS), initially IS-04 (discovery and registration) v1.1.

## Getting started

Readers are advised to be familiar with:
* The JT-NM Reference Architecture (http://jt-nm.org/)
* The [overview of Networked Media Open Specifications](https://github.com/AMWA-TV/nmos)
* The [NMOS Discovery and Registration Specification](https://github.com/AMWA-TV/nmos-discovery-registration) (IS-04)

## Contents

* README.md -- This file
* [LICENSE](LICENSE) -- Licenses for software and text documents
* [NOTICE](NOTICE) -- Disclaimer
* test - A folder of test specifications for an NMOS IS-05 API.

## Work to Date

### Sprint 1

Extraction of the the ledger HTTP-based tests into this project.

Further work this sprint:

* extract the running up of ledger from the tests themselves so that they can be run against ledger of the BBC implementation;
* add in basic v1.1 support to ledger so that it can respond to v1.0 and v1.1 requests;
* add support for the mux'd stream data model for v1.1 calls.
