# Governance

## Purpose

This document describes how OpenGameBuilder is governed: who has authority, how decisions are made, how responsibility is assigned, and how that structure can change.

OpenGameBuilder is a community open-source preservation, reimplementation, and extension of MyGameBuilder.com. Governance exists to keep the project coherent, sustainable, and accountable while leaving room for the community to grow.

OpenGameBuilder is not an official continuation of MyGameBuilder.com.

## Governance Model

OpenGameBuilder uses a **BDFL-style governance model**.

The project founder is the **Benevolent Dictator For Life**, or **BDFL**. The BDFL has final authority over project direction, repository administration, releases, maintainer access, governance, and interpretation of the project's goals.

The phrase is traditional open-source shorthand, not a claim of ownership over the community. In an open-source project, authority depends on trust. Contributors participate because they believe the project is worth their time, and they remain free to leave, disagree, or fork the project if it stops serving its purpose well.

The :benevolent" part matters. The BDFL is expected to act as a steward of the project: listening seriously, explaining important decisions, accepting criticism, delegating responsibility where appropriate, and using final authority to protect the long-term health of the project rather than personal preference.

OpenGameBuilder prefers open discussion, rough consensus, and trusted delegation. The BDFL role exists to resolve deadlocks, preserve coherence, and keep the project aligned with its preservation, reimplementation, and extension goals.

This model reflects the current stage of the project. If OpenGameBuilder grows into a larger community with multiple long-term maintainers, this governance model may evolve into a maintainer council, steering group, or other shared governance structure.

## Project Principles

OpenGameBuilder decisions should be guided by these principles:

- **Preservation:** protect the history, games, tools, and community memory of MyGameBuilder.
- **Continuity:** preserve the spirit of MyGameBuilder while allowing OpenGameBuilder to grow beyond the original site.
- **Respect:** treat the original site, developers, moderators, users, and creators with care, even when discussing limitations or historical problems.
- **Openness:** welcome contributors who participate in good faith, whether or not they were part of the original MyGameBuilder community.
- **Stewardship:** handle archived material thoughtfully, balancing preservation, privacy, creator agency, historical value, and project sustainability.
- **Maintainability:** prefer decisions that keep the codebase, infrastructure, and community manageable over time.

## Roles

### Community Members

Community members are people who participate in OpenGameBuilder spaces in good faith.

### Contributors

Contributors are people who contribute useful work to the project. Contributions may include code, documentation, testing, design, issue reports, archival research, historical knowledge, moderation help, or community support.

A contribution does not need to be code to matter.

### Reviewers

Reviewers are trusted contributors who help review issues, pull requests, documentation, designs, or proposals.

Reviewers may not have merge access. Their role is to help improve project quality and support contributors.

### Maintainers

Maintainers are trusted contributors with responsibility for one or more parts of the project.

Maintainers may review and merge pull requests, triage issues, manage releases, maintain documentation, administer infrastructure, moderate community spaces, or help guide project direction.

Maintainer access is granted based on trust, judgment, sustained constructive participation, and project need.

### Moderators

Moderators are trusted community members responsible for helping maintain healthy project spaces and enforce the Code of Conduct.

Moderators may or may not also be maintainers. Moderation responsibility does not require code contribution or repository access.

### BDFL

The BDFL is the project founder and lead maintainer.

The BDFL may delegate authority to maintainers, moderators, reviewers, or other trusted contributors. Delegated authority can be adjusted as project needs change.

## Decision Making

OpenGameBuilder prefers **rough consensus**.

Rough consensus means concerns are heard and considered, but unanimous agreement is not required. A decision can move forward when the relevant maintainers and the BDFL believe the project has had a fair chance to discuss it and remaining objections have been reasonably addressed.

OpenGameBuilder does not use formal votes for normal project decisions. Polls may be used to understand preferences, but they are not binding unless explicitly stated.

If consensus cannot be reached, the BDFL makes the final decision.

### Routine Decisions

Routine decisions include small bug fixes, documentation updates, minor refactors, dependency updates, tests, issue triage, and ordinary maintenance work.

These may be handled through the normal issue and pull request process by maintainers.

### Significant Decisions

Significant decisions should usually be discussed publicly before implementation.

Examples include:

- major architectural changes;
- public API or data format changes;
- release process changes;
- project branding changes;
- licensing changes;
- archival policy changes;
- compatibility commitments;
- governance or Code of Conduct changes;
- changes that materially affect how archived MyGameBuilder games are restored, presented, or made playable.

Significant decisions should leave a durable written record where practical, such as an issue, discussion, pull request, architecture decision record, or documentation update.

### Urgent Decisions

Some decisions may need to be made quickly, especially around security, privacy, harmful content, production incidents, legal risk, or Code of Conduct enforcement.

In urgent situations, the BDFL, maintainers, or moderators may act immediately. When possible, the decision should be explained afterward in a way that respects safety, privacy, and confidentiality.

## Maintainer Selection

Maintainers are invited by the BDFL, usually after sustained constructive participation.

Maintainer selection may consider:

- quality and consistency of contributions;
- judgment and communication;
- understanding of the project's goals;
- respect for the original MyGameBuilder site and community;
- ability to work constructively with others;
- care when handling archival material;
- reliability with project permissions and responsibilities.

Maintainer status is not based only on code contributions.

## Maintainer Inactivity and Removal

Maintainers may step back voluntarily at any time.

Maintainers who are inactive for an extended period may have permissions reduced or be moved to inactive or emeritus status. This is not a punishment; it helps keep project access accurate and secure.

Maintainer access may also be removed for security reasons, loss of trust, misuse of permissions, repeated failure to follow project expectations, or Code of Conduct violations.

The BDFL has final authority over maintainer access.

## Repository and Organization Access

Repository and organization access is granted based on trust, project need, and the principle of least privilege.

Where practical, OpenGameBuilder should use protected branches, required reviews, required status checks, and automation to reduce the risk of accidental or unauthorized changes.

Administrative access should be limited to people who need it.

## Archive Stewardship

OpenGameBuilder includes preservation work related to MyGameBuilder games and historical material.

Archive-related decisions should balance preservation, privacy, creator agency, historical value, technical feasibility, safety, and long-term project sustainability.

The existence of archived material does not automatically mean every item should be public, searchable, or restored without context. Requests from original creators or affected people about attribution, privacy, or removal should be considered seriously.

The BDFL has final authority over archive stewardship decisions, but significant archival policy changes should be discussed publicly when practical.

## Code of Conduct and Moderation

OpenGameBuilder's community standards are defined in [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).

Code of Conduct enforcement is handled by the BDFL and any designated moderators. Reporting details and enforcement procedures belong in the Code of Conduct, not this document.

If a report involves someone with enforcement authority, that person should not handle the report alone when another trusted moderator or maintainer is available.

## Conflicts of Interest

People making project decisions should avoid acting where they have a serious conflict of interest.

A conflict of interest may include decisions involving close personal relationships, direct personal disputes, reports about oneself, or situations where a person cannot reasonably act in the best interest of the project.

When practical, people with a conflict should step back and allow another trusted person to handle the decision.

## Project Continuity

The BDFL may designate trusted maintainers to act on their behalf for specific areas of the project or during periods of absence.

If the BDFL becomes unavailable for an extended period without a designated successor or delegate, active maintainers should coordinate to preserve project continuity and document any temporary governance arrangement.

## Changes to Governance

Small clarifications to this document may be made through the normal pull request process.

Significant governance changes should be discussed publicly before being adopted.

While OpenGameBuilder uses a BDFL-style governance model, final approval of governance changes rests with the BDFL.
