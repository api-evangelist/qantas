# Qantas (qantas)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Qantas Airways Limited is Australia's flag carrier and, with its low-cost subsidiary Jetstar, one half of a domestic duopoly alongside Virgin Australia. In the distribution chain Qantas is the supplier of its own inventory — it sits upstream of the GDSs (Amadeus, Sabre, Travelport), the aggregators (Duffel, Travelfusion, Mystifly, Verteil, AirGateway, TPConnects, TravelSky) and the large Australian agency groups (Flight Centre, Corporate Travel Management, Webjet). Its API posture is distribution-only and fully gated. Qantas publishes no developer portal, no OpenAPI or Swagger definition, and no public consumer API; `developer.`, `developers.`, `docs.` and `api.qantas.com.au` do not resolve, and `api.qantas.com` returns 404 on every path probed. The one real API is the Qantas Distribution Platform (QDP) NDC XML API, built with Farelogix (now Accelya) and certified by IATA to NDC@Scale. It is documented in prose on Qantas Agency Connect but no endpoint, schema or specification is published; a technology partner must sign a Qantas Distribution Platform Access Agreement, subject to Qantas technical and commercial approval, before it is granted test-environment access, and an agency must hold IATA, ARC, TIDS or VTC accreditation. Public docs on how to get in, no public contract and no exit path.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qantas/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qantas/refs/heads/main/apis.yml)

## Tags

- Travel
- Australia
- Aviation
- Airline
- Distribution
- NDC
- Booking
- Corporate Travel
- Loyalty

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

### Qantas Distribution Platform NDC XML API

The Qantas Distribution Platform (QDP) is Qantas' NDC XML API for airline retailing — shopping, offer and order creation, ticketing, ancillaries and post-booking servicing of Qantas (QF) content for travel agencies, GDSs and aggregators. Built in partnership with Farelogix Inc. (now Accelya) on IATA's New Distribution Capability standard, and certified by IATA to NDC@Scale. Qantas states the platform "does not have a customer-facing user interface" and is "designed to allow Technology Partners to develop a connection to our NDC XML API". No endpoint host, no NDC schema version and no machine-readable specification are published; access requires a signed Qantas Distribution Platform Access Agreement, and agencies must hold IATA, ARC, TIDS or VTC accreditation. Agencies that cannot connect through a Certified Technology Partner may instead use the QDP portal, a web UI powered by Accelya NDC SPRK.

- **Human URL:** [https://agencyconnect.qantas.com/en-au/ndc](https://agencyconnect.qantas.com/en-au/ndc)
- **Base URL:** not published

#### Tags

- NDC
- Airline Distribution
- XML
- Offers and Orders
- Ticketing
- Ancillaries
- Servicing

#### Properties

- [Documentation](https://agencyconnect.qantas.com/en-au/ndc/what-is-ndc)
- [Documentation](https://agencyconnect.qantas.com/en-au/ndc/benefits)
- [Partners](https://agencyconnect.qantas.com/en-au/ndc/approved-technology-partners)
- [Support](https://agencyconnect.qantas.com/en-au/ndc/help-support)
- [Glossary](https://agencyconnect.qantas.com/en-au/ndc/help-support/glossary)
- [RateLimits](https://agencyconnect.qantas.com/en-au/policies/agent-information/ndc-shopping-policy)
- [TermsOfService](https://agencyconnect.qantas.com/en-au/standard-agency-terms-conditions)
- [Portal](https://agencyconnect.qantas.com/en-au/ndc/distribution-platform-portal)
- [Signup](https://agencyconnect.qantas.com/en-au/ndc/distribution-platform-portal/register)
- [TermsOfService](https://agencyconnect.qantas.com/en-au/ndc/distribution-platform-portal/terms-conditions)
- [Pricing](https://agencyconnect.qantas.com/en-au/ndc/premium)

---

## Common Properties

- [Website](https://www.qantas.com/)
- [Portal](https://agencyconnect.qantas.com/en-au)
- [Documentation](https://agencyconnect.qantas.com/en-au/ndc)
- [TermsOfService](https://agencyconnect.qantas.com/en-au/standard-agency-terms-conditions)
- [VulnerabilityDisclosure](https://www.qantas.com/.well-known/security.txt)
- [LinkedIn](https://www.linkedin.com/company/qantas)

## Switching Cost

Recorded in full in [`review.yml`](review.yml) under `switchingCost`. Summary:

| Dimension | Finding |
| --- | --- |
| Interface shape | `standard-plus-proprietary` — IATA NDC XML, certified NDC@Scale, extended with Qantas-only content tiering, qualifiers and commercial entitlements |
| Second source | `no-alternative` — the channel is competitive, the content is monopoly; only Qantas sells Qantas seats |
| Exit path | `no-export-published` — no export, dump, bulk or data-portability operation documented |
| Identifier portability | Shared industry keys (QF, PNR, EMD, IATA/ARC/TIDS/VTC, PCC) plus platform-bound NDC Order ID, QFF number and ABN/QBR corporate codes |
| Contractual lock-in | Qantas Distribution Platform Access Agreement; Standard Agency Terms cl. 1.3 (30 days' notice), 2.1 (accreditation), 2.5 (Ticketing Authority revocable at sole discretion); portal terms forbid hyperlinking to or exposing the portal |
| Distribution model | `ndc-direct` — Qantas runs its own NDC platform and surcharges every other channel |
| Access gate | `commercial-agreement` — plus IATA/ARC/TIDS/VTC accreditation, plus invitation for the surcharge-free Premium tier |

Channel pricing published by Qantas, effective 1 July 2025:

| Channel | Qantas surcharge |
| --- | --- |
| Traditional EDIFACT via GDS | A$11.50 per segment (AU POS); up to US$13 per segment other POS |
| Standard NDC via Amadeus / Sabre / Travelport | A$4.50 or US$3.00 per segment |
| Certified Technology Partner, or the QDP portal | none |
| Premium NDC (invitation / EOI only) | none, and the widest content range |

## No Specifications Harvested

No `openapi/` directory exists. Qantas publishes no OpenAPI, Swagger, AsyncAPI or Postman artifact. Every spec path probed on `qantas.com`, `api.qantas.com` and `agencyconnect.qantas.com` returned HTTP 404; no developer subdomain resolves; there is no Qantas GitHub organization; and Qantas is not listed on the IATA Developer Portal. The NDC XML API contract is disclosed only after a Qantas Distribution Platform Access Agreement is signed. Every URL probed and its HTTP status is recorded in [`review.yml`](review.yml) under `probes`.
