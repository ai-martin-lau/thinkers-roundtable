# Thinkers Roundtable

A decision-making prompt system that turns one hard decision into a structured debate between 11 different decision lenses.

This is not a chatbot personality pack. It is a way to make an AI model pressure-test your assumptions before you commit time, money, reputation, or attention to a path.

## What It Does

Most AI advice is too agreeable.

Thinkers Roundtable forces disagreement:

- Elon Musk asks what the physical or economic limit really is.
- Charlie Munger asks how this could kill you.
- Nassim Taleb asks whether the downside can wipe you out.
- Naval Ravikant asks whether the path has leverage and whether you actually want it.
- Richard Feynman asks whether you understand it or only know the name.
- Steve Jobs asks what you are willing to remove.
- Andrej Karpathy asks whether it works in demos or in production.
- Paul Graham asks whether you can write the idea clearly and test it with real users.
- Ilya Sutskever asks whether this is real understanding or pattern memory.
- Donald Trump asks what the negotiation really is.
- MrBeast asks whether anyone will notice and whether they will stay.

The system does not make the decision for you. It helps you see:

1. What you are really deciding.
2. Which assumption is weakest.
3. Which risk is hidden.
4. Which first step can be tested this week.

## Why 11 Thinkers

The original internal version had more figures. This public English version intentionally keeps only globally recognizable thinkers for an international X/Twitter and GitHub audience.

China-specific figures were removed to keep the project easier to understand without cultural background.

## How To Use

1. Open a new conversation in Claude, ChatGPT, DeepSeek, or another long-context AI tool.
2. Upload or paste the files in `docs/`.
3. Paste the full master prompt from `docs/01-master-prompt.md`.
4. Describe your decision using `docs/02-question-guide.md`.
5. Let the model run the six-stage roundtable.

For small questions, this is overkill. Use it for decisions where being wrong has a real cost.

## Files

- `docs/00-overview.md` - concept, thinker list, and default seating.
- `docs/01-master-prompt.md` - the full prompt to paste into an AI model.
- `docs/02-question-guide.md` - how to describe your decision well.
- `docs/03-thinker-cards.md` - the 11 decision lenses.
- `docs/04-example-questions.md` - ready-to-copy decision templates.
- `launch/x-launch-post.md` - X/Twitter launch copy.
- `CREDITS.md` - inspiration and attribution.

## Important Note

This project uses public decision frameworks and widely discussed thinking patterns as inspiration. It does not claim to reproduce anyone's private views, exact speech, or endorsement.

Use the named figures as lenses, not as simulated authorities.

## Credits

Inspired by Huashu's Nuwa Skill:

https://github.com/alchaincyf/nuwa-skill

Nuwa showed a powerful direction: distilling how people think into reusable agent skills. This project adapts that idea into a free decision-roundtable prompt system.

## License

MIT. Use it, modify it, remix it, and share it.
