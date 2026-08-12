# Elpha Secure

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

Elpha Secure is a New York-based cyber insurance managing general agent (MGA) for small and midsize
businesses that bundles a first-party cybersecurity software agent with the insurance policy itself.
The Elpha Agent ships endpoint detection and response, Malware Guard anti-malware, encrypted offsite
backup, multi-factor authentication for remote desktop access, email security (ES Mail), financial
fraud detection, vulnerability and security-posture scoring, and XDR integrations with SentinelOne,
Sophos, Trend Micro and CrowdStrike, all managed from the Elpha Secure Portal. Policies are
distributed through appointed brokers who quote and bind in the broker portal.

- Website — https://www.elphasecure.com/
- Help Center — https://help.elphasecure.com/en
- Blog — https://blog.elphasecure.com/
- Portal (sign-in) — https://my.elphasecure.com
- Terms — https://www.elphasecure.com/terms
- Privacy — https://www.elphasecure.com/privacy

## API surface

Elpha Secure publishes **no public developer portal, API reference, or machine-readable
specification**. Its Terms of Service (section 9, effective 2025-10-20) define *"Elpha Secure API's"*
as "application programming interfaces that enable external applications to access Elpha Secure
Software (e.g., via SOAP- or REST-based interfaces)" and reference Sample Code and API documentation
made available on the Site to third parties building integrations — but that material is not
publicly reachable. Contract discovery found nothing: `/openapi.json`, `/swagger.json`, `/api-docs`
and every `/.well-known/*` path return 404 on `www`, `my` and `app`; `api.`, `docs.`, `developer.`
and `status.elphasecure.com` do not resolve. See `x-coverage` in `apis.yml`.

What *is* published and captured here: a real `llms.txt` index of the help centre
(`llms/elpha-secure-llms.txt`), SOC 2 Type II and VB100 certification claims
(`conformance/`), and a live TLS/DNS security probe (`security/`).
