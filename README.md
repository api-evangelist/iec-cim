# IEC CIM - Common Information Model (iec-cim)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

IEC Common Information Model (CIM) is an international standard developed by the International Electrotechnical Commission for representing electrical power system data and facilitating data exchange between applications. The IEC 61968 and IEC 61970 series define data models and interfaces for distribution management, energy management, and advanced metering infrastructure across electric utility systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/iec-cim/refs/heads/main/apis.yml)

## Scope

- **Type:** Standard
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - AMI, CIM, Energy, Smart Grid, Smart Meter, Utilities, XML

## Timestamps

- **Modified:** 2026-04-28

## APIs

### IEC CIM 61968 Distribution Management API
The IEC CIM 61968 standard defines interfaces for distribution management systems (DMS), enabling integration of outage management, network management, meter reading, and work management systems using CIM XML message exchange.

**Human URL:** [https://www.iec.ch/](https://www.iec.ch/)

**Base URL:** https://ami-gateway.utility.example.com/cim/61968

#### Tags:

 - CIM, Distribution, Energy, Smart Grid, Utilities, XML

#### Properties

- [Documentation](https://www.iec.ch/)
- [Reference](https://cimug.ucaiug.org/)
- [OpenAPI](openapi/iec-cim-61968-distribution-openapi.yml)

### IEC CIM 61970 Energy Management API
The IEC CIM 61970 standard defines the Common Information Model for energy management systems (EMS), enabling data exchange for power system network models, measurements, and topology across transmission utility systems.

**Human URL:** [https://www.iec.ch/](https://www.iec.ch/)

**Base URL:** https://ems-gateway.utility.example.com/cim/61970

#### Tags:

 - CIM, EMS, Energy, Transmission, Utilities, XML

#### Properties

- [Documentation](https://www.iec.ch/)
- [Reference](https://cimug.ucaiug.org/)

### IEC CIM AMI Smart Meter API
The IEC CIM AMI (Advanced Metering Infrastructure) APIs from AMI head-end systems provide smart meter readings, interval data, usage points, and demand response signals using CIM XML data models compliant with IEC 61968-9 for utility grid operations.

**Human URL:** [https://www.iec.ch/](https://www.iec.ch/)

**Base URL:** https://ami-gateway.utility.example.com/cim

#### Tags:

 - AMI, CIM, Energy, Metering, Smart Meter, Utilities, XML

#### Properties

- [Documentation](https://www.iec.ch/)
- [Reference](https://cimug.ucaiug.org/)

## Common Properties

- [Portal](https://www.iec.ch/)
- [Documentation](https://www.iec.ch/)
- [Getting Started](https://cimug.ucaiug.org/)
- [Website](https://www.iec.ch/)
- [GitHub Organization](https://github.com/cimug-org)
- [Developer Tools](https://github.com/cimug-org)
- [OpenAPI](openapi/iec-cim-61968-distribution-openapi.yml)
- [JSONSchema](json-schema/iec-cim-asset-schema.json)
- [JSONLDContext](json-ld/iec-cim-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
