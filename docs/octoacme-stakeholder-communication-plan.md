# OctoAcme — Stakeholder Communication Plan Template

## Purpose
Ensure all stakeholders receive timely, relevant updates throughout the project lifecycle. This template helps project managers identify stakeholders, define communication needs, and maintain consistent engagement.

## When to Use
- During project initiation to establish communication expectations
- Updated throughout the project as stakeholders or needs change
- Referenced during project execution to ensure no stakeholder is overlooked

---

## Stakeholder Identification

### Stakeholder Matrix

| Stakeholder Name/Group | Role | Interest Level | Influence Level | Communication Priority |
|------------------------|------|----------------|-----------------|------------------------|
| Example: Jane Smith | Executive Sponsor | High | High | Critical |
| Example: Engineering Team | Contributors | High | Medium | High |
| Example: Customer Success | Informed | Medium | Low | Medium |

**Interest Level**: How much this stakeholder cares about the project (High/Medium/Low)  
**Influence Level**: How much this stakeholder can impact project decisions (High/Medium/Low)  
**Communication Priority**: Based on interest + influence (Critical/High/Medium/Low)

---

## Communication Plan

### Critical Priority Stakeholders

| Stakeholder | Information Needs | Communication Method | Frequency | Owner |
|-------------|-------------------|---------------------|-----------|-------|
| Example: Executive Sponsor | High-level status, risks, major decisions | 1:1 meeting + email summary | Weekly | PM |
| Example: Product Lead | Progress, blockers, scope changes | Sync meeting + Slack | Daily/Weekly | PM + PdM |

### High Priority Stakeholders

| Stakeholder | Information Needs | Communication Method | Frequency | Owner |
|-------------|-------------------|---------------------|-----------|-------|
| Example: Engineering Team | Task assignments, technical decisions, blockers | Standup + Slack | Daily | PM |
| Example: Security Lead | Security requirements, threat model updates, vulnerabilities | Email + Review meetings | As needed + Milestone reviews | PM + Security Lead |

### Medium Priority Stakeholders

| Stakeholder | Information Needs | Communication Method | Frequency | Owner |
|-------------|-------------------|---------------------|-----------|-------|
| Example: Customer Support | Feature changes, known issues, rollout timeline | Email update + Q&A session | Before release | PM + PdM |
| Example: Marketing | Release dates, key features, customer messaging | Email + Documentation | Monthly / Major releases | PdM |

### Low Priority Stakeholders

| Stakeholder | Information Needs | Communication Method | Frequency | Owner |
|-------------|-------------------|---------------------|-----------|-------|
| Example: Legal/Compliance | Compliance impacts, data handling changes | Email notification | As needed | PM |
| Example: Finance | Budget impact, resource allocation | Email update | Quarterly | PM |

---

## Communication Channels

### Standard Channels
- **Email**: Formal updates, status reports, decision documentation
- **Slack/Teams**: Quick questions, daily updates, informal coordination
- **Project Board**: Real-time task status (GitHub Projects, Jira, etc.)
- **Meetings**: Planning, reviews, retrospectives, stakeholder briefings
- **Documentation**: Project charter, design docs, runbooks (in repo or wiki)

### Channel Guidelines
- Use email for decisions requiring a paper trail
- Use Slack/Teams for time-sensitive coordination
- Update project board daily to reflect current status
- Schedule recurring meetings in advance; send agendas 24 hours before
- Store documentation in version control or wiki

---

## Communication Templates

### Weekly Status Update Email

```
Subject: [Project Name] – Week of [Date] Status Update

Hi [Stakeholder Group],

**Progress This Week:**
- [Key accomplishment 1]
- [Key accomplishment 2]
- [Key accomplishment 3]

**Next Week Priorities:**
- [Priority 1]
- [Priority 2]

**Risks & Blockers:**
- [Risk/Blocker 1] – Mitigation: [plan]
- [Risk/Blocker 2] – Status: [in progress/escalated]

**Decisions Needed:**
- [Decision 1] – By when: [date]
- [Decision 2] – Owner: [name]

**Upcoming Milestones:**
- [Milestone] – Target: [date]

Questions? Reply to this email or ping me in [Slack channel].

Thanks,
[Your Name]
```

