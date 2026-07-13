# Inbox — Referral Central Prototype

Interactive mockup exploring how referral-related conversations work in the Referral Central inbox when multiple applicants message on the same referral.

**▶️ Live demo:** https://viveknandoskar-des.github.io/inbox/

## What's inside

One conversation per referral (a "room"), with two ways to switch between applicant threads:

- **Option 1 — a 2nd nav:** the referral opens with its own mini-list (all applicants plus a read-only "Referral updates" feed); pick a person to see that thread.
- **Option 2 — chips at top:** all applicants sit as chips above the chat; switch with one click.

## Things to try

- **⚡ Stress test toggle** — jumps the referral from 3 applicants to 18. Option 2 breaks at scale (the chip wall); Option 1 stays usable at any count.
- **🔔 Referral updates** — the referral's own read-only feed for general notifications (new applicant, applicant count, and agreement signing), separate from person threads.
- **👤 Profile** — applicant details are hidden by default; the button in the header reveals them.
- **General tab** — plain 1:1 conversations not tied to any referral, for contrast.

## Run locally

Open `index.html` in any browser — no build, no dependencies.

---

Made with [Claude Code](https://claude.com/claude-code) · design exploration by Vivek Nandoskar
