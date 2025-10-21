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

## 宣布投票结果
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

## 向 IPMC 发送通知
在PPMC私有邮件列表上宣布投票结果后，向IPMC（private@incubator.apache.org）发送NOTICE邮件，通知新的PPMC成员加入：

标题:

```text
[NOTICE] New PPMC member for Apache Fesod (Incubating): ${candidate_name}
```

正文:

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

## 发送邀请邮件给候选人
向IPMC发送NOTICE后，向候选人发送正式邀请邮件并抄送private@fesod.apache.org:

标题:

```text
[INVITATION] Apache Fesod (Incubating) PPMC Membership for ${candidate_name}
```

正文:

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