# RAML

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
