## Unitex/GramLab Governance Model

> This document is a draft for discussion and still a work in progress. To contribute, please submit a [pull request](https://github.com/UnitexGramLab/governance/pulls). Major changes will be discussed in the comment section.

> The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in the [RFC 2119][RFC2119] 

### History

| Date     | Version    | User              | Description                                                         |
| :------: | :--------: | ----------------- | ------------------------------------------------------------------- |
| 05/05/15 | 0.1.0      | martinec          | First draft                                                         |
| 05/06/15 | 0.1.1      | martinec          | Improve information about licenses                                  |
| 11/07/15 | 0.1.2      | martinec          | Fix information about committers                                    |
| 18/02/16 | 0.1.2      | martinec          | Add some missing links                                              |
| 06/04/16 | 0.1.3      | martinec          | Unitex/GramLab adheres to the Contributor Covenant code of conduct  |


### Overview

[Unitex/GramLab][unitex] is an open source, cross-platform, multilingual, lexicon- and grammar-based corpus processing suite. Project decision-making is based on a community meritocratic process. Anyone with an interest in Unitex/GramLab can join the community, contribute to the project design and participate in decisions. This document describes how that participation takes place and how to set about earning merit within the project community.

### Background

#### Project Infrastructure

| Name                     | Link                                          |
| -------------------------| ----------------------------------------------|
| Main website             | http://unitexgramlab.org                      |
| Binary releases          | http://releases.unitexgramlab.org             |
| Users forum              | http://forum.unitexgramlab.org                |
| Developers mailing list  | unitex-devel@univ-mlv.fr                      |
| Code hosting (legacy)    | https://gforgeigm.univ-mlv.fr/projects/unitex |
| Code hosting (current)   | http://code.unitexgramlab.org                 |
| Governance               | http://governance.unitexgramlab.org           |

#### Project License

* All Unitex/GramLab programs, libraries and source codes are distributed under the terms of the [GNU Lesser General Public License version 2.1][LGPLv2] (LGPLv2), which itself incorporates the terms and conditions of the GNU General Public License.

* Linguistic Resources are distributed under the terms of the [Lesser General Public License For Linguistic Resources][LGPLLR] (LGPLLR).

* Documentation is licensed under the terms of the [GNU Free Documentation License version 1.3][GFDL] (GFDL), as published by the Free Software Foundation.

* Unitex/GramLab includes copyrighted third-party libraries licensed under the terms of the [Apache Software License version 2.0][Apache-2.0] (Apache-2.0), the [BSD 2-Clause License][BSD-2-Clause] (BSD License), and the [MIT License][MIT] (MIT). All  third-party packages are copyright by their respective authors.

#### Project Code of Conduct

Unitex/GramLab is intended to be a safe, welcoming space for collaboration. All contributors and participants are expected to adhere to the [Contributor Covenant version 1.4](http://contributor-covenant.org/version/1/4/code_of_conduct.md) code of conduct. To report violations, send an email to unitex-devel@univ-mlv.fr.

#### Getting support

All participants in the Unitex/GramLab community are encouraged to provide support for new users within the project management infrastructure. This support is provided as a way of growing the community. Those seeking support should recognise that all support activity within the project is voluntary and is therefore provided as and when time allows. A user requiring guaranteed response times or results should therefore seek to purchase a support contract from a community member. However, for those willing to engage with the project on its own terms, and willing to help support other users, the community support channels, as the [developer mailing list][devel] or the [users forum][forum], are ideal.

### Roles And Responsibilities

Unitex/GramLab development is based on user consensus and open discussion between users. In order to have a smoothly running project, formal roles with corresponding responsibilities are established. A member of the community may have multiple roles.

 <table align="center">
  <tr>
    <th>Role</th>
    <th>Type</th>
    <th>Name</th>
  </tr>
  <tr align="center">
     <td colspan="2">Unitex/GramLab User</td>
     <td>[User](#unitexgramlab-user)</td>
  </tr>
  <tr align="center">
    <td colspan="2">Unitex/GramLab Contributor</td>
    <td>[Contributor](#unitexgramlab-contributor)</td>
  </tr>
  <tr align="center">
    <td  rowspan="3">Unitex/GramLab Commiter</td>
    <td>Non-Coding Commiter</td>
    <td>[Commiter](#non-coding-commiter)</td>
  </tr>
  <tr align="center">
    <td> Linguistic Resources Commiter</td>
    <td>[LR-Commiter](#linguistic-resources-commiter)</td>
  </tr>
  <tr align="center">
    <td>Coding Commiter</td>
    <td>[DEV-Commiter](#coding-commiter)</td>
  </tr>
  <tr align="center">
    <td colspan="2">Unitex/GramLab Sponsor</td>
    <td>[Sponsor](#unitexgramlab-sponsor)</td>
  </tr>
  <tr align="center">
    <td rowspan="2">Unitex/GramLab Management Committee Member</td>
    <td>Committee Member</td>
    <td>[Committee Member](#committee-member)</td>
  </tr>
  <tr align="center">
    <td>Committee Chair</td>
    <td>[Project Leader](#committee-chair)</td>
  </tr>
</table>

#### Unitex/GramLab User

Unitex/GramLab users are community members who have a need for the project, they are the most important members of the community: through their usage, they give the project a purpose. Users should be encouraged to participate in the life of the project and the community as much as possible. User contributions enable the project team to ensure that they are satisfying the needs of those users. Common user activities include, but are not limited to:

* Evangelising about the project.
* Informing developers of strengths and weaknesses from a new user perspective both through the [Unitex/GramLab forum][forum] or following the [Bug Reporting Guide][bugs].
* Identifying needs and filing feature requests.
* Participating on the [users forum][forum].
* Providing moral support, a 'thank you' goes a long way.

###### Become a Unitex/GramLab User

Anyone can be a user; there are no special requirements. Users who continue to engage with the project and the community will often find themselves becoming more and more involved. Such users may then go on to become Unitex/GramLab Contributors, as described below.

#### Unitex/GramLab Contributor

Unitex/GramLab Contributors are community members who contribute in concrete ways to the project. Contribution may be a one time participation or occur over time. Contribution can take place in many specific ways:

* Helping maintain existing linguistic resources.
* Submitting patches to fix bugs or add features.
* Identifying requirements.
* Participating in the community's activities.

#### Unitex/GramLab Committer

Unitex/GramLab Committers are contributors who have shown dedication to the project, i.e. providing valuable contribution over a period of time, have a deep understanding of the code base and project strategy and work well with contributors and users. Committers have no more authorities than contributors, and they should engage with the community through the [developer mailing list][devel] or the [users forum][forum] regarding their intention. However committers have earn enough trust from the community to have direct access to the project code base without having to submit pull requests. Committers seeks approval after the contribution is made, rather than before. Therefor committers:

* Help contributors via the [developer mailing list][devel].
* Merge pull request submit by contributors.
* Have direct access to the code base.
* Nominate and vote new committers.
* Participate in the release planning.

##### Linguistic Resources Commiter
[LR-contributor]

* Contributing to new linguistic resources and helping maintain existing ones.

###### Become a Linguistic Resources Commiter

You need to start being a Unitex/GramLab Contributor and be then be nominated as a Linguistic Resources Commiter. Unitex/GramLab committers select and elect new ones using the [Guidelines for assessing new candidates for committership][newcommitter] from the Apache Software Foundation.

##### Coding Commiter
[DEV-Commiter]

* Adding features.
* Assisting with project infrastructure.

###### Become a Coding Commiter

The [documentation for developers](https://github.com//UnitexGramLab/unitex-doc-devel) is a good place to start getting familiar with the coding style and documentation guidelines. We invite contributors to share their feature development and patch idea through the [developer mailing list][devel] or the [users forum][forum]. It is recommended to start with small patches and share your code early so the existing committers can provide feedback and guidance.

##### Non-Coding Commiter

[Non-code contributions](https://modelviewculture.com/pieces/non-coding-contributors-in-open-source) ([Commiter]) are incredibly valuable and very welcome,  Here are some examples of simple ways to contribute:

* Writing and maintaining the documentation (e.g. [tutorials][tutorials])

###### Become a Non-Coding Commiter

#### Unitex/GramLab Sponsor

Unitex/GramLab Sponsors are ...

###### Become a Sponsor

#### Unitex/GramLab Management Committee

The Unitex/GramLab Management Committee (UGMC) has additional responsibilities over and above those of a committer or sponsor. These responsibilities ensure the smooth running of the project. Project Management Committee activities include:

* Participate in strategic planning.
* Approve changes to the governance model. 
* Manage the copyrights within the project outputs.
* Access to the project's private archives (They are never used for project management or planning. This include information about sensitive issues, and legal matters that cannot be discussed in public.)

##### Committee Member

The Unitex/GramLab Management Committee Members do not have significant authority over other members of the community, although they make decisions when community consensus cannot be reached. 

Membership of the UGMC is by invitation from the existing members. A nomination will result in discussion and then a vote by the existing members. Membership votes are subject to consensus approval of the current members.

##### Committee Chair

The UGMC Chair is a single committer and the project leader whom people interested in the project can consider the primary point of contact or first point of contact for the project. The chair is voted by the members. Once someone has been appointed Chair, they remain in that role until they choose to retire, or the UGMC casts a two-thirds majority vote to remove them.

The Chair has no additional authority over other members of the UGMC: the role is one of coordinator and point of contact. The Chair is also expected to ensure that all governance processes are adhered to, and has the casting vote when the project fails to reach consensus. 

### Decision Making Process 

From a practical point of view, the direction that the project takes is controlled by the contributors, not the users, unless they're contributors too. Development is made based on contributors and committers donating their time to the community. In order to ensure that the project is not bogged down by endless discussion and continual voting, the project operates using the [Apache Decision Making][makedecision] process. This allows the majority of decisions to be made without resorting to a formal vote.

#### Lazy Consensus

[Lazy Consensus](http://community.apache.org/committers/lazyConsensus.html) is a very important concept within the project. It is this process that allows a large group of people to efficiently reach consensus, as someone with no objections to a proposal need not spend time stating their position, and others need not spend time reading such mails. For lazy consensus to be effective, it is necessary to allow at least 72 hours before assuming that there are no objections to the proposal. This requirement ensures that everyone is given enough time to read, digest and respond to the proposal. This time period is chosen so as to be as inclusive as possible of all participants, regardless of their location and time commitments. In all cases silence is consent.

The lazy consensus is used for most the contribution ranging from bug fixes to minor changes where the contributor assume to have the support of the community to tackle the issue.

#### Building consensus

Not all decisions can be made using lazy consensus. If you feel that lazy consensus isn't appropriate for your proposal, you can explicitly request for feedback on the [developer mailing list][devel]. [Building consensus](http://community.apache.org/committers/consensusBuilding.html) help contributors and committers to gather feedback early on and pool the interest by the community for a new feature.

Contributors are invited to express their opinion of any given feature or pull request. Support is expressed using:

| Value | Meaning                                        | Signifié                                                  |
| :---: |:-----------------------------------------------|:--------------------------------------------------------- |
| +1    | I agree with this and will help make it happen | Je suis d'accord, je peux aider si besoin            |
| +0.9  | This is a cool idea and i like it, but I don't have time/the skills necessary to help out | Je suis d'accord, mais je n'ai pas le temps / les compétences nécessaires pour aider                  |
| +0    | I agree with this but probably won't make it happen, so my opinion is not that important | Je suis d'accord, mais ceci n'arrivera pas, donc mon avis n'est pas si important   |
| -0    | I don't agree with this, but I'm offering no alternative so my opinion is not that important | Je ne suis pas d'accord, mais je ne propose pas une alternative, donc mon avis n'est pas si important            |
| -0.9  | I really don't like this, but I'm not going to stand in the way if everyone else wants to go ahead with it  | Je ne suis pas d'accord, mais je ne vais pas m'y opposer si tous les autres sont d'accord |
| -1    | I don't agree and I am offering an alternative that I am able to help implement | Je ne suis pas d'accord, je vous offre une alternative que je vais aider à mettre en place                           |

#### Transparency

Building community trust in the governance of an open-source project is vital to its success. To that end, Unitex/GramLab project decision making must be done in a transparent, open fashion. No decisions about the project's direction, bug fixes or features may be done without community involvement and participation. Discussions must begin at the earliest possible point on a topic; the community’s participation is vital during the entire decision-making process.

### About this document

This document is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/). This work is based upon the [OpenRefine Governance Model](https://github.com/OpenRefine/openrefine.github.com/blob/master/governance.md) and the [OWIN Project Governance model](https://docs.google.com/document/d/1mn3dY6zNyKBU3P_TWoR-RdYpScJDbsXU2TRhwpSAha8), which themselves are based upon  [Meritocratic Governance Model](http://www.oss-watch.ac.uk/resources/meritocraticGovernanceModel) by University of Oxford. This document contains information about the [Lazy Consensus](http://community.apache.org/committers/lazyConsensus.html) concept available from the [Apache Community](http://community.apache.org) and uses the [Semantic Versioning scheme](http://semver.org) to track version releases.

--

Copyright (C) 2016 Université Paris-Est Marne-la-Vallée

[RFC2119]:      http://tools.ietf.org/html/rfc2119
[repos]:        https://github.com/UnitexGramLab
[unitex]:       http://unitexgramlab.org
[forum]:        http://forum.unitexgramlab.org
[devel]:        mailto:unitex-devel@univ-mlv.fr
[tutorials]:    https://github.com/UnitexGramLab/unitex-doc-tutorials
[bugs]:         http://www-igm.univ-mlv.fr/~unitex/index.php?page=6
[newcommitter]: https://community.apache.org/newcommitter.html
[makedecision]: http://community.apache.org/committers/decisionMaking.html

[Apache-2.0]:   http://opensource.org/licenses/Apache-2.0
[BSD-2-Clause]: http://opensource.org/licenses/BSD-2-Clause
[GFDL]:         http://www.gnu.org/licenses/fdl-1.3.txt
[MIT]:          http://opensource.org/licenses/MIT
[LGPLLR]:       http://spdx.org/licenses/LGPLLR
[LGPLv2]:       http://opensource.org/licenses/lgpl-2.1
