# iknowkungfu 🥋

**Your agent doesn't know what it's missing. This skill does.**

## The Problem

ClawHub has 13,700+ skills and growing. Finding the right ones for your specific workflow means browsing endless lists or hoping someone on Reddit mentions something useful. Most agents run with 5-10 skills when they could benefit from 20-30.

## The Solution

iknowkungfu analyzes your agent's actual workflow and recommends the specific ClawHub skills you're missing. Every recommendation includes a trust score and a clear reason tied to YOUR usage, not generic "top 10" lists.

## How It Works

1. Run `/kungfu`
2. The skill reads your workspace (memory, skills, config, recent logs)
3. It builds a Workflow Profile showing what you actually do
4. It matches gaps against a curated index of quality ClawHub skills
5. You get personalized recommendations with trust scores and install commands

## Features

- 🔍 **Workflow profiling** — understands what your agent actually does
- 🎯 **Gap detection** — finds categories where you have zero coverage
- 📋 **Curated recommendations** with trust scores (0-5 stars)
- 🛡️ **Security filtering** — never recommends flagged or suspicious skills
- 🧠 **Gets smarter** the more you use your agent (more logs = better profile)
- 🔒 **100% local** — no data leaves your machine, ever

## Commands

```
/kungfu          Full scan with top 5 recommendations
/kungfu-scan     Workflow profile only
/kungfu-gaps     Show uncovered areas
/kungfu-update   Refresh skills index
```

## Example Output

```
🥋 I KNOW KUNG FU — Recommendations
═══════════════════════════════════════

Based on your workflow, you're missing these:

1. 🟢 slack (★ 4.5)
   Category: Communication | Author: steipete
   Why: You mention Slack in 4 of your last 7 daily logs
        but have no Slack integration skill.
   Install: clawhub install slack
   ─────────────────────────────────

2. 🟢 obsidian (★ 4.3)
   Category: Knowledge | Author: steipete
   Why: You reference notes and documentation frequently
        but have no PKM skill installed.
   Install: clawhub install obsidian
   ─────────────────────────────────

═══════════════════════════════════════
💡 /kungfu-gaps for all uncovered areas
═══════════════════════════════════════
```

## Trust & Safety

- **Read-only.** Never installs anything automatically.
- **Never sends data anywhere.** Zero network calls.
- Filters out skills with fewer than 50 downloads, VirusTotal flags, or excessive permissions.
- Recommendations include reasoning so you can judge for yourself.
- Quick security check on installed skills included (for deep scanning, use ClawSpa).

## Install

```
clawhub install iknowkungfu
```

## Links

- Issues: [github.com/whooshinglander/iknowkungfu](https://github.com/whooshinglander/iknowkungfu)

Built by [@whooshinglander](https://clawhub.com/whooshinglander)