### Project Kickoff Email

```
Subject: [Project Name] Kickoff – Stakeholder Engagement

Hi everyone,

We're kicking off [Project Name] to [brief objective]. This email outlines how we'll keep you informed and involved.

**Project Overview:**
- Goal: [high-level goal]
- Timeline: [start] to [end]
- Key Milestones: [milestone 1], [milestone 2], [milestone 3]

**Your Role:**
You're receiving this because you are a [stakeholder type]. We'll share updates [frequency] via [channel].

**How to Stay Informed:**
- [Communication method 1]: [frequency]
- [Communication method 2]: [frequency]
- Project Board: [link]

**Key Contacts:**
- Project Manager: [name] – [email/slack]
- Product Lead: [name] – [email/slack]
- Technical Lead: [name] – [email/slack]

**Next Steps:**
- [Date]: Project kickoff meeting (invite sent separately)
- [Date]: First status update

Let me know if you have questions!

Thanks,
[Your Name]
```

### Major Milestone/Release Announcement

```
Subject: [Project Name] – [Milestone] Completed / [Release X.Y] Deployed

Hi team,

I'm pleased to announce that we've [completed milestone / deployed release X.Y] for [Project Name].

**What's Included:**
- [Feature/change 1]
- [Feature/change 2]
- [Feature/change 3]

**Impact:**
- [Customer impact]
- [Internal team impact]

**Documentation:**
- Release Notes: [link]
- User Guide: [link]
- Support Runbook: [link]

**Known Issues:**
- [Issue 1] – Workaround: [details]

**Support & Feedback:**
- Questions? Contact [support channel]
- Feedback? [feedback form/email]

Thank you to everyone who contributed!

[Your Name]
```

---

## Escalation Communication

### When to Escalate
- Project at risk of missing critical deadline
- Major blocker with no clear resolution path
- Scope change requiring additional resources or timeline adjustment
- Cross-team dependency blocking progress
- Security incident or critical production issue

### Escalation Template

```
Subject: ESCALATION: [Project Name] – [Brief Issue Description]

[Escalation Contact],

I'm escalating an issue on [Project Name] that requires your attention.

**Issue:**
[Clear description of the problem]

**Impact:**
- Timeline impact: [delay estimate]
- Scope impact: [what's at risk]
- Business impact: [customer/revenue impact]

**Actions Taken:**
- [Action 1]
- [Action 2]

**What We Need:**
[Specific decision, resource, or intervention needed]

**Timeline:**
Decision needed by [date] to avoid further impact.

I'm available to discuss at your earliest convenience.

Thanks,
[Your Name]
```

---

## Review & Maintenance

### Communication Plan Review Cadence
- **Weekly**: Review with PM during project sync
- **Monthly**: Update stakeholder matrix if roles/involvement changes
- **Per Milestone**: Verify all stakeholders received appropriate updates
- **Retrospective**: Assess communication effectiveness and adjust plan

### Effectiveness Metrics
- Stakeholder satisfaction (survey or informal feedback)
- Response time to escalations
- Number of missed updates or miscommunications
- Meeting attendance rates
- Stakeholder engagement in decision-making

### Continuous Improvement
- Gather feedback during retrospectives
- Adjust communication frequency based on stakeholder feedback
- Simplify channels if too many are causing confusion
- Add stakeholders if new dependencies emerge

---

## Tips for Effective Stakeholder Communication

1. **Be Proactive**: Share updates before stakeholders have to ask
2. **Be Concise**: Busy stakeholders appreciate brevity; use bullets
3. **Be Transparent**: Share risks and challenges early
4. **Be Consistent**: Establish a rhythm and stick to it
5. **Be Responsive**: Acknowledge questions and concerns promptly
6. **Tailor Content**: Executives need different details than individual contributors
7. **Use Visuals**: Charts, roadmaps, and burndowns communicate faster than text
8. **Close the Loop**: Follow up on decisions and action items
9. **Celebrate Wins**: Recognize contributions and share successes
10. **Listen Actively**: Communication is two-way; solicit and act on feedback

---

## Related Documents
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
