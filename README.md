**Development of the Scivision library itself is in the [scivision repository](https://github.com/alan-turing-institute/scivision). If you are new to the project, start there.**

# Scivision RFCs

This repository collects RFCs for Scivision.  An RFC, or *Request For Comments*, is a document describing a proposed standard that the project should adopt.  An RFC could describe:
  - software architecture
  - an interface or API that the software exposes
  - a file format
  - a process or way of working together.

An RFC has an *editor*, who is normally the proposor, and is responsible for gathering feedback and revising the text before it is adopted.

RFCs that have been adopted (whose *status* is 'stable') complement the project documentation, where relevant RFCs can be linked and referenced.

## When should an RFC be used?

Consider making an RFC if: you would like to propose changes that affect the overall design of the library, introduce or change an interface, and in any situation where **early feedback from the community** on an idea would be helpful.

They are not necessary for every change: For smaller, or self-contained contributions, simply open a pull request to the relevant repository (e.g. [scivision](https://github.com/alan-turing-institute/scivision)). This type of change can be made and discussed on the pull request directly.

## Who can make an RFC?

**Any scivision contributor** can propose an RFC by making a pull request to this repository, following the steps below. See also the [contributing guide](https://github.com/alan-turing-institute/scivision/blob/main/contributing.md) for advice about contributing to the project generally.

## The RFC process

We use the [Consensus Oriented Specification System](https://rfc.unprotocols.org/2/) to manage the lifecycle of an RFC.

In summary, the steps to follow, from proposal to adoption, are listed below. Feel free to ask on the [discussions board](https://github.com/alan-turing-institute/scivision/discussions) if you need any help with any part of this process.

 1. Fork/clone this repository
 2. Copy the [template RFC]() to a file in [docs/rfcs](./docs/rfc) (using the next available numbered filename)
 3. Add your GitHub username to the `editor` field (or the username of whoever has agreed to be the editor)
 4. Give it a short, descriptive title, and optionally add any draft text to the relevant sections of the document
 5. Open a pull request into this repository
    - Normally this can be merged immediately, even if the text is incomplete or an early draft - ask a [maintainer]() if you do not have sufficient access rights to merge it yourself
 7. While the status of the RFC is `raw` or `draft`, the text can be modified in any way, with the process managed by the editor (normally the proposor)
 8. Consider [discussing](https://github.com/alan-turing-institute/scivision/discussions) the proposal with the community, and requesting feedback or edits from  others as pull requests into this repository
 9. When it is ready for work to begin on an implementation, change (via pull request) the status to `draft`
 10. Once there is broad agreement that it should be adopted (and a working implementation, for code changes), change the status to `stable`.
     - Substantial edits should not be made to RFCs whose status is `stable`.  Instead, create a new one as a replacement (using this process), perhaps copying and modifying any relevant text, and eventually deprecating/retiring the original.









