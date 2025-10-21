---
id: 'nominate-ppmc-member'
title: 'Nominate New PPMC Member'
---

## Nominate PPMC member Guide

This document describes how Apache Fesod (incubating) PPMC members can nominate new PPMC members.

## Discuss Candidate
Start a discussion by sending an email to private@fesod.apache.org:

candidate_name: Full name of the candidate.
candidate_github_id: Candidate's GitHub ID.
Subject:

```text
[Discuss] Nomination of ${candidate_name} as a PPMC member for Apache Fesod (Incubating)
```

Body:

```text
Hi All,

I'm reaching out to officially nominate ${candidate_name} [1] as a new
PPMC member for Apache Fesod (incubating).

${candidate_contributions}

Feel free to share any thoughts or suggestions you might have!

[1]. https://github.com/${candidate_github_id}

Warm regards,

${your_name}
```

## Initiate Candidate Vote
Start a vote by sending an email to private@fesod.apache.org:

candidate_name: Full name of the candidate.
candidate_github_id: Candidate's GitHub ID.
discussion_thread: Discussion email thread URL.
vote_thread: Vote email thread URL.
Subject:

```text
[VOTE] New PPMC member: ${candidate_name}
```

Body:

```text
Hi All,

We've been discussing ${candidate_name} [1] becoming a new PPMC member for our community, as you might have seen in discussion thread [2]. Now it's time to kick off the official voting process. We'd love for you to cast your vote and let us know if you support bringing ${candidate_name} on board as a new PPMC member. Your input is super important in helping us make this decision.

Voting ends one week from today.

Please vote accordingly:

[ ] +1 approve

[ ] +0 no opinion

[ ] -1 disapprove (and reason)

[1]. https://github.com/${candidate_github_id}
[2]. https://lists.apache.org/thread/${discussion_thread}

Warm regards,
${your_name}
```

## Announce Vote Result
After at least 3 "+1" binding votes and no vetoes, announce the vote result:

Subject:

```text
[RESULT] [VOTE] New PPMC member:${candidate_name}
```

Body:

```text
Hi All,

The vote for ${candidate_name} to become a new PPMC member has passed, with ${N} +1 binding votes, no +0 or -1 votes.

${N} (+1 binding)

- XXX
- YYY
- ZZZ

Vote thread: https://lists.apache.org/thread/${vote_thread}

Warm regards,
${your_name}
```

## Send NOTICE to IPMC
After announcing the vote result on the PPMC private list, send a NOTICE email to the IPMC (private@incubator.apache.org) to inform them of the new PPMC member addition:

Subject:

```text
[NOTICE] New PPMC member for Apache Fesod (Incubating): ${candidate_name}
```

Body:

```text
Hi IPMC,

Apache Fesod (Incubating) PPMC has voted in ${candidate_name} as a new PPMC member.

Vote result: ${N} +1 binding votes, no vetoes
Vote thread: https://lists.apache.org/thread/${vote_thread}

The PPMC will now send an invitation to the candidate to join the PPMC.

Regards,
${your_name}
Apache Fesod PPMC Member
```

## Send Invitation Email to Candidate
After sending the NOTICE to IPMC, send a formal invitation email to the candidate and CC private@fesod.apache.org:

Subject:

```text
[INVITATION] Apache Fesod (Incubating) PPMC Membership for ${candidate_name}
```

Body:

```text
Dear ${candidate_name},

On behalf of the Apache Fesod (Incubating) Podling Project Management Committee (PPMC), I am pleased to invite you to become a PPMC member of the Apache Fesod project.

The PPMC has voted to approve your membership based on your valuable contributions to the project. As a PPMC member, you will have the privilege to:

- Participate in PPMC discussions and decisions
- Vote on PPMC matters including new committers and PPMC members
- Help guide the project's development and community growth
- Contribute to the project's success within the Apache Software Foundation

This invitation comes with the understanding that you will use these privileges responsibly and in accordance with Apache's principles of open governance and collaborative development.

Of course, you may decline this invitation and continue to participate as a contributor. This is a personal invitation, and your response can be made privately.

Please reply to this message to let us know whether you accept or decline this invitation.

If you accept, please ensure you have completed your iCLA (Individual Contributor License Agreement) if you haven't already done so. You can check your status and complete the iCLA at: https://www.apache.org/licenses/icla.pdf

We look forward to your positive response and continued contributions to Apache Fesod.

Best regards,

${your_name}
Apache Fesod PPMC Member
```

## Add Candidate to PPMC List
After the candidate accepts the invitation and records their iCLA, add the candidate to the PPMC list through [whimsy roster tools](https://whimsy.apache.org/roster/ppmc/fesod#pmc)

## Announce
Once the nominee accepts the invitation, send a notification email to dev@fesod.apache.org to welcome the new PPMC member. Here is an email template:

Subject:

```text
Welcome new PPMC member: ${candidate_name}
```

Body:

```text
Hi Community,

On behalf of Apache Fesod(incubating) PPMC, I am pleased to announce that ${candidate_name} [1], has been voted as a new PPMC member.

Please join me to say congratulations to him!

${candidate_name}, would you please briefly introduce yourself to community?

[1]. https://github.com/${candidate_github_id}

Warm regards,
${your name}
```