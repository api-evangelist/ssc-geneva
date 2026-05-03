# SS&C Geneva

SS&C Geneva is an enterprise-grade fund accounting and portfolio management platform for asset managers, hedge funds, and fund administrators. Geneva provides APIs for NAV calculation, trade processing, investor accounting, position management, and regulatory reporting across multi-asset portfolios including equities, fixed income, derivatives, and alternative investments.

- **Website:** https://www.ssctech.com/
- **Documentation:** https://www.ssctech.com/resources
- **Support:** https://www.ssctech.com/about/support-client-portals

## APIs

### SS&C Geneva Fund Accounting API

SS&C Geneva provides fund accounting and portfolio management APIs for asset managers, hedge funds, and fund administrators. APIs enable NAV calculation, trade processing, investor accounting, position management, and regulatory reporting across multi-asset portfolios. Geneva is an enterprise system with REST APIs for integration with external systems including OMS, custodians, and reporting platforms.

- **Base URL:** https://api.ssctech.example.com/geneva/v1
- **Documentation:** https://www.ssctech.com/
- **OpenAPI:** [ssc-geneva-fund-accounting-openapi.yml](openapi/ssc-geneva-fund-accounting-openapi.yml)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [ssc-geneva-fund-accounting-openapi.yml](openapi/ssc-geneva-fund-accounting-openapi.yml) | SS&C Geneva Fund Accounting REST API |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [ssc-geneva-rules.yml](rules/ssc-geneva-rules.yml) | Spectral rules for SS&C Geneva API conventions |

### Capabilities

#### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [fund-operations.yaml](capabilities/fund-operations.yaml) | Unified fund operations and portfolio management workflow |

#### Shared Definitions

| Shared | Description |
|--------|-------------|
| [fund-accounting.yaml](capabilities/shared/fund-accounting.yaml) | SS&C Geneva Fund Accounting API consumer definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [ssc-geneva-portfolio-schema.json](json-schema/ssc-geneva-portfolio-schema.json) | Fund portfolio entity schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [ssc-geneva-fund-structure.json](json-structure/ssc-geneva-fund-structure.json) | Fund accounting structure documentation |

### JSON-LD

| Context | Description |
|---------|-------------|
| [ssc-geneva-context.jsonld](json-ld/ssc-geneva-context.jsonld) | JSON-LD context for SS&C Geneva fund vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [ssc-geneva-list-portfolios-example.json](examples/ssc-geneva-list-portfolios-example.json) | List active hedge fund portfolios example |
| [ssc-geneva-get-nav-example.json](examples/ssc-geneva-get-nav-example.json) | Get official NAV calculation example |

### Vocabulary

| Vocabulary | Description |
|-----------|-------------|
| [ssc-geneva-vocabulary.yml](vocabulary/ssc-geneva-vocabulary.yml) | SS&C Geneva fund accounting vocabulary and terminology |
