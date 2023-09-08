---
title: "IETF Community Moderation"
category: bcp

docname: draft-ecahc-moderation-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
venue:
    mail: gendispatch@ietf.org
    github: larseggert/moderation
    latest: https://larseggert.github.io/moderation/draft-ecahc-moderation.html

author:

-
    name: Lars Eggert
    org: NetApp
    street: Stenbergintie 12 B
    city: Kauniainen
    code: "02700"
    country: FI
    email: lars@eggert.org
    uri: https://eggert.org/
-
    name: Alissa Cooper
    org: Cisco
    email: alcoop@cisco.com
-
    name: Jari Arkko
    org: Ericsson
    city: Kauniainen
    code: "02700"
    country: FI
    email: jari.arkko@ericsson.com
-
    name: Russ Housley
    org: Vigil Security
    email: housley@vigilsec.com
-
    name: Brian E. Carpenter
    ins: B. Carpenter
    org: The University of Auckland
    abbrev: Univ. of Auckland
    extaddr: School of Computer Science
    street: PB 92019
    city: Auckland
    code: 1142
    country: NZ
    email: brian.e.carpenter@gmail.com

normative:

informative:
  AHP:
    title: IETF Anti-Harassment Policy
    date: 2013-11-03
    author:
        - org: IESG
    target: https://www.ietf.org/about/groups/iesg/statements/anti-harassment-policy/
  OT:
    title: Ombudsteam
    date: false
    target: https://www.ietf.org/contact/ombudsteam/
  MODML:
    title: IESG Guidance on the Moderation of IETF Working Group Mailing Lists
    date: 2000-08-29
    author:
        - org: IESG
    target: https://www.ietf.org/about/groups/iesg/statements/mailing-lists-moderation/
  DP:
    title: IESG Statement on Disruptive Posting
    date: 2006-02-16
    author:
        - org: IESG
    target: https://www.ietf.org/about/groups/iesg/statements/disruptive-posting/

--- abstract

This document describes the creation of a moderator team for all of the
IETF's various contribution channels. Without removing existing responsibilities
for working group management, this team enables a uniform approach to moderation
of disruptive participation across all mailing lists and other methods of IETF
collaboration.

--- middle

# Introduction

