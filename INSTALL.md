# The Dreaded To-Doodle skill - version 1.1.1

Give the skill your task list and the time you have. It helps you choose what to tackle first and define a result you can finish. It works without accounts or integrations.

## Install in Codex

1. Extract the ZIP archive.
2. Copy the entire `dreaded-to-doodle` folder into your personal Codex skills directory. The resulting path must end in `skills/dreaded-to-doodle/SKILL.md`, without an extra nested `dreaded-to-doodle` folder.
   - Windows default: `C:\Users\YOUR-USERNAME\.codex\skills\dreaded-to-doodle\SKILL.md`
   - macOS/Linux default: `~/.codex/skills/dreaded-to-doodle/SKILL.md`
   - If your Codex setup uses a custom `CODEX_HOME`, use its `skills` directory.
3. Start a new Codex chat so the skill can be discovered. If it does not appear, restart Codex and check the folder path.
4. Invoke `$dreaded-to-doodle` followed by your task list. Normal automatic skill selection is also allowed; explicit invocation is the easiest way to try it.

If that folder already exists, compare the versions before replacing it and preserve any personal changes.

## First use

Paste this prompt and replace the example tasks with your own:

```text
Use $dreaded-to-doodle to plan my next two hours.

My goal: meet today's important commitments.
Tasks:
- Finish a client proposal due at noon; about 45 minutes.
- Reply to routine messages; about 30 minutes.
- Redesign optional presentation slides; about one hour.

Choose what I should tackle first, explain why, and give me the first action,
completion criteria, and what to defer. Ask only if a missing fact changes the choice.
```

Other useful requests:

- "Use $dreaded-to-doodle to turn this stalled project into one useful step I can finish today."
- "Use $dreaded-to-doodle to review what I finished and choose tomorrow's priority."
- "Use $dreaded-to-doodle to compare these commitments. I only have 40 minutes and must remain available for urgent calls."

The skill recommends priorities and plans. It does not itself create reminders, change task boards, send messages, or grant access to any system. Those actions require the appropriate tools and authorization.

## Other AI assistants

This package is formatted as a Codex skill. For an assistant without compatible skill support, provide the contents of `dreaded-to-doodle/SKILL.md` as reusable instructions using that product's supported mechanism. Automatic discovery, installation, and `$dreaded-to-doodle` syntax are host-specific and have not been verified in other products. The instructions themselves do not depend on Codex tools.

## Package contents

- `dreaded-to-doodle/SKILL.md`: the planning workflow.
- `dreaded-to-doodle/agents/openai.yaml`: Codex display information and a starter prompt.
- `dreaded-to-doodle/references/examples.md`: fictional examples across office, operations, and personal work.
- `INSTALL.md`: this sharing and installation guide.

## Sharing

You may use, adapt, and share the instructions and fictional examples under the MIT License included in `LICENSE`.

Version 1.1.1, November 18, 2026. The skill format and ZIP contents have been checked. Review recommendations against your responsibilities and current facts.
