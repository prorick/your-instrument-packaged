# Your show-and-tell slide — made with your Claude, in one pass

*This is a set of steps written to be handed to Claude. Answer the four
questions below (one or two honest sentences each — rough edges are the
point), then in Claude Code — already open from the main steps — say:
**"Read show-and-tell/CLAUDE-STEPS.md and build this."** (Claude Code,
not the claude.ai website: the website can't write files to your repo.)*

## My four answers (fill these in first)

1. **What it is** — what does my instrument do?
   > My instrument goes through my gmail to find events for me! It finds homework deadlines, and events. It also notes if an event has free food. 

2. **The idea behind it** — how does it help me think better with AI?
   > It helpes me think better with AI as it allows me to find events that might have slipped through my inbox.

3. **One wrong thing + one fix** — what broke, and what I did about it:
   > One thing that didn't work was that Claude said my tracker was empty and stopped. Now list_tasks tells it to load inbox-radar and scan Gmail. A tool’s output steers what the model does next.

4. **What feedback I want** — the question I'm ending my show with:
   > How can I further improve my instrument? Is there any use case that you think I should also include? 

## Claude: your instructions

Build a SINGLE self-contained HTML file at `show-and-tell/slide.html` in
this repository:

- One screen, no scrolling at laptop/projector resolution (1280×720 up).
  It is ONE slide, not a deck.
- The four answers above are the content, in that order; the fourth one
  ("what feedback I want") is the visual climax — biggest treatment, it
  is the question the room answers.
- Big type, high contrast, readable from the back of a classroom.
- Self-contained: inline CSS, no external scripts, no build step, works
  from a `file://` open and when pushed to GitHub.
- Style is the author's call — ask them for two or three preferences
  (a color they like, serious vs. playful) before writing, then commit
  the file with a clear message.
- Do not invent content: if an answer above is blank, ask for it instead
  of writing one.

Open it when done (`open show-and-tell/slide.html` on macOS;
`explorer.exe show-and-tell/slide.html` on Windows/WSL; `xdg-open` on
Linux) so the author sees it immediately.
