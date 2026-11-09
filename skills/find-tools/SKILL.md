---
name: find-tools
description: Find and assess existing internal or external tools, reusable components, libraries, services, workflows, and AI skills. Use when the user asks for tools or skills, when choosing a stack, framework or library that agents will build with, or before choosing how to handle unfamiliar, specialized, or recurring work. Skip routine execution with an already chosen tool.
license: MIT
---

# There's a Tool for That

Assume a reusable solution may already exist, and search past what you remember. Pick the option that saves the most total work, even if it covers only part of the job.

## Check what exists

Work out the outcome, what makes it hard, and the constraints. Ask only for information that would change the search.

Start with what is already here: installed tools and skills, platform features, project dependencies and code, shared components, earlier internal solutions. Check whether they work in this setup, reuse what fits, and search only for the gaps. If something already meets the need, stop. Keep private details out of public queries.

For adoption, replacement or build decisions, establish how people solve this problem before narrowing the candidates. Read practitioner comparisons, discussions and accounts of real work. Identify recurring approaches, widely used options, who uses them and the reported benefits and costs. Follow their references and search with the terms you learn. Match the depth to the decision; routine lookups can stay brief.

## Search past the first results

Search for the outcome and the specific gap, phrased a few ways. Look across registries, communities, comparisons, integrations and repositories. A component or reusable instruction can replace part of the work without replacing the system.

For AI skills, resolve Vercel's `find-skills` (`vercel-labs/skills`) through the host's catalog or installed skills. **Read its `SKILL.md` and execute its discovery procedure**, including catalog/leaderboard checks and keyword searches. A CLI invocation or GitHub search alone is incomplete. Use the assessment criteria here rather than fixed popularity cutoffs.

If the companion is unavailable, use [skills.sh](https://skills.sh/): check established and trending skills, search relevant terms, and read actual entries before their repositories. Do not install the companion just for discovery. Catalogs complement practitioner research.

A failed page load leaves that step unfinished. Try another permitted route or source serving the same purpose; report remaining gaps.

If results are thin, follow references and alternatives beyond the first catalog or familiar vendor.

## Read the source

Read promising candidates' original docs or code; for skills, their `SKILL.md` and dependencies. Trace relevant workflows before making system-wide capability claims; state the inspected scope when coverage is partial. Check versions and dates. Listings and snippets are leads. Trace repeated claims to distinguish independent experience from copies of one announcement.

Compare fit, compatibility, access, cost, permissions, licensing, data handling and maintenance with the work saved. Use firsthand reports and comparisons to understand successful use as well as failures. Keep publisher claims, user experience and your observations distinct; apply the same evidentiary standard to established and niche candidates.

Broad adoption and recurring independent reports warrant investigation and increase confidence in practical maturity. State what a count measures: repository stars, downloads, skill installs or active users are different. Weigh the combined pattern against the specific task; neither one complaint nor one impressive README settles it. Investigate contradictions and explain any choice of a less-established option over a relevant widely used one. Keep specialist options eligible, with uncertainty and a small trial where needed.

## Choose

Compare serious candidates with what you already have and the smallest custom solution. Prefer benefits that outweigh switching costs.

Before recommending, make the comparison account for recurring approaches and adoption signals, real usage conditions, and capability evidence. Explain how these affected the shortlist and choice. Check actual tool results against applicable discovery steps, including the companion's; visiting pages alone is insufficient. If the practical context is still missing, continue discovery or label the result provisional at the agreed limit. Before concluding nothing fits, try newly learned terms and another search route.

Before ranking candidates within a layer, check whether skill demand has moved to a different kind of component that makes the layer unnecessary. If it has, decide at that level, and say so when the brief named only the old layer's candidates; "Express, Fastify or Hono, your call" does not create the need for an API server. Example: those three at 3.1K, 93.5K and 17K installs read as a choice of HTTP framework. The demand sits on platforms: Supabase 478K and 360K, Prisma 418K, Convex 136K, Better Auth 131K. The decision is which platform the frontend's server functions call. A hand-written API server is a layer agents are no longer being equipped for, and "which framework" is the question the training data has the most examples of.

When the candidates are stacks, frameworks or libraries that agents will build with, list two numbers for each, side by side: skill demand (skills.sh installs of its best skill, that skill's publisher and repo stars, whether current scaffolders default to it) and repository stars. Installs show how many agent setups are being equipped for the option now; stars and training-data familiarity show what was common before, and familiarity is why the older option feels safe. Adopt the most-demanded modern option. A low install count marks a legacy option whatever its stars. The exception is evidence of newness: a 1.0 this year, a top write-in in the latest State of JS or its equivalent, a scaffolder default. Installs of a personal skill repo do not promote its stack; demand counts when the skill comes from the project's own organization or a widely adopted repo. A small project, a single user, a deadline or a brief that says "keep it simple" or "something like X" never justifies the older option: recommend the demanded one and say in one line what the older would have cost. A constraint stated in the brief (no hosted services, must run offline) removes a candidate; a tradeoff you raise yourself, such as vendor dependence, goes next to the numbers and does not override them. Name both numbers for the chosen option and for the default it displaces.

Report the choice, tradeoffs and supporting sources, including what practitioner evidence established and what remains unverified. Proceed within the task's authority; use the host's manager for skill installation.
