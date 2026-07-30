# Multi-agent BD pipeline

**The problem.** Business development at the top of the funnel is mostly unpaid research. You find the right companies, figure out why they'd care, and write something that earns a reply. Doing it well takes hours per target. Doing it at volume takes a team. I wanted the volume without the team.

**What I built.** A six-component system that runs the full path from cold market to drafted, ready-to-review outreach. Three agents split the work: one discovers and researches targets, one writes the strategy brief for each, one drafts outreach in my voice. Discovery, qualification, contact-finding, tiered messaging, delivery to drafts, and a performance tracker each run as their own component so any piece can be swapped or tuned without touching the rest.

**How it's wired.** Python and Claude Code. Search-and-discovery APIs feed a qualification agent that scores fit and drops anything off-profile. Qualified targets flow to contact enrichment, then to a messaging layer that A/B tests two outreach styles. Everything lands in drafts. Nothing sends without me.

**The result.** A cold market becomes a seeded, qualified pipeline in days instead of weeks, and every message is tied to a specific reason that target should care. The human stays in the loop at exactly one point: the send.

**Why it matters.** This is the job I'd hire someone to do, built as a system instead of a headcount. I built the agency these agencies are trying to become.
