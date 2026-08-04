# Liquid AI (liquid-ai)

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

Liquid AI is an MIT spinoff developing Liquid Foundation Models (LFMs) - a new class of generative models based on liquid neural networks. Offers LFM2 (2.6B, 8B-A1B, 24B-A2B) and LFM2.5 (350M, 1.2B variants) with text, vision, audio, and thinking modes. The LEAP platform enables LFM customization and on-device deployment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/liquid-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=liquid-ai-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, Foundation Models, Liquid Networks, Edge AI, On-Device

## APIs
- **Liquid AI Platform API** — Hosted inference plus the LEAP customization/deployment platform and Liquid Playground. [Docs](https://docs.liquid.ai/) · [Pricing](https://www.liquid.ai/pricing) · [Hugging Face](https://huggingface.co/LiquidAI)

### Models
LFM2-2.6B, LFM2-8B-A1B, LFM2-24B-A2B (and Audio / Vision-Language / Thinking variants), LFM2.5-350M, LFM2.5-1.2B (Instruct / Thinking). Pricing (third-party inference, May 2026): LFM2-24B-A2B $0.03/M input · $0.12/M output. LFM2.5-1.2B-Instruct/Thinking available free on OpenRouter.

## Plans, Rate Limits, FinOps
- [Plans](plans/liquid-ai-plans-pricing.yml)
- [RateLimits](rate-limits/liquid-ai-rate-limits.yml)
- [FinOps](finops/liquid-ai-finops.yml)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.liquid.ai/)
- [Documentation](https://docs.liquid.ai/)
- [Hugging Face](https://huggingface.co/LiquidAI)

## Notes
- Liquid AI's primary distribution is via Hugging Face open weights and on-device deployment through LEAP. Hosted-API consumption is also available through aggregators like OpenRouter.
- No public OpenAPI spec discovered at the time of profiling.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
