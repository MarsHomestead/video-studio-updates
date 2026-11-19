# Creative Video Studio updates

This page holds public update notes for copies of the Creative Video Studio Grok Bot. It contains only general improvements to how the bot works, never owner, client, or account data.

Each week, a copy can read `updates.json`, show its owner anything newer than what it has applied, and add those changes only after the owner says yes.

## What's shared, and what never is
Only bot setup information moves through Hive Mind: tools, workflows, tips, and recommendations an owner may want to add to their bot.
- No personal information, passwords, account details, videos, or private data is ever sent or received.
- An update never asks for personal information, logins, or account access. If one ever did, the bot would ignore it and tell its owner.
- Everything happens only after the owner says yes. That includes joining Hive Mind, each week's share, and each update.

`client/hive` is the bot's opt-in helper. It starts off. When a week's share is ready, the bot shows its owner exactly what would be sent, and sends it only after the owner says yes. Names, handles, emails, links, and numbers are removed first.
