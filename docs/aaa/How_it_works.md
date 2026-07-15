---
title: How AAA works day to day
---

# How AAA works day to day

## The flow

```mermaid
sequenceDiagram
  participant Broker
  participant You as Your inbox
  participant SkillATS
  participant Recruiter as You in SkillATS

  Broker->>You: Assignment email
  You->>SkillATS: Forwarded to your AAA address
  SkillATS->>SkillATS: Reads each assignment
  SkillATS->>SkillATS: Searches candidates with your prompt
  SkillATS->>Recruiter: Emails shortlist (up to 10)
  Recruiter->>SkillATS: Opens link in AI Search
  SkillATS->>Recruiter: Shows assignment + shortlist
```

1. A broker sends an assignment email.
2. Your rule forwards it to SkillATS.
3. SkillATS extracts each assignment from the message.
4. It searches your candidates using the prompt you saved.
5. You get an email with a shortlist (up to 10 people).
6. Open the link to review and continue in AI Candidate Search.

From there, open candidates, compare them, and move good matches onto the right job board.

![AAAEmail](../assets/AAAEmail.png)

![AAASkillATS](../assets/AAASkillATS.png)

## Privacy

Candidate data still follows your company’s retention and privacy rules. See [Privacy and GDPR](../settings/GDPR_and_privacy.md).
