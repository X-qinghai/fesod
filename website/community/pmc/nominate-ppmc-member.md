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

## Send Invitation Email to Candidate
Send an invitation email to the candidate and CC private@fesod.apache.org:

Subject:

```text
Invitation to become Apache Fesod(incubating) PPMC member: ${candidate_name}
```

Body:

```text
Hi ${candidate_name},

The Fesod Podling Project Management Committee (PPMC) hereby offers
you membership in PPMC. These privileges are offered on the
understanding that you'll use them reasonably and with common sense.
We like to work on trust rather than unnecessary constraints.

Of course, you can decline and instead remain as a contributor,
participating as you do now.

This personal invitation is a chance for you to accept or decline in private.
Please let us know in reply to this message whether you accept or decline.

Warm regards,
${your_name}
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