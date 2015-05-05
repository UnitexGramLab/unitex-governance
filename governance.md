## Unitex/GramLab Governance Model

> This document is a draft for discussion and still a work in progress. To contribute, please submit a [pull request](https://github.com/UnitexGramLab/governance/pulls). Major changes will be discussed in the comment section.

> The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in the [RFC 2119][RFC2119] 

### Overview

[Unitex/GramLab][unitex] is an open source, cross-platform, multilingual, lexicon- and grammar-based corpus processing suite. Project decision-making is based on a community meritocratic process, anyone with an interest in the project can join the community, contribute to the project design and participate in decisions. This document describes how that participation takes place and how to set about earning merit within the project community.

### Project Management Infrastructure

| Name                    | Link                             |
| ----------------------- | -------------------------------- |
| main website            | http://unitexgramlab.org         |
| users forum             | http://forum.unitexgramlab.org   |
| developers mailing list | unitex-devel@univ-mlv.fr         |
| code hosting            | https://github.com/UnitexGramLab |

### Getting support

All participants in the Unitex/GramLab community are encouraged to provide support for new users within the project management infrastructure. This support is provided as a way of growing the community. Those seeking support should recognise that all support activity within the project is voluntary and is therefore provided as and when time allows. A user requiring guaranteed response times or results should therefore seek to purchase a support contract from a community member. However, for those willing to engage with the project on its own terms, and willing to help support other users, the community support channels, as the [developer mailing list][devel] or the [users forum][forum], are ideal.

### Roles And Responsibilities

Unitex/GramLab development is based on user consensus and open discussion between users. In order to have a smoothly running project, formal roles with corresponding responsibilities are established. A member of the community may have multiple roles.

#### Unitex/GramLab Users

Unitex/GramLab users are community members who have a need for the project, they are the most important members of the community: through their usage, they give the project a purpose. Users should be encouraged to participate in the life of the project and the community as much as possible. User contributions enable the project team to ensure that they are satisfying the needs of those users. Common user activities include, but are not limited to:

* Evangelising about the project.
* Informing developers of strengths and weaknesses from a new user perspective both through the [Unitex/GramLab forum][forum] or following the [Bug Reporting Guide][bugs].
* Identifying needs and filing feature requests.
* Participating on the [users forum][forum].
* Providing moral support, a 'thank you' goes a long way.

###### Become a Unitex/GramLab User

Anyone can be a user; there are no special requirements. Users who continue to engage with the project and its community will often become more and more involved. Such users may find themselves becoming Unitex/GramLab Contributors, as described in the next section.

#### Unitex/GramLab Contributors

Unitex/GramLab Contributors are community members who contribute in concrete ways to the project. Contribution may be a one time participation or occur over time. Contribution can take place in many specific ways:

##### Linguistic Resources Contributors
[LR-contributor]

* Contributing new linguistic resources and helping maintain existing ones.

###### Become a Linguistic Resources Contributor

##### Coding Contributors
[DEV-Contributor]

* Adding features.
* Submitting patches to fix bugs or add features.
* Identifying requirements.
* Assisting with project infrastructure.

###### Become a Coding Contributor

The [documentation for developers](https://github.com//UnitexGramLab/unitex-doc-devel) is a good place to start getting familiar with the coding style and documentation guidelines. Coding Contributors engage with the project through the issue tracker and the [developer mailing list][devel], or by writing or editing documentation. We invite contributors to share their feature development and patch idea through the [developer mailing list][devel] or the [users forum][forum]. It is recommended to start with small patches and share your code early so the existing committers (see next section) can provide feedback and guidance.

##### Non-Coding Contributors

[Non-code contributions](https://modelviewculture.com/pieces/non-coding-contributors-in-open-source) ([Contributor]) are incredibly valuable and very welcome,  Here are some examples of simple ways to contribute:

* Writing and maintaining the documentation (e.g. [tutorials][tutorials])
* Participate in the community's activities.

###### Become a Non-Coding Contributor

#### Unitex/GramLab Commiters

Unitex/GramLab Committers are contributors who have shown dedication to the project, i.e. providing valuable contribution over a period of time, have a deep understanding of the code base and project strategy and work well with contributors and users. Committers have no more authorities than contributors, and they should engage with the community through the [developer mailing list][devel] or the [users forum][forum] regarding their intention. However committers have earn enough trust from the community to have direct access to the project code base without having to submit pull request. Committers seeks approval after the contribution is made, rather than before. Therefor committers

* Help contributors via the [developer mailing list][devel].
* Merge pull request submit by contributors.
* Have direct access to the code base.
* Nominate and vote new committers.
* Participate in the release planning.

###### Become a Commiter

You need to start being a Unitex/GramLab Contributor and be then be nominated as a committer. Unitex/GramLab select and elect new committers using the [Apache model][newcommitter]. You may nominate yourself. Nomination should be sent to the [developer mailing list][devel].

#### Unitex/GramLab Sponsors

Unitex/GramLab Sponsors are ...

###### Become a Sponsor

#### Unitex/GramLab Project Management Committee

The Unitex/GramLab Project Management Committee (U/G-PMC) has additional responsibilities over and above those of a committer or sponsor. These responsibilities ensure the smooth running of the project. His members organizations do not have significant authority over other members of the community, although it makes decisions when community consensus cannot be reached.

* Participate in strategic planning.
* Approve changes to the governance model. 
* Manage the copyrights within the project outputs.
* Access to the project's private archives (They are never used for project management or planning, only include information about sensitive issues, and legal matters that cannot be discussed in public.)

Membership of the U/G-PMC is by invitation from the existing members. A nomination will result in discussion and then a vote by the existing members. Membership votes are subject to consensus approval of the current members. 

##### Unitex/GramLab Project Management Committee Chair

The U/G-PMC Chair is a single individual, voted for by the U/G-PMC members. Once someone has been appointed Chair, they remain in that role until they choose to retire, or the U/G-PMC casts a two-thirds majority vote to remove them.

The U/G-PMC Chair has no additional authority over other members of the U/G-PMC: the role is one of coordinator and facilitator. The Chair is also expected to ensure that all governance processes are adhered to, and has the casting vote when the project fails to reach consensus. 

### Decision Making Process 

From a practical point of view, the direction that the project takes is controlled by the contributors, not the users (unless they're contributors too). Development is made based on contributors and committers donating their time and money to the community. In order to ensure that the project is not bogged down by endless discussion and continual voting, the project operates using the [Apache Decision Making][makedecision] process. This allows the majority of decisions to be made without resorting to a formal vote.

#### Lazy Concensus

The [lazy consensus](http://community.apache.org/committers/lazyConsensus.html) is used for most the contribution ranging from bug fixes to minor changes where the contributor assume to have the support of the community to tackle the issue.

If you are not sure to have the support of the community for a change, you can state a lazy consensus. Member of the community have then 72h to provide feedback on the proposal. 

In all cases silence is consent.

#### Consensus Building

If you feel that lazy consensus isn't appropriate for your proposal, you can explicitly request for feedback on the the [developer mailing list][devel]. [Building concensus](http://community.apache.org/committers/consensusBuilding.html) help contributors and committers to gather feedback early on and pool the interest by the community for a new feature.

Contributors are invited to express their opinion of any given feature or pull request. Support is expressed using:

| Value | Meaning                                                                                                    |
| :---: |:---------------------------------------------------------------------------------------------------------- |
| +1    | I agree with this and will help make it happen                                                             |
| +0.9  | This is a cool idea and i like it, but I don't have time/the skills necessary to help out                  |
| +0    | I agree with this but probably won't make it happen, so my opinion is not that important                   |
| -0    | I don't agree with this, but I'm offering no alternative so my opinion is not that important               |
| -0.9  | I really don't like this, but I'm not going to stand in the way if everyone else wants to go ahead with it |
| -1    | I don't agree and I am offering an alternative that I am able to help implement                            |


#### Open Development Process

Unitex/GramLab development is based on user consensus and open discussion between users. Decision making must be done in a transparent, open fashion (ie. using discussion list and issue list). No decisions about the project's direction, bug fixes or features may be done in private without community involvement and participation. Discussions must begin at the earliest possible point on a topic; the community's participation is vital during the entire decision-making process.

### Unitex/GramLab Project License

* Core (Unitex) and IDE (GramLab) components are distributed under the terms of the GNU Lesser General Public License, version 2.1 [LGPLv2][LGPLv2], which itself incorporates the terms and conditions of the GNU General Public License.

* Linguistic Resources are distributed under the terms of the Lesser General Public License For Linguistic Resources [LGPL-LR][LGPL-LR].

* Unitex/GramLab includes copyrighted third-party libraries licensed either under the terms of the Apache Software License Version 1.1, or  under the terms of the [BSD 2-Clause][BSD-2-Clause] License ("BSD License"). All  third-party packages are copyright by their respective authors.

### About this document

This document is licensed under a [Creative Commons Attribution-ShareAlike 2.0](http://creativecommons.org/licenses/by-sa/2.0/). This work is based upon the ["OpenRefine Governance Model"](https://github.com/OpenRefine/openrefine.github.com/blob/master/governance.md) which itself is based upon the University of Oxford ["Meritocratic Governance Model"](http://www.oss-watch.ac.uk/resources/meritocraticGovernanceModel), the [OWIN Project Governance model](https://docs.google.com/document/d/1mn3dY6zNyKBU3P_TWoR-RdYpScJDbsXU2TRhwpSAha8) and the [Lazy Consensus](http://community.apache.org/committers/lazyConsensus.html) guideline available for the [Apache Community](http://community.apache.org).

--

Copyright (C) 2014-2015 Université Paris-Est Marne-la-Vallée

[RFC2119]:      http://tools.ietf.org/html/rfc2119
[repos]:        https://github.com/UnitexGramLab
[unitex]:       http://unitexgramlab.org
[forum]:        http://forum.unitexgramlab.org
[devel]:        mailto:unitex-devel@univ-mlv.fr
[tutorials]:    https://github.com/UnitexGramLab/unitex-doc-tutorials
[bugs]:         http://www-igm.univ-mlv.fr/~unitex/index.php?page=6
[LGPL-LR]:      http://bit.do/LGPL-LR
[LGPLv2]:       http://opensource.org/licenses/lgpl-2.1
[BSD-2-Clause]: http://opensource.org/licenses/BSD-2-Clause
[newcommitter]: https://community.apache.org/newcommitter.html
[makedecision]: http://community.apache.org/committers/decisionMaking.html