This document proposes the creation of a moderator team for all of the
IETF's various contribution channels. This moderator team is modeled
after, and subsumes, the moderator team for the IETF discussion list
{{?RFC9245}}.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Motivation {#motiv}

The IETF community has defined general guidelines of conduct for
personal interaction in the IETF {{?RFC7154}}, and the IESG has
defined an anti-harassment policy for the IETF {{AHP}} for which the IETF
community has defined anti-harassment procedures {{!RFC7776}},
empowering an ombudsteam {{OT}} to take necessary action.

Dealing with *disruptive* behavior, however, is not part of the role
of the ombudsteam. {{?RFC3934}} task the chairs of each IETF working
group with moderating their group's in-person meetings and mailing
lists, and an IESG statement {{MODML}} describes additional guidance
to working group chairs about how - but not when - to moderate their
lists.

For IETF mailing lists not associated with a working group, another
IESG statement clarifies {{DP}} that the list administrators are
tasked with moderation. And the IETF list for general discussions
has, mostly for historic reasons, a team of moderators that are not
list administrators and operate by a different set of processes
{{?RFC9245}}.

In addition, {{?RFC3683}} defines a process for revoking an
individual's posting rights to IETF mailing lists following a
community last-call of a "posting rights" action (PR-action) proposed
by the IESG, often in response to complaints from the community.

This fractured approach to moderation of disruptive participation
through chairs, list administrators, and moderator teams, combined
with the IESG-led process of PR-actions, has proven to be less than
ideal:

- The IETF community has not been able to agree on a common definition
  of disruptive behavior. Therefore, chairs and list administrators
  apply individually different criteria when making decisions, and
  participants have different expectations for when PR-actions are
  warranted.

- The moderation process that chairs and list administrators need to
  follow {{?RFC3934}} is slow and cumbersome, which makes it
  ill-suited to situations that escalate quickly. It also assumes
  that the originator of disruptive behavior is a misguided
  participant who can be reasoned with and who will change their
  ways.

- Chairs and list administrators may only enact moderation actions for
  their single list, which is ill-suited when a pattern of disruptive
  behavior spans multiple lists. Also, chairs and list administrators
  may not be fully aware of disruptive behavior that spans multiple
  lists, due to not being subscribed to some of the affected.

- PR-actions, which can address disruptive behavior across several
  lists, are cumbersome and slow, and the community has not been able
  to agree on a common definition of disruptive behavior. This has
  led to a situation where PR-actions are rarely used, and when they
  are used, they are perceived as very heavy-handed.

- For a given mailing list, participants may not feel comfortable
  reporting disruptive behavior to a chair or list administrator, for
  various reasons. For mailing lists not associated with working
  groups, list administrators are not even publicly identified - they
  can only be contacted through an anonymous alias address. This
  exacerbates the problem, because participants may not be
  comfortable reporting disruptive behavior to an anonymous party.

- The IETF offers participation not only through in-person meetings
  and mailing lists, which are the two channels of participation for
  which moderation processes are currently defined. IETF business
  also happens in chat channels, remote meeting participation
  systems, virtual meetings, wikis, GitHub repositories, and more.
  How disruptive behavior is moderated in these channels is currently
  undefined.

# IETF Moderator Team

This document proposes a different, uniform approach to moderating the
IETF's various participation channels: a moderator team for the IETF.
The creation of this team intends to address the issues identified
in {{motiv}}.

{:aside}
> TODO: Decide whether moderation rights remain also with WG chairs,
> list admins, and others who currently have them, or whether all
> moderation rights centralize with the moderator team.

## Scope

This IETF moderator team consists of a small number of individuals
(no less than three) that SHALL moderate all the IETF's various
current and future participation channels. At present, these include
mailing lists, chat channels, and discussions in other systems that
the IETF or WGs have chosen to employ, such as GitHub repositories,
Wikis, or issue trackers.

It is not expected that the moderator team will be monitoring every
IETF channel, but rather that participants will proactively flag
concerns about disruptive behavior to the moderator team. However,
the moderator team SHOULD actively monitor a small set of key
participation channels, including, for example, the IETF discussion
and last-call mailing lists or the IETF plenary chat channel. The
moderator team should decide which channels are in this set based on
their own judgment and community suggestions.

The management and moderation of in-person, remote, and interim
meetings remains a task of the relevant group's management, such as
WG chairs. However, it is expected that moderators are available for
consultation and assistance should issues arise, and they may confer
with the group management over potential patterns of behavior.

The moderator team SHALL operate according to a consistent and uniform
set of criteria, processes, and actions. The moderator team SHALL
independently define and execute their role. They SHALL maintain a
public set of moderation criteria, processes, actions, and other
material that allows the community to understand and comment on the
role of the team. The moderator team SHOULD consider adopting
moderation criteria, processes, and actions that other technical
communities have found suitable. The moderator team's criteria and
processes SHALL be developed with community input, but they are not
expected to be documented in the RFC series.

The moderator team MAY initiate moderation actions by itself;
individual participants SHOULD also alert the team to disruptive
behavior they observe. Participants should be able to contact the
moderator team in ways that are, ideally, integrated into the various
participation channels the IETF offers.

{:aside}
> TODO: Decide whether chairs and list admins should retain the
> ability to moderate their lists in addition to the moderator team,
> or whether chair and list admins should only inform the moderator
> team of potentially disruptive behavior and let them deal with it.

## Membership

The IETF Chair appoints members of the moderator team. Apart from
appointing moderators, the IETF Chair SHALL refrain from the
day-to-day operation and management of the moderator team. The
moderator team MAY decide to consult with the IETF Chair when needed.

Because the IESG and IAB are in the appeals chain for moderator team
decisions (see {{appeals}}), the IETF Chair SHOULD NOT appoint a
moderator who is serving on the IESG or IAB. Individuals serving on
other bodies to which the NomCom appoints members, such as the IETF
Trust or the LLC Board, as well as LLC staff and contractors SHALL
also be excluded from serving on the moderator team. If a moderator
is assuming any such role, they SHALL step down from the moderator team
soon after.

## Appeals {#appeals}

Because the moderator team serves at the discretion of the IETF Chair,
any moderation decision can be appealed to the IETF Chair, per
{{!RFC2026}}. Disagreements with a decision by the IETF Chair can be
brought to their attention. If this does not lead to a resolution, a
decision by the IETF Chair can be appealed as described in
{{!RFC2026}}, as with any other Area Director decision. In this case,
the appeals chain starts with an appeal to the entire IESG.

## Team Diversity

Due to the global nature of the IETF, the membership of this team
SHOULD reflect a diversity of time zones and other participant
characteristics that lets it operate effectively around the clock and
throughout the year. Team diversity is also important to ensure any
participant observing problematic behavior can identify a moderator
they feel comfortable contacting.

## Relation to Ombudsteam

The moderator team SHALL complement the efforts of the IETF
ombudsteam {{OT}}, whose focus on anti-harassment and operation
SHALL remain unchanged. The moderator team and ombudsteam are
expected to work together in cases that may involve both disruptive
behavior and harassment; they may determine the most effective way to
do so in each case.

The ombudsteam has strict rules of confidentiality. If a moderation
case overlaps with an ombudsteam case, confidential information MUST
NOT be shared between the teams.

# Changes to Existing RFCs

Creation of the IETF moderator team requires some changes to existing
RFCs and also requires the IESG to update a number of their
statements. This section describes these changes.

{:aside}
> TODO: Add once we know this I-D will go forward in some form.

# Security Considerations

The usual security considerations {{?RFC3552}} do not apply to this
document.

Potential abuse of the moderation process for the suppression of
undesired opinions is counteracted by the availability of an appeals
process, per {{appeals}}.

# IANA Considerations

This document has no IANA actions.

# Acknowledgments

These individuals suggested improvements to this document:

- Jay Daley
- Rich Salz

--- back
