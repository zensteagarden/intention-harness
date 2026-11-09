# The Intention Harness

**Created by John Patrick Daly.**

The Intention Harness proposes an external support architecture for technical work when working memory, executive function, or cognitive stamina is limited.

It combines **Listen → Mirror → Confirm → Guard → Execute** with an **Evidence Ratchet**: persistent records of verified milestones that help a person resume work after interruptions or errors.

## Read the paper

The formal manuscript is in the [`paper/`](paper/) directory.

## Architecture

- **Listen:** Capture the person's intended outcome.
- **Mirror:** Reflect that intention back in clear language.
- **Confirm:** Let the person confirm the intended outcome before proceeding.
- **Guard:** Check constraints and risks before execution.
- **Execute:** Carry out the agreed work within those constraints.
- **Evidence Ratchet:** Preserve records of verified milestones so progress can be inspected and work can resume.

A recorded milestone documents what was verified at that time. It does not guarantee that external systems or conditions remain unchanged.

## Status and evidence

This repository publishes the architecture and manuscript for review and collaboration. It does not claim clinical validation or proven enterprise reliability.

John Patrick Daly reports testing core components through an AWS serverless API qualification proof of concept using AWS Bedrock in `us-east-2`. This is an author-reported technical implementation claim, not an independently verified result presented by this repository. Controlled studies of cognitive or functional outcomes remain future work.

Related public work is available in [Noticer](https://github.com/zensteagarden/noticer-open), including intention guidance, a Success Contract, an offline verifier, and synthetic examples. That implementation has a narrower disclosed scope and should not be treated as validation of the full Intention Harness.

## Work with me

I'm John Patrick Daly. I created The Intention Harness and I'm looking to work with teams interested in developing and testing it.

Use this repository's [Discussions](https://github.com/zensteagarden/intention-harness/discussions) for collaboration inquiries and design conversations, or [Issues](https://github.com/zensteagarden/intention-harness/issues) for concrete questions and proposed improvements. Please do not post private or confidential information.

Find me on [X / Twitter: @deloosio](https://x.com/deloosio) or [GitHub](https://github.com/zensteagarden).

## Attribution and citation

Please credit **John Patrick Daly** and link to this repository when discussing or building on this work. See `CITATION.cff` for citation metadata. This publication records the work under the author's name; it does not establish an independently verified claim of first invention or novelty.

## License

Copyright 2026 John Patrick Daly.

The manuscript and original materials in this repository are licensed under the **Apache License, Version 2.0**. See `LICENSE` and `NOTICE`. Linked external projects retain their own licenses.

No deployment credentials, customer data, or private service source are included.
