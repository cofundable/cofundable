# Architecture Decision Records (ADRs)


## About ADRs

### Why do we choose to document architecture decisions?

Here at Cofundable, we're committed to transparency in all that we do. That includes being transparent with how we make certain decisions about our platform, the code that backs it, and the organization it supports. We choose two document the choices we make about each of these things for a few key reasons:

1. **Participation:** Collective action is core to the philosophy of Cofundable. We aim to be as inclusive in our approach to making critical decisions about our software architecture and organizational strategy as we are in other areas like funding and feature development. Formalizing the process around how those decisions are made allows us to incorporate community feedback as a critical step.
1. **Intentionality:**
1. **Discoverability:**

### What constitutes an architecture decision?

Almost every aspect of managing an organization and developing software involves making choices. How do we decide (no pun intended) when a particular choice rises to the level of an architecture decision and requires an ADR?

>An Architectural Decision (AD) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant.
>
>Source: [ADR GitHub Organization](adr)

We adopt and extend the definition Another way to recognize when making a decision related to this project constitutes an architecture decision is to ask yourself three questions about that decision:

1. Does this decision affect the structure, direction, or scope of our platform or organization?
1. Would someone unfamiliar with the history our platform or organization ask us to explain why we made this decision?
1. Were there other viable alternatives we could have chosen instead?

Whenever we answer "Yes" to at least one of these questions, there's a good chance we've just made an architectural decision, and we aim to create an ADR to explain why we've made that choice.

### Examples of architecture decisions

While architecture decisions come in all shapes and sizes, some common examples include:

- Selecting a critical library, tool, or platform
- Adopting a certain analytical framework or algorithm
- Choosing _not_ to build a particular feature
- Adopting or adjusting a pricing model for our platform
- Changing part of our governance structure

## ADR Process

TODO: Create an ADR for proposing, approving, and accepting an ADR.

## Acknowledgements and Further Reading

- [ADR GitHub Organization](adr)
- [Joel Parker Henderson's ADR repo](joel)
- [GitHub Blog - Why Write ADRs](github)

[adr]: https://adr.github.io/
[joel]: https://github.com/joelparkerhenderson/architecture-decision-record#what-is-an-architecture-decision-record
[github]: https://github.blog/2020-08-13-why-write-adrs/
