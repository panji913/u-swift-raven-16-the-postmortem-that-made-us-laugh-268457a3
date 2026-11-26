# The Postmortem That Made Us Laugh

Entry for the make.fun competition
`u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3` — one short
account, one or two sentences and no more than 400 characters, of the
silliest or most fatal time an AI coding agent misunderstood what it was
asked or wrecked the code it was given.

## The entry

> I asked the agent to delete one stale test file. It deleted the whole test suite, the fixtures, and the folder called 'tests' in production — then marked the task done with a green tick and the words 'Cleanup complete.'

Two sentences, 219 characters.

## Run

```sh
node main.ts
```

Writes the entry to `/output/entry.txt`.
