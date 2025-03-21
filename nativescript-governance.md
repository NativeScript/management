# Governance

NativeScript is an open source project that depends on contributions from the community. Anyone may contribute to the project at any time by submitting code, [participating in discussions](https://github.com/orgs/NativeScript/discussions), making suggestions, or any other contribution they see fit. This document describes how various types of contributors work within the NativeScript project.

## Roles and Responsibilities

### Users

Users are community members who have a need for the project. Anyone can be a User; there are no special requirements. Common User contributions include evangelizing the project (e.g., display a link on a website and raise awareness through word-of-mouth), informing developers of strengths and weaknesses from a new user perspective, or providing moral support (a "thank you" goes a long way).

Users who continue to engage with the project and its community will often become more and more involved. Such Users may find themselves becoming Contributors, as described in the next section.

### Contributors

Contributors are community members who contribute in concrete ways to the project, most often in the form of code and/or documentation. Anyone can become a Contributor, and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements, and no selection process.

Contributors have read-only access to source code and so submit changes via pull requests. Contributor pull requests have their contribution reviewed and merged by a TSC member. TSC members and Committers work with Contributors to review their code and prepare it for merging.

As Contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. At some stage, they may find themselves being nominated for committership by an existing Committer.

### Committers

Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committers are given push access to the project's GitHub repos and must abide by the project's [Contribution Guidelines](https://github.com/NativeScript/NativeScript/blob/main/tools/notes/CONTRIBUTING.md).

Committers:

* Are expected to work on public branches of the source repository and submit pull requests from that branch to the master branch.
* Are expected to delete their public branches when they are no longer necessary.
* Must submit pull requests for all changes.
* Have their work reviewed by TSC members before acceptance into the repository.
* May label and close issues.
* May merge some pull requests.

To become a Committer:

* One must have shown a willingness and ability to participate in the project as a team player. Typically, a potential Committer will need to show that they have an understanding of and alignment with the project, its objectives, and its strategy.
* Committers are expected to be respectful of every community member and to work collaboratively in the spirit of inclusion.
* Have submitted a minimum of 10 qualifying pull requests. What's a qualifying pull request? One that carries significant technical weight and requires little effort to accept because it's well documented and tested.

New Committers can be nominated by any existing Committer. Once they have been nominated, there will be a vote by the TSC members.

It is important to recognize that committership is a privilege, not a right. That privilege must be earned and once earned it can be removed by the TSC members by a standard TSC motion. However, under normal circumstances committership exists for as long as the Committer wishes to continue engaging with the project.

A Committer who shows an above-average level of contribution to the project, particularly with respect to its strategic direction and long-term health, may be nominated to become a reviewer, described below.

#### Process for Adding Committers

1. Send email congratulating the new committer and confirming that they would like to accept. This should also outline the responsibilities of a committer with a link to the maintainer guide.
1. Add the GitHub user to the "committers" team
1. Invite to Discord team channel
1. Tweet congratulations to the new committer from the NativeScript Twitter account

### Reviewers

Reviewers are community members who have contributed a significant amount of time to the project through triaging of issues, fixing bugs, implementing enhancements/features, and are trusted community leaders.

Reviewers may perform all of the duties of Committers, and also:

* May merge external pull requests for accepted issues upon reviewing and approving the changes.
* May merge their own pull requests once they have collected the feedback they deem necessary. (No pull request should be merged without at least one Committer/Reviewer/TSC member comment stating they've looked at the code.)

To become a Reviewer:

* Work in a helpful and collaborative way with the community.
* Have given good feedback on others' submissions and displayed an overall understanding of the code quality standards for the project.
* Commit to being a part of the community for the long-term.
* Have submitted a minimum of 25 qualifying pull requests.

A Committer is invited to become a Reviewer by existing Reviewers and TSC members. A nomination will result in discussion and then a decision by the TSC.

#### Process for Adding Reviewers

1. Add the GitHub user to the "reviewers" GitHub team
1. Tweet congratulations to the new Reviewer from the NativeScript Twitter account

### Technical Steering Committee (TSC)

The NativeScript project is jointly governed by a Technical Steering Committee (TSC) which is responsible for high-level guidance of the project.

The TSC has final authority over this project including:

* Technical direction
* Project governance and process (including this policy)
* Contribution policy
* GitHub repository hosting

TSC seats are not time-limited. The size of the TSC can not be larger than twenty-one members. This size ensures adequate coverage of important areas of expertise balanced with the ability to make decisions efficiently.

The TSC may add additional members to the TSC by a standard TSC motion.

A TSC member may be removed from the TSC by voluntary resignation, by a standard TSC motion, or by attending less than 3 TSC meetings annually. In all cases, the TSC member will revert to Reviewer status unless they prefer Alumni status.

Changes to TSC membership should be posted in the agenda, and may be suggested as any other agenda item (see "TSC Meetings" below).

TSC members have additional responsibilities over and above those of a Reviewer. These responsibilities ensure the smooth running of the project. TSC members are expected to review code contributions, approve changes to this document, manage the copyrights within the project outputs, and attend regular TSC meetings.

TSC members may perform all of the duties of Reviewers, and also:

* May release new versions of all NativeScript projects.
* May participate in TSC meetings.
* May propose budget items.
* May propose new NativeScript projects.

There is no specific set of requirements or qualifications for TSC members beyond those that are expected of Reviewers.

A Reviewer is invited to become a TSC member by existing TSC members. A nomination will result in discussion and then a decision by the TSC.

#### Process for Adding TSC Members

1. Add the GitHub user to the "core" GitHub team
1. Set the GitHub user to be have the "Maintainer" role for the NativeScript organization
1. Send a welcome email
1. Tweet congratulations to the new TSC member from the NativeScript Twitter account

#### TSC Meetings

The TSC meets every month via Zoom on Thursday at 1 pm PDT. The meeting is run by a designated moderator approved by the TSC. TSC members are not required to attend every single TSC Meeting, only that they attend at least 8 a year to maintain status.

Items are added to the TSC agenda which are considered contentious or
are modifications of governance, contribution policy, TSC membership,
or release process.

The intention of the agenda is not to approve or review all patches.
That should happen continuously on GitHub and be handled by the larger
group of Committers.

Any community member, Committer, or Reviewer can ask that something be added to
the next meeting's agenda by logging a GitHub Issue. Anyone can add the item to the agenda by adding the "tsc agenda" tag to the issue.

Prior to each TSC meeting, the moderator will share the Agenda with
members of the TSC. TSC members can add any items they like to the
agenda at the beginning of each meeting. The moderator and the TSC
cannot veto or remove items.

No binding votes on TSC agenda items can take place without a quorum of
TSC members present in the meeting. Quorum is achieved when more than
half of the TSC members (minus non-attending members) are present.

The TSC may invite persons or representatives from certain projects to
participate in a non-voting capacity.

The moderator is responsible for summarizing the discussion of each
agenda item and sending it as a pull request after the meeting.

## Consensus Seeking Process

The TSC follows a
[Consensus Seeking](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making)
decision making model.

When an agenda item has appeared to reach a consensus, the moderator
will ask "Does anyone object?" as a final call for dissent from the
consensus.

If an agenda item cannot reach a consensus, a TSC member can call for
either a closing vote or a vote to table the issue to the next
meeting. The call for a vote must be approved by a majority of the TSC
or else the discussion will continue. Simple majority wins.

----

This work is a derivative of [YUI Contributor Model](https://github.com/yui/yui3/wiki/Contributor-Model) and the [Node.js Project Governance Model](https://github.com/nodejs/node/blob/master/GOVERNANCE.md).

This work is licensed under a [Creative Commons Attribution-ShareAlike 2.0 UK: England & Wales License](https://creativecommons.org/licenses/by-sa/2.0/uk/).

latest updated 2020-08-04
