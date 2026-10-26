# Skydio (skydio)

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

Skydio is a U.S. manufacturer of autonomous drones for public safety, defense, and enterprise customers, building self-flying aircraft such as the X10, X10D, X2, and S2+ along with the Skydio Cloud platform for fleet management, mission planning, live telemetry, and media sync. Skydio exposes a public REST API through Skydio Cloud (apidocs.skydio.com) for managing vehicles, docks, flights, missions, media, alerts, webhooks, and users, alongside on-vehicle integration interfaces such as the Control & Telemetry ICD, Android Intent API, and Attachment ICD for partners and developers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/skydio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/skydio/refs/heads/main/apis.yml)

## Tags

- Autonomous Systems
- Defense
- Drones
- Enterprise
- Fleet Management
- Public Safety
- Robotics
- Unmanned Aerial Vehicles

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Skydio Cloud API

The Skydio Cloud API is an HTTP-based REST API with JSON request and response bodies that lets developers manage Skydio drone fleets programmatically. It covers vehicles, docks, controllers, batteries, attachments, and sensor packages; mission templates, scheduled missions, mission control, and mission results; flights and telemetry (including live telemetry); media files, downloads, thumbnails, and scans; alerts and markers; users, external contacts, and distribution lists; webhooks, remote video, and media transfer; plus JWT/JWK validation and OpenAPI spec endpoints for administration.

- **Human URL:** [https://apidocs.skydio.com/reference/introduction](https://apidocs.skydio.com/reference/introduction)

#### Tags

- Drones
- Fleet Management
- Live Telemetry
- Missions
- REST API
- Webhooks

#### Properties

- [Documentation](https://apidocs.skydio.com/docs)
- [API Reference](https://apidocs.skydio.com/reference/introduction)
- [Authentication](https://support.skydio.com/hc/en-us/articles/4402958154651-How-to-Generate-an-API-Token-for-a-Skydio-Cloud-Integration)
- [Getting Started](https://apidocs.skydio.com/docs)
- [Changelog](https://apidocs.skydio.com/changelog)
- [L L Ms Txt](https://apidocs.skydio.com/llms.txt)
- [Postman Collection](collections/skydio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/skydio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Skydio Control & Telemetry ICD

Real-time command and control interface for the Skydio X10D using MAVLink/RAS-A, enabling integration with ground control stations and third-party autonomy stacks. Access is gated through Skydio Support.

- **Human URL:** [https://www.skydio.com/developer-tools](https://www.skydio.com/developer-tools)

#### Tags

- Defense
- MAVLink
- RAS-A
- Telemetry

#### Properties

- [Product Page](https://www.skydio.com/developer-tools)
- [Support](https://support.skydio.com/)
- [Postman Collection](collections/skydio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/skydio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Skydio Android Intent API

Android Intent API for the X10D Controller that lets third-party Android applications running on the controller receive information from the Skydio flight stack.

- **Human URL:** [https://www.skydio.com/developer-tools](https://www.skydio.com/developer-tools)

#### Tags

- Android
- Controller
- Intent API

#### Properties

- [Product Page](https://www.skydio.com/developer-tools)
- [Support](https://support.skydio.com/)
- [Postman Collection](collections/skydio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/skydio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Skydio Attachment ICD

Mechanical, electrical, and power interface specification for building custom attachments and payloads for the Skydio X10 and X10D platforms. Access requires a request through Skydio.

- **Human URL:** [https://www.skydio.com/developer-tools](https://www.skydio.com/developer-tools)

#### Tags

- Attachments
- Hardware
- Payloads

#### Properties

- [Product Page](https://www.skydio.com/developer-tools)
- [Support](https://support.skydio.com/)
- [Postman Collection](collections/skydio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/skydio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.skydio.com/)
- [Portal](https://apidocs.skydio.com/)
- [Developer Tools](https://www.skydio.com/developer-tools)
- [Integrations Catalog](https://www.skydio.com/integrations-catalog)
- [Documentation](https://apidocs.skydio.com/docs)
- [API Reference](https://apidocs.skydio.com/reference/introduction)
- [Changelog](https://apidocs.skydio.com/changelog)
- [Support](https://support.skydio.com/)
- [Status Page](https://www.skydio.com/platform/reliability-dashboard)
- [Training](https://www.skydio.com/skydio-academy)
- [Blog](https://www.skydio.com/blog)
- [Login](https://cloud.skydio.com/)
- [Careers](https://www.skydio.com/careers)
- [Contact Sales](https://www.skydio.com/contact-sales)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
