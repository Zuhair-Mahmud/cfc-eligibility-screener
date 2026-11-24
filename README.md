# Pre-Submission Eligibility Screening Tool

A self-service eligibility screener for the Common Fund for Commodities Call for Proposals.

**Live:** https://zuhair-mahmud.github.io/cfc-eligibility-screener/

## Purpose

The CFC's published materials indicate deal flow in excess of 400 loan requests a year, against 21 projects approved in 2025. The published calendar allocates approximately two months to screening by the Secretariat for completeness and basic criteria before proposals reach the Consultative Committee.

A substantial share of that screening resolves against rules that are fixed and published in advance. This tool applies those rules at the applicant's end, so that an applicant learns whether they qualify before assembling a dossier, and the Secretariat receives a structured record rather than an unscreened application.

## Rule register

Twelve criteria are encoded, each referenced to the published source it derives from:

| Ref | Criterion |
|-----|-----------|
| ELG-01 | Activities financed by the CFC are implemented in a Member State |
| ELG-02 | Applicant domicile, where outside the membership |
| TRK-01 | Track record of at least three years; start-ups not financed |
| TRK-02 | Audited financial statements for the latest three financial years |
| MAN-01 | Activity falls within the mandate |
| MAN-02 | Activity is positioned in a commodity or agricultural value chain |
| EXC-01 | Exclusion List, eleven items |
| FIN-01 | Amount requested against the applicable ceiling and approval track |
| FIN-02 | Co-financing requirement |
| FIN-03 | Instrument availability by organisation type |
| DOC-01 | Section 8.1 required documents |
| ADM-01 | Language of submission |

Every determination reports against these references together with the source document behind each rule, so that an outcome can be reconstructed and audited.

## Sources

Logic derives solely from documents the CFC publishes: the Call for Proposals page and its frequently asked questions, the Member States list, the Call for Proposals application form including the supporting document checklist at Sections 8.1 and 8.2, and the Exclusion List annexed to the Sustainability Policy. No rule has been inferred where the published sources are silent.

## Implementation

A single self-contained HTML document. All screening is performed locally in the browser; no information entered is transmitted, stored or retained. No build step and no dependencies beyond a webfont.

## Status

Independent proof of concept, prepared by Zuhair Mahmud. Not affiliated with, endorsed by, commissioned by or operated by the Common Fund for Commodities, and issuing no decision on its behalf.

Criteria reflect the 29th Call for Proposals as published. The terms of the 30th Call would need to be reflected before any operational use. Document PSE-1.0.
