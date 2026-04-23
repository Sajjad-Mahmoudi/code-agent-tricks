# Tricky Prompts
### Fix Bug
- This works surprisingly well: Ask Claude Code to fix a bug. Let it work and figure it out.
- When it finishes, use this prompt: "Knowing everything you know now, delete your fix and implement a better|concise|elegant version."
- Claude will use the first pass to explore and learn the problem. Sometimes, this will lead to suboptimal code. The second pass will be better because Claude already knows the problem and can write a better solution.

### From Scratch
- I want to build [ONE-LINE DESCRIPTION].
- Interview me in detail. Cover implementation approach, edge cases, tradeoffs, and constraints. Skip obvious questions. - Ask one at a time and build on my answers.
- When we've covered everything, write the spec to [SPEC FILENAME].
