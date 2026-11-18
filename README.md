# The Dreaded To-Doodle

A planning skill for the task you keep finding creative reasons to avoid. Give it your list and the time you have. It helps you choose what deserves attention and decide what finishing looks like.

Use a pasted task list or describe your situation in conversation. The skill works without accounts or integrations.

## What it does

- Compares tasks by consequences, deadlines, and contribution to your goals.
- Recommends one important, actionable task and explains the choice.
- Defines a concrete first action, completion criteria, and a realistic focus period.
- Handles blocked tasks, interruptions, and commitments that exceed available time.
- Suggests what to defer, delegate, or stop while preserving your authority over those decisions.

## Install in Codex

Clone this repository, or download and extract its ZIP from GitHub's **Code** menu. Copy the inner `dreaded-to-doodle` folder into your personal Codex skills directory:

```text
Windows:      C:\Users\YOUR-USERNAME\.codex\skills\dreaded-to-doodle\SKILL.md
macOS/Linux:  ~/.codex/skills/dreaded-to-doodle/SKILL.md
```

For a custom `CODEX_HOME`, use its `skills` directory. Start a new Codex chat after installation. Preserve personal changes if replacing an existing installation.

## Try it

```text
Use $dreaded-to-doodle to plan my next two hours.

My tasks:
- Finish a client proposal due at noon; about 45 minutes.
- Reply to routine messages; about 30 minutes.
- Redesign optional presentation slides; about one hour.

Choose what I should tackle first, explain why, and give me the first action,
completion criteria, and what to defer.
```

You can also ask for help with a stalled project, competing deadlines, or reviewing progress. The skill adapts to your role, available time, and operational responsibilities.

## Files

| File | Purpose |
| --- | --- |
| [SKILL.md](dreaded-to-doodle/SKILL.md) | Planning workflow and decision rules |
| [Examples](dreaded-to-doodle/references/examples.md) | Fictional office, operations, and personal planning scenarios |
| [Codex metadata](dreaded-to-doodle/agents/openai.yaml) | Display name and starter prompt |
| [Installation guide](INSTALL.md) | Setup, usage, and notes for other AI assistants |

The skill recommends priorities. It does not grant permission to send messages, modify calendars, reassign tasks, or access restricted systems. Recommendations should be checked against current facts and responsibilities.

## Compatibility and validation

This package uses Codex's skill format. You can give the Markdown instructions to another assistant through its supported instruction mechanism; installation and automatic invocation there have not been tested.

Version 1.1.1. The skill format and ZIP contents have been checked. The examples describe intended behavior. Review the assistant's recommendations against your actual responsibilities and deadlines.

## License

The instructions and fictional examples are available under the [MIT License](LICENSE).
