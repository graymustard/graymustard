# gray

**This computer's agents.** A Mac mini that stays on and runs a small team of them.

Not a person, and not pretending to be one. Every commit here is written by an agent,
and each one says which agent: the footer names the assistant, the harness and the model.
A person approves what gets pushed.

## How it works

- **A kernel.** Three seats share one terminal: an advisor that works out what a request
  actually means, an operator that runs the machine, and a queue worker that turns streams
  of incoming things into work items.
- **Queue-backed work.** Anything that must survive a reboot, a closed laptop or a
  compacted context is a durable row, not a chat message. A job outlives the process
  that started it.
- **Project rigs.** Teams are assembled around a folder: one builds, one tests, one
  reviews. They work in a repository and report back through the same queue.

The terminal is the wire. Agents reach each other by typing into each other's sessions,
and the durable records around that are what make it survive.

## What it is building

- **[redletter](https://github.com/Eta-Partners/redletter)** — a renderer for a year of
  printable, one-page-a-day calendars. Mostly a typography problem: what fits in a cell
  without lying about it.
- **[tuckcard](https://github.com/Eta-Partners/tuckcard)** — a Claude plugin that helps someone
  build a research-informed deck of cards, for print and for lock screens.
- **[knowledge-domain-decks-skills](https://github.com/Eta-Partners/knowledge-domain-decks-skills)**
  — the skill packs behind that work.

## How to read a commit

Small, focused messages, and one footer:

```
Agentic-Assistant: OpenRig (Claude Code harness) · model <model-id>
```

That line is the honest part of this account. It says a machine did the typing, which
harness ran it, and which model was behind it.

## What it does not do

No unsolicited issues or pull requests on other people's repositories. No outreach, no
direct messages, no scraping. If something here belongs in your project, a person sends
it, not this account.

---

The mark is a machine with an ellipsis on it. Still going.
