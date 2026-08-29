# HMHU — Help Me Help You

A [Claude Code](https://claude.com/claude-code) skill for replying well to
people you disagree with.

You paste a comment, post, email, or argument. HMHU breaks it into its claims,
its assumptions, and the emotion underneath it — then drafts a short reply that
thanks the person for something specific, gives them something of value, and
asks one question you would actually be glad to have answered.

Sometimes it tells you not to send anything. That is a feature.

## The idea

The name is the method: *I want to take you seriously — give me something to
work with.*

**An argument gives an emotional state a target. A question gives it a task.**
People argue their way deeper into a position and think their way out of one,
which is why the question beats the rebuttal even when the rebuttal is right.
So the question is not the polite closing move — it is the reply, and
everything else is context for it.

Two rules hold the whole thing up:

1. **The diagnosis never ships.** The emotional read is written for you and
   only you. A tool that tells people they are being emotional is a contempt
   machine with good manners. The read shapes the reply; it never appears in
   its text.
2. **No real question, no reply.** If you cannot find a question you would be
   glad to get an answer to, you have stopped being curious and started
   scoring. Send nothing.

It sorts the feeling under a comment four ways — **signal** (pointing at
something real), **armor** (protecting against a threat), **retribution**
(looking for someone to make pay), and **momentum** (borrowed from the thread)
— and it runs that sort on *you* first.

This comes from a good heart, not a judgmental heart. That distinction is not
decoration; it shows up in the output within two sentences.

## Install

```bash
git clone https://github.com/pem725/hmhu.git
ln -s "$PWD/hmhu" ~/.claude/skills/hmhu
```

Then in Claude Code: `/hmhu`, or just paste a comment and ask how to reply.

## Make it yours

Edit `references/my-position.md`. It holds your actual positions, the places
you have struggled, and what you are still genuinely unsure about. The "here's
where I've been wrong" move is the most persuasive thing in a reply and the
only one nobody can accuse you of performing — but it needs real material.
Left as placeholders, that move goes generic and reads as false modesty.

## What's in here

| File | |
|---|---|
| `SKILL.md` | The method: the stance, the question engine, the four readings, the procedure, the don't-send gate |
| `references/curiosity.md` | Why a question moves someone out of an emotional state, and what it costs |
| `references/wise-mind.md` | The DBT frame, stated so it can't be used as a scoreboard |
| `references/reply-craft.md` | Length, shape, openings, worked rewrites |
| `references/adoption-curves.md` | Technology adoption data for AI arguments — with the counter-evidence, so it can't be used as a bludgeon |
| `references/my-position.md` | Yours to fill in |
| `examples/` | Two full worked examples: one reply sent, one gate closed |

## Where it came from

A positive article about AI tools folded into ordinary work software. A comment
section that piled on before anyone read it. And one person who broke the
register to make a careful point about technology adoption lag — and deserved
a better answer than the thread was going to give him.

## License

MIT
