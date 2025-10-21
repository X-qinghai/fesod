---
id: 'nominate-ppmc-member'
title: '提名新 PPMC 成员'
---

本文档主要介绍Apache Fesod (incubating) PPMC成员如何提名新的PPMC成员。

## 讨论候选人
发起一个讨论到邮件到 private@fesod.apache.org:

candidate_name: 候选人全名。
candidate_github_id: 候选人 GitHub id。
标题:

```text
[Discuss] Nomination of ${candidate_name} as a PPMC member for Apache Fesod (Incubating)
```

正文:

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

## 发起候选人投票
发起一个投票到邮件 private@fesod.apache.org:

candidate_name: 候选人全名。
candidate_github_id: 候选人的 GitHub id。
discussion_thread: 讨论邮件 thread URL。
vote_thread: 投票邮件 thread URL。
标题:

```text
[VOTE] New PPMC member: ${candidate_name}
```

正文:

```text
Hi All,

We've been discussing ${candidate_name} [1] becoming a new PPMC member for our community, as you might have seen in discussion thread [2]. Now it's time to kick off the official voting process. We'd love for you to cast your vote and let us know if you support bringing ${candidate_name} on board as a new PPMC member. Your input is super
important in helping us make this decision.

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

在至少 3 "+1" 有约束力的投票且没有否决后，宣布投票结果：

标题:

```text
[RESULT] [VOTE] New PPMC member:${candidate_name}
```

正文:

```text
Hi All,

The vote for ${candidate_name} to become a new PPMC member has passed, with ${N}  +1 binding votes, no +0 or -1 votes.

${N} (+1 binding)

- XXX
- YYY
- ZZZ

Vote thread: https://lists.apache.org/thread/${vote_thread}

Warm regards,
${your_name}
```

## 发送邀请邮件给候选人
给候选人发送邮件邀请并抄送private@fesod.apache.org:

标题:

```text
Invitation to become Apache Fesod(incubating) PPMC member: ${candidate_name}
```

正文:

```text
Hi ${candidate_name},

The Fesod Podling Project Management Committee (PPMC)  hereby offers
you membership in PPMC. These privileges are  offered on the
understanding that you'll use them reasonably and with common sense.
We like to work on trust rather than unnecessary constraints.

Of course, you can decline and instead remain as a contributor,
participating as you do now.

This personal invitation is a chance for you to accept or decline in private.
Please let us know in reply to this message whether you accept or decline.

Warm regards,
${your_name}
```

## 添加候选人到 PPMC 列表
在候选人接受邀请并记录iCLA后，将候选人添加到PPMC列表中，通过 [whimsy roster tools](https://whimsy.apache.org/roster/ppmc/fesod#pmc)

## 宣布
一旦被提名人接受了邀请，发送一封通知邮件 到dev@fesod.apache.org 欢迎新的 PPMC member。下面是一个电子邮件模板：

标题:

```text
Welcome new PPMC member: ${candidate_name}
```

正文:

```text
Hi Community,

On behalf of Apache Fesod(incubating) PPMC, I am pleased to announce that ${candidate_name} [1], has been voted as a new PPMC member.

Please join me to say congratulations to him !

${candidate_name}, would you please briefly introduce yourself to community?


[1]. https://github.com/${candidate_github_id}

Warm regards,
${your name}
```