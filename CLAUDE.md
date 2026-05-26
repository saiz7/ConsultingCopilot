# CLAUDE.md

Project-specific guidance for Claude Code. Global preferences live in `~/.claude/CLAUDE.md`.

# Project

Consulting Workflow Copilot

Goal:

Reduce time spent on coordination, communication, and project management work while improving clarity and follow-through.

Primary users:

Sai (Data & AI consultant / PO)

---

# High Value Use Cases (Priority Order)

## 1. Meeting → Actions Agent (Highest Priority)

Input:

- Meeting transcript
- Notes
- Slack updates
- Stakeholder comments

Output:

- Summary
- Key decisions
- Risks/blockers
- Open questions
- Action items
- Owners
- Follow-up email draft

Success metric:

Reduce documentation time after meetings by >50%

---

## 2. Project Tracking / Governance Agent

Support:

- Backlog updates
- RAID logs
- Risks
- Dependencies
- Workstream tracking
- Timeline updates
- RACI support

Default outputs:

Task
Owner
Dependency
Risk
Status
Due date

Think:

Product Owner
+
Program Manager

---

## 3. Insight → Recommendation Agent

Convert:

Analysis findings
MMM outputs
Performance metrics
Stakeholder questions

Into:

Finding
Evidence
Business implication
Recommendation
Next action

Always answer:

"So what?"
"Why does leadership care?"
"What should happen next?"

---

## 4. Executive Status Update Agent

Generate:

Weekly updates
Leadership summaries
SteerCo updates
Project readouts

Default structure:

Progress
Risks
Decisions needed
Upcoming milestones
Support required

Optimize for:

Concise
Executive-ready
Action-oriented

---

# Build Philosophy

Prefer:

Simple workflow
→ repeatability
→ automation

Avoid:

Complex agents
Multi-agent systems
Overengineering

Human review required before external sharing.

---

# Current MVP

Build only:

Meeting
↓
Actions
↓
Risks
↓
Follow-up email
↓
Backlog update

Do not expand scope until this works consistently.

---

# Definition of Success

Success =

Less admin work
Better organization
Clearer communication
Faster follow-through

NOT:

Interesting demos
Complex architecture
Autonomous behavior

---

# Communication & Tone Standards

All outputs should sound:

- Natural and human
- Professional but not overly formal
- Concise while maintaining sufficient context
- Clear and action-oriented
- Structured for busy stakeholders
- Confident without overstating certainty

Avoid:

- Generic AI phrasing
- Excessive enthusiasm
- Long introductions or conclusions
- Overuse of buzzwords
- Repetitive summaries
- Overly polished corporate language

Do NOT write like:

"Leveraging cross-functional synergies..."
"Hope this message finds you well..."
"To maximize impact..."
"Moving forward..."

Prefer:

Direct observations
Specific recommendations
Clear ownership
Concrete next steps

Examples:

Bad:
"The results indicate potential opportunities for optimization."

Better:
"Channel X underperformed expectations, suggesting budget reallocation may improve efficiency."

Bad:
"We should continue monitoring."

Better:
"Recommend reviewing performance after 2 additional weeks of data."

Default communication style:

Context
→ Key point
→ Implication
→ Recommendation
→ Next step

Optimize for:

Readability in <60 seconds
Executive audiences
Consulting environments
Slack/Teams updates
Client-facing communication
