# RAML

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

RAML (RESTful API Modeling Language) is a YAML-based specification language for describing RESTful APIs with first-class support for reusable patterns, traits, resource types, annotations, libraries, overlays, and extensions. Developed by MuleSoft and Salesforce; RAML 1.0 is the current stable version. The raml-org GitHub organization repositories were archived read-only in February 2024.

- **Website:** [raml.org](https://raml.org)
- **Specification:** [github.com/raml-org/raml-spec](https://github.com/raml-org/raml-spec)
- **GitHub Organization:** [github.com/raml-org](https://github.com/raml-org)
- **Documentation:** [raml.org/developers/raml-100-tutorial](https://raml.org/developers/raml-100-tutorial)
- **Forum:** [forum.raml.org](https://forum.raml.org)

## Scope

- **Type:** Index (Standard)

## Tags

API Design, Specification Language, Standards, YAML, REST, API Modeling

## Specification

### RAML Specification
The canonical RAML 1.0 specification is at [github.com/raml-org/raml-spec](https://github.com/raml-org/raml-spec).

Key constructs in RAML 1.0:
- **Types**: Unified type system replacing separate schema constructs
- **Traits**: Reusable method-level behaviors (applied with `is:`)
- **Resource Types**: Reusable resource patterns (applied with `type:`)
- **Annotations**: Typed extensibility mechanism
- **Libraries**: Modular reuse via `uses:` imports
- **Overlays / Extensions**: Separated metadata and functional enhancement layers
- **Security Schemes**: OAuth 1.0/2.0, Basic, Digest, Pass Through

## Tooling Ecosystem

| Tool | Repository | Description |
|---|---|---|
| webapi-parser | [raml-org/webapi-parser](https://github.com/raml-org/webapi-parser) | Multi-format parser: RAML 0.8, 1.0, OAS 2.0, OAS 3.0 |
| raml-js-parser-2 | [raml-org/raml-js-parser-2](https://github.com/raml-org/raml-js-parser-2) | JavaScript RAML parser |
| raml-php-parser | [raml-org/raml-php-parser](https://github.com/raml-org/raml-php-parser) | PHP RAML parser |
| ramldt2jsonschema | [raml-org/ramldt2jsonschema](https://github.com/raml-org/ramldt2jsonschema) | Convert RAML types ↔ JSON Schema |
| raml-tck | [raml-org/raml-tck](https://github.com/raml-org/raml-tck) | Test Compatibility Kit for RAML 1.0 |
| raml-mock-service | [raml-org/raml-mock-service](https://github.com/raml-org/raml-mock-service) | Generate mock services from RAML |

## Artifacts

### JSON Schema
| File | Description |
|---|---|
| [json-schema/raml-document-schema.json](json-schema/raml-document-schema.json) | JSON Schema for RAML 1.0 document structure |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/raml-document-structure.json](json-structure/raml-document-structure.json) | RAML 1.0 document structure documentation |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/raml-context.jsonld](json-ld/raml-context.jsonld) | Linked data context for RAML vocabulary |

### Examples
| File | Description |
|---|---|
| [examples/raml-basic-api-example.json](examples/raml-basic-api-example.json) | Basic RAML 1.0 API definition example |
| [examples/raml-traits-example.json](examples/raml-traits-example.json) | RAML traits usage example |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/raml-vocabulary.yml](vocabulary/raml-vocabulary.yml) | RAML normative vocabulary (constructs, conformance terms) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
