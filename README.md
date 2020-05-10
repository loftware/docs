# [Draft - Please do not circulate] The Loft Manifesto

*This document is expected to change substantially before it
becomes public. To avoid forming public opinion about the project
based on incomplete ideas, please do not share the document or the
concepts outlined here.*

## What?

Loft is:
- an open source, peer-reviewed index of Swift libraries.
- a community of developers and users evolving these
  libraries, and library development in general.

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
- Investigate [what Rust does](https://forums.swift.org/t/evolution-process-discussion/33272/26).

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

## License

Like Swift itself, all Loft Libraries are Apache 2.0 licensed.
