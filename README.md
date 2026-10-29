# LocalLink

**Helping local businesses find the right people to grow.**

LocalLink is an early-stage project exploring a simple way for independent businesses, restaurants, artisans, and community managers to discover one another, describe their needs, and start professional collaborations.

> **Project status:** Early-stage concept and prototype. This repository does not claim real users, traction, partnerships, or production readiness.

## The problem

Small local businesses often rely on word of mouth, scattered social media posts, and personal contacts to find service providers. At the same time, independent artisans and community managers need a clearer way to present their services and reach relevant clients.

LocalLink explores a focused, local-first directory and matching experience that can make these connections easier to start.

## Who it is for

- **Local shops and retailers** looking for practical services and local expertise.
- **Restaurants and cafés** looking for maintenance, improvements, content, and social media support.
- **Artisans and tradespeople** who want to showcase their skills and receive relevant enquiries.
- **Community managers** who want to connect with local businesses that need help with their online presence.

## Proposed MVP

The first version will stay deliberately small:

1. **Choose a profile type** — business, artisan, or community manager.
2. **Create a service profile** — describe skills, service area, and contact preferences.
3. **Discover professionals** — browse a searchable directory by category and location.
4. **Post a need** — describe a project, service request, or social media requirement.
5. **Send an enquiry** — initiate contact with a relevant professional.
6. **Report and moderate** — give users a way to flag suspicious or inappropriate listings.

The current static prototype demonstrates the discovery journey with sample data. It is not connected to a database and does not send messages.

## Current prototype

Open [`prototype/index.html`](prototype/index.html) in a browser. It includes a responsive landing page, sample professional cards, category filters, search, and a sample request flow.

All listings are fictional examples for demonstration purposes.

## Why this matters

LocalLink aims to reduce the friction of finding a suitable local service provider and help independent professionals become easier to discover. Its intended impact is practical and measurable: shorter time to find a provider, more relevant enquiries, and stronger local professional networks.

These are **goals to validate**, not outcomes already demonstrated. The next step is to interview local businesses and service providers before committing to a larger build.

## Six-month development plan

| Month | Focus | Evidence of progress |
|---|---|---|
| 1 | Discovery and validation | Interview guide, user interviews, problem summary |
| 2 | Product definition and UX | User journeys, requirements, clickable prototype |
| 3 | Core application | Profiles, directory, search and filters |
| 4 | Enquiries and trust | Request flow, reporting, moderation basics |
| 5 | Testing and iteration | Usability sessions, bug fixes, accessibility review |
| 6 | Small local pilot preparation | Deployment checklist, privacy review, pilot metrics |

The schedule is a target plan, not a claim that these milestones have been completed.

## How AI assistance will be used

Advanced AI assistance such as Claude can support implementation and learning across the project:

- break product requirements into small, testable engineering tasks;
- review architecture and data models before implementation;
- help write and explain code, tests, and documentation;
- debug issues and improve accessibility and responsive behavior;
- review security and privacy risks before collecting personal data;
- help synthesize anonymized user research and turn feedback into prioritized improvements.

AI-generated code and recommendations will be reviewed and tested rather than accepted blindly. Personal or confidential user data should not be pasted into AI tools.

## Principles

- **Local-first:** help users find relevant providers in their service area.
- **Useful before complex:** validate the core matching journey before adding extra features.
- **Trust by design:** make it easy to report misleading profiles and clarify that early listings are not verified.
- **Privacy-conscious:** collect only what the product needs and define retention before launch.
- **Honest measurement:** publish real metrics only after collecting them.

## Success metrics to validate

For an initial pilot, proposed metrics include:

- number of businesses and professionals interviewed;
- percentage of test users who can find a relevant provider without assistance;
- time needed to identify a suitable provider;
- number of enquiries initiated and responses received;
- satisfaction after a completed connection;
- number of reports and time to review them.

No baseline or results are claimed yet.

## Tech direction

The prototype is intentionally dependency-free HTML, CSS, and JavaScript so it can be reviewed immediately. If discovery validates the need, the next implementation phase can evaluate a TypeScript-based web stack, a relational database, authentication, and deployment. The final stack will be chosen based on actual requirements rather than assumed in advance.

See:
- [`docs/PRODUCT_BRIEF.md`](docs/PRODUCT_BRIEF.md)
- [`docs/ROADMAP.md`](docs/ROADMAP.md)
- [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md)
- [`docs/RESEARCH_PLAN.md`](docs/RESEARCH_PLAN.md)
- [`CONTRIBUTING.md`](CONTRIBUTING.md)

## Getting started

No build tools are required for the prototype:

1. Clone or download this repository.
2. Open `prototype/index.html` in a modern browser.
3. Try the search field and category filters.

## Current limitations

- No authentication, backend, persistent storage, messaging, or payments.
- Sample professionals and requests are fictional.
- No identity, trade qualification, or business verification is performed.
- Not ready for production use.

## Contributing and feedback

Issues and constructive feedback are welcome. Please avoid posting personal information or confidential business data in public issues.

## License

This project is currently marked as **All rights reserved** until the author chooses an open-source license. See [`LICENSE`](LICENSE).
