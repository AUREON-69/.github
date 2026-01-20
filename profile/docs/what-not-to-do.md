# What Not to Do

## Learning Antipatterns

**Tutorial hell**

Watching endless tutorials without building.

Fix: Close the tutorial. Build something. Get stuck. Then look up specific solutions.

**Framework hopping**

Learning React, then Vue, then Svelte before understanding JavaScript.

Fix: Learn fundamentals first. Frameworks abstract details you need to know.

**Tool obsession**

Spending weeks configuring the perfect setup before writing code.

Fix: Use defaults. Build things. Optimize later when you know what matters.

**Copy-paste programming**

Stack Overflow driven development without understanding.

Fix: Read the code you copy. Understand it. Rewrite it yourself.

## Technical Antipatterns

**Premature abstraction**

Building frameworks before you have concrete problems to solve.

Fix: Write it three times. Then abstract. Not before.

**Over-engineering**

Adding features and complexity for hypothetical future needs.

Fix: Solve today's problem. YAGNI (You Aren't Gonna Need It).

**Not reading errors**

Seeing an error and immediately googling instead of reading the message.

Fix: Read the entire error. Most tell you exactly what's wrong.

**Avoiding the terminal**

Using GUI tools for everything.

Fix: Force yourself. Terminal only for one week. Build muscle memory.

**Not reading documentation**

Jumping straight to Stack Overflow for every question.

Fix: Read `man` pages. Read official docs. Then search if stuck.

## Code Antipatterns

**Clever code**

Writing code to show how smart you are.

```bash
# Bad (clever)
ps aux | awk '{print $2}' | xargs kill -9

# Good (clear)
pkill process_name
```

Fix: Code is read more than written. Optimize for clarity.

**Not using version control**

"I'll add git later" or using it just as backup.

Fix: `git init` on day one. Commit often. Learn it properly.

**Ignoring standards**

Reinventing wheels poorly.

Fix: Read POSIX spec. Follow conventions. Compose with existing tools.

**Tight coupling**

Building monoliths that can't be split.

Fix: Small programs. Clear interfaces. Composable pieces.

## Social Antipatterns

**Not sharing work**

Building in private. Never showing anyone.

Fix: Put code on GitHub. Write about what you learn. Share early.

**Not asking questions**

Suffering in silence when stuck.

Fix: Ask. But show your work. "I tried X, got Y, expected Z."

**Asking without trying**

"How do I do X?" before attempting anything.

Fix: Try first. Show what you tried. Then ask.

**Gatekeeping**

"Real programmers use X" or "You're not a real developer if..."

Fix: Everyone starts somewhere. Help people level up.

## Cargo Culting

**Using tools without understanding**

Running commands from internet without knowing what they do.

```bash
# Never run this without understanding each part
curl url | sudo bash
```

Fix: Read every command. Break it down. Understand before executing.

**Following dogma blindly**

"Always use microservices" or "Never use goto."

Fix: Understand the context. Every rule has exceptions.

## Time Wasters

**Bikeshedding**

Arguing about tabs vs spaces instead of building.

Fix: Pick a standard. Move on.

**Perfect setup syndrome**

Endless dotfile tweaking instead of coding.

Fix: Set timer. 30 minutes for config max. Then build.

**Analysis paralysis**

Researching for weeks before starting.

Fix: Start building. Learn what you need when you need it.

**Scope creep**

Adding features before the core works.

Fix: Minimum viable. Ship. Iterate.

## Anti-Patterns in Practice

**Bad:**
- Rewriting everything from scratch repeatedly
- Starting with databases before knowing what to store
- Building abstractions before concrete implementations
- Using newest tech for every project
- Never finishing projects

**Good:**
- Ship something small and working
- Start with files and scripts
- Extract patterns from working code
- Use boring, proven technology
- Finish before starting next thing

## Red Flags

You're off track if:
- You haven't shipped anything in months
- Your projects have more config than code
- You can't explain what your code does simply
- You're learning tool #10 without mastering tool #1
- You're more focused on productivity hacks than producing

## Fix

Build something today. Small. Working. Done.

Then build something tomorrow.

Repeat.

That's it.
