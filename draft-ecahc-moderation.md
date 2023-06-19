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

TODO Abstract

--- middle

# Introduction

This document proposes the creation of a moderation team for all of
the IETF's various contribution channels. This moderation team is
modeled after, and subsumes, the moderation team for the IETF
discussion list {{?RFC9245}}.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Motivation

The IETF community has defined general guidelines of conduct for
personal interaction in the IETF {{?RFC7154}}, and the IESG has
defined an anti-harassment policy for the IETF {{AHP}} that the IETF
community has defined anti-harassment procedures {{?RFC7776}} for,
empowering an ombudsteam {{OT}} to take necessary action.

Dealing with *disruptive* behavior, however, is not part of the role
of the ombudsteam. {{?RFC3934}} task the chairs of each IETF working
group with moderating their group's in-person meetings and mailing
lists, and an IESG statement {{MODML}} describes additional guidance
to working group chairs. For IETF mailing lists not associated with a
working group, another IESG statement clarifies {{DP}} that the list
administrators are tasked with moderation.

In addition, {{?RFC3683}} defines a process for revoking an
individual's posting rights to IETF mailing lists following a
community last-call of a "PR-action" proposed by the IESG, often in
response to complaints from the community.

This decentralized approach to moderation of disruptive participation
through chairs and list administrators, combined with the IESG-led
process of PR-actions, has proven to be less than ideal:

* The IETF community has not been able to agree on a common definition
  of disruptive behavior. Therefore, chairs and list administrators
  apply individually different criteria when making decisions, and
  participants have different expectations for when PR-actions are
  warranted.

* The moderation process that chairs and list administrators need to
  follow {{?RFC3934}} is slow and cumbersome, which makes it
  ill-suited to situations that escalate quickly. It also assumes
  that the originator of disruptive behavior is a misguided
  participant that can be reasoned with and who will change their
  ways.

* Chairs and list administrators may only enact moderation actions for
  their single list, which is ill-suited when disruptive behavior
  spans multiple lists. Also, chairs and list administrators may not
  be aware of a pattern of disruptive behavior that spans multiple
  lists, due to not being subscribed to the other lists in question.

* PR-actions, which can address disruptive behavior across several
  lists, are cumbersome and slow, and the community has not been able
  to agree on a common definition of disruptive behavior. This has
  led to a situation where PR-actions are rarely used, and when they
  are used, they are perceived as very heavy-handed.

* For a given mailing list, participants may not feel comfortable
  reporting disruptive behavior to a chair or list administrator due
  to personal reasons. For mailing lists not associated with working
  groups, list administrators are not even publicly identified - they
  can only be contacted through an anonymous alias address. This
  exacerbates the problem, because participants may not be
  comfortable reporting disruptive behavior to an anonymous party.

* The IETF offers participation not only through in-person meetings
  and mailing lists, which are the two channels of participation for
  which moderation processes are currently defined. IETF business
  also happens in chat channels, remote meeting participation
  systems, virtual meetings, wikis, GitHub repositories, and more.
  How disruptive behavior is moderated in these channels is currently
  undefined.

# Scope

These channels currently include mailing lists, chat channels and
in-person and remote meetings.

This team SHALL also moderate participation in other future channels.

# Appeals

# Security Considerations

This document raises no security issues.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
