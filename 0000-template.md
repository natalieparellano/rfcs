# Meta
[meta]: #meta
- Name: GitHub discussions as RFC nursery
- Start Date: 3/17/2021
- Author(s): natalieparellano
- RFC Pull Request: (leave blank)
- CNB Pull Request: (leave blank)
- CNB Issue: (leave blank)
- Supersedes: N/A

# Summary
[summary]: #summary

The RFC process is central to how substantial changes are formalized within the CNB project. But the effort required to write an RFC and shepherd it through to completion could be prohibitive for some members of the community who may still wish to contribute their ideas. This RFC proposes using GitHub Discussions as a place to incubate RFC ideas until an RFC is proposed.

# Definitions
[definitions]: #definitions

RFC: Request for Comments. Described in https://github.com/buildpacks/rfcs

GitHub Discussions: discussion forum attached to a GitHub repository (see https://docs.github.com/en/discussions/quickstart and for buildpacks: https://github.com/buildpacks/community/discussions)

# Motivation
[motivation]: #motivation

- Why should we do this? Make it easier for community to contribute ideas
- What use cases does it support? Larger more nebulous topics that could benefit from diverse input prior to formalization
- What is the expected outcome? It's easier to write RFCs because they've already been "workshopped" by the community

# How it Works
[how-it-works]: #how-it-works

We could create a discussion thread per topic. An example might be "RFC idea: Test API". If someone starts an RFC on this topic the discussion thread could be locked and all conversation directed to the RFC.

# Drawbacks
[drawbacks]: #drawbacks

Why should we *not* do this? Having multiple places where conversation is happening could be confusing. It might dissuade people from writing RFCs if they can just leave a comment on a discussion thread instead.

# Alternatives
[alternatives]: #alternatives

- What other designs have been considered?

  - Leave things the way they are
  - Use GitHub issues on the RFC repo instead of GitHub discussions on community repo
    - Pro: more discoverable for people who arrive directly at RFC repo
    - Con: less discoverable for people who arrive directly at community repo
    - Mitigation: make an issue per topic on RFC repo that points to a discussion thread?
  - Make a "skeleton" RFC per topic and have people comment there instead
    - Pro: more consistent with the existing process
    - Con: potentially more cumbersome for participants
    - Con: still requires someone to undertake the effort to create and update the RFC
  - Modify the existing process
    - Could it be made less rigid somehow? Could we have different "tiers" of RFCs (expressing desired outcome vs. design, etc.)? Could more parts of the RFC template be made optional?

- Why is this proposal the best?

  - Not actually sure it's the best. But putting it out there...

# Prior Art
[prior-art]: #prior-art

Discuss prior art, both the good and bad.

  - https://github.com/concourse/rfcs/discussions - using GitHub discussions
  - https://github.com/rust-lang/rfcs#before-creating-an-rfc - using various discussion forums
  - https://github.com/moby/buildkit/issues?q=is%3Aissue+is%3Aopen+rfc - using GitHub issues
  - https://github.com/golang/proposal#the-proposal-process - differentiating proposal from design
