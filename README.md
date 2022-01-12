# Ada User Community Input

## What is Ada User Community Input?

The Ada User Community Input is a clearly defined **process** supported by appropriate infrastructure to facilitate Ada users from the community at-large to identify existing issues with the Ada Reference Manual, or to advocate new features for consideration by the ARG for possible inclusion to future revisions of the Ada language.

The UCI process defines a way for interested users to explore ideas, propose working groups, and collaborate on concrete language proposals that the ARG can formally deliberate on.

## Is this repository the official home of UCI?

Not exactly. This repository is only the community facing portion that tracks stage progression and handles community input for Stages I and II-final.

The Ada UCI process is developed and maintained by a dedicated ARG working group that aims to design a process that is platform independent and transparent.

An alternate interface for those not familiar with github is also available at (link), where issues can be submitted directly, and working groups can be proposed.

Additionally, a set of Google Docs mirror the issues and working groups seen (here).

## What is the Ada UCI Process?

The Ada UCI process applies to any given language change proposal that evolves through a three stage process.

---
### Stage I

All proposed change and ideas begin in Stage I. The idea is to make the proposal of languages changes and new features as easy as possible, with the lowest possible barrier. Stage I is about presenting ideas, seeking clarification (potentially interpretation), and discussing the merits and/or issues with those ideas among the community.

Valid proposals to Stage I are really any coherent idea for a change or new feature. This can be as small as a few sentences. The goal of Stage I is to have open debate and discussion about the proposal, and is not about developing a specific, formal proposal.

Discussions of Stage I are open to all participants, and the discussion will remain visible to anyone.

Moderators will monitor new issues for issues that have already been proposed at an earlier time, are in a working group, or have already been considered by the ARG. In such cases, moderators will make a reference to the relevant issue/WG/AI in the discussion. Moderators may also assign an appropriate tag such as _Duplicate_, _In WG_ or _ARG Concluded_

**Instructions**

To propose a language change, bug fix, or new capability, simply create a standard issue on this repository.

The title should give a concise description as possible.

The issue should be given one of the following tags:
* **Comment**: Issues/observations that the user does not necessarily have a proposal for. Comments generally will not progress to Stage II.
* **Question**: A request for clarification or interpretation of an aspect of Ada or the Ada Reference Manual. If a binding interpretation becomes a goal, Questions may propose to an abbreviated Stage II for consideration by the ARG.
* **Bug Report**: An issue with the current Ada Reference Manual
* **Feature Request**: A proposal for a new language feature or capability (feature request)

Finally, a description should informally describe the comment, question, bug, or feature, including a very generalized (high-level) 

Alternatively, those not familiar with Github issues may use the (web form). Submissions to the webform will be synchronized as new issues in this repository (and vice-versa).

---
### Stage II

If a some number of members may coordinate with each other and propose to form a **working group** to formalize the proposal.

The Working Group takes on the issue stated in the proposal, and works towards the completion of a formal AI for consideration by the ARG.

Working groups are responsible for coordinating amongst themselves to develop a a formal proposal (AI) for consideration by the ARG.

**Instructions**

When forming the working group, a shared Google Drive folder must be created that contains all working materials of the working group. This folder must be publicly readable, and the link to that folder must be provided in the working group proposal. The working group can organize the content of this folder as they see fit.

The working group proposal is put forward by creating a pull request for the addition of a *Stage II working group proposal* to the 'Active Working Groups' subdirectory of this repository, following the [Active Working Group Template](https://github.com/).

Alternatively, working groups can use the (webform) to make a request to form a working group.



The proposal should follow the official template (here) and should be submitted by the working group as a pull request to the 'Final Proposals' subdirectory.

This pull request will then be open to the community to make comments on. Depending on the comments, the working group may need to add commits to their pull requests to refine their proposal.


---
### Stage III

Once a Stage II proposal has been accepted and merged via the pull request described in Stage II, it will then be available for review and selection by the ARG.

The ARG may request that the working group clarify or modify parts of their final proposal, at which point the proposal regresses to Stage II, and the working group must submit a pull request for updates to the Final Proposal.
