# [Draft - Please do not circulate] The Loft Manifesto

*This document is expected to change substantially before it
becomes public. To avoid forming public opinion about the project
based on incomplete ideas, please do not share the document or the
concepts outlined here.*

## What?

Loft is:
- an open source, peer-reviewed index of Swift libraries.
- a community of developers and users evolving:
  - individual libraries
  - the Swift library ecosystem
  - best practices for Swift programming.
- an incubation area for libraries targeted at Loft.

## Why?

- The success of any programming language ultimately depends on
  building a vibrant ecosystem of high-quality libraries.
- Swift doesn't yet have one.
- A vibrant library ecosystem is supported by maintaining a degree of
  consistency.
- The best libraries are not simply inventions of their authors, but a 
  product of evolution over time based on feedback from their actual and
  prospective users. 
- Evolution implies *some* degree of instability.
- Library design is an art that flourishes through a shared culture
  of understanding and discovery of design principles and techniques.
- Swift needs a home where that culture can flourish and produce real,
  widely-used, evolving libraries.

## Where?

- [Website](http://loftware.org)
- [GitHub org](http://github.com/loftware)
- [Incubation Area](http://github.com/loft-nest)
- Loft forums (TODO: create these) and join our 
- [Discord server](https://discord.gg/2AkrfW) 

## Community

- Need code of conduct
- Need home for discussions (MLs, forums, etc.)

## Peer Review

- Baseline [Boost](http://boost.org) model, which was mostly adopted by
  the Swift evolution process.  
- Acceptance of new libraries into the index is entirely up to the review
  manager (no core team rulings).
- In making a determination, the review manager should try to reflect the
  consensus of the most thoughtful reviews.
- Investigate [what Rust
  does](https://forums.swift.org/t/evolution-process-discussion/33272/26).

## Ownership

Original authors and their designated maintainers maintain full control
over the evolution of their libraries, without required review, once
accepted into the Loft index. Reviews are encouraged for substantial
source breaking changes.

## Stability

- There is no Loft policy mandating ABI stability.
- There is no Loft policy mandating API stability, but a high degree
  of API stability with only conscientious exceptions is strongly
  encouraged.
- Any library maintainer is free to promise full API, or even ABI,
  stability to their clients.
- Loft libraries follow [semantic versioning](https://semver.org/) conventions.

## Infrastructure/Systems

- Infrastructure development and maintenance can be a major drag on an
  open-source organization's viability.
- GitHub's services are:
  - free for open-source projects.
  - mostly excellent.
  - well-known and understood.
  - well-documented.
  - used successfully to support many important projects.
- Therefore, the Loft makes maximal use of GitHub's facilities and loft
  libraries are strongly encouraged to do the same.
- Opening an issue tracker to arbitrary non-actionable bug reports can create an
  untenable time sink for an open-source maintainer.  Therefore, exposing an
  issue tracker for a project is not required as long as the project accepts
  PRs.

## Seed Libraries

We should launch with some packages already in the collection.  Some ideas:

- John Sundell's “Files” package.
- Other packages by Sundell
- A package that provides the ability to [XCTest things that
  FatalError](https://medium.com/@marcosantadev/how-to-test-fatalerror-in-swift-e1be9ff11a29).

## Anticipated Problems

SwiftPM doesn't work on Windows, and IIUC the team has so far been unwilling to
accept patches to support it working on Windows.

## License

Like Swift itself, all Loft Libraries are Apache 2.0 licensed.
