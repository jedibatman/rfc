# Topgolf Labs Request For Comments (RFC)

A repository that serves as a codex of all decisions made that impact the Topgolf Labs organization. The current scope of those decisions is arbitrarily defined as:
  - Meta -- decisions that impact a process, the governance of the identity of Topgolf Labs.
  - Idea -- decisions that result in the seeding of a new project. Alternatively it can be an idea that represents a significant change to one (or more) existing projects.

## What Is The Process

TL;DR; To either suggest a new project / idea or evolve a process, the governance, or the identity of Topgolf Labs one must first get a RFC merged into this repository as a markdown file. At that point, the RFC is considered accepted and may be implemented with the goal of eventual inclusion of the outputs from said RFC (the resulting decision and consequences as outlined by the RFC in question).
  - Fork the RFC repository.
  - Copy `0000-template.md` to either `idea/0000-my-idea.md` *or* `meta/0000-my-idea.md` (where "my-idea" is concise and descriptive) based on whether the idea should be categorized as **meta** or **idea** based on the criteria outlined above. Don't assign an RFC number at this stage.
  - Fill in the fields of the RFC. It is advised to be thoughtful and take time to invest in articulating the idea in such a way that leaves little ambiguity. RFCs that cannot illustrate clear and convincing motivations, are lacking in conceptual integrity / completeness, or are misleading in the resulting consequences will have difficulty in garnering support and subsequent adoption.
  - Submit a pull request. At this stage, the idea will receive feedback from the community. The author is expected to be prepared to revise the request in response to the community feedback.
  - For the interim, the benevolent dictator of Topgolf Labs (jedibatman) will take on the responsibility of assigning labels and/or creating repos and issues as is appropriate until another process materializes to replace it.
  - Work to build consensus among the community and integrate feedback. RFCs that have overwhelming support will have a better chance of making progress than others that don't.
  - At some point, a member of the core team will propose to enter a *final comment period* (FCP), along with a *disposition* for the RFC (merge, close, or postpone).
     - This stage is entered when enough of the *decision space* is explored through discussion that the core team is positioned to be able to make a decision. This does not required consensus amongst all participants given that it is generally impossible. The argument in support of the disposition *does* need to be clearly articulated, however, and there should not be a strong consensus against the position among the core team. The core team members are expected to use their best judgement during this period, and the FCP is intended to allow enough time and information to push back if the decision is made too early.
     - Before entering the FCP, all members of the core team must actually review in entirety the request.
  - The FCP will last 10 calendar days, which provides at minimum 5 business days.
  - After the FCP has ended, the RFC will usually be merged or closed. In rare cases, the FCP may be cancelled at which point the RFC will go back into a development stage wherein the RFC can be further cultivated.
