# Language launch · omnigami

Your product now speaks more languages. Show it.

A 14-second announcement on your real screens. The headline says your product now speaks, each language rolls in by its own name as a carousel of your real screen swipes to its phone, one at a time, each held long enough to read. Then every phone flies into one row under the count, and your end card.

Watch it play live, and change its words, at [omnigami.ai/skills/language-launch](https://omnigami.ai/skills/language-launch).

## Install

In Claude Code:

```
/plugin marketplace add omnigami-ai/skills
/plugin install omnigami-language-launch@omnigami
```

With the skills CLI, for Claude Code and other agents that read SKILL.md:

```bash
npx skills add omnigami-ai/language-launch
```

Or copy `skills/language-launch/` into your agent's skills folder (for Claude Code, `~/.claude/skills/language-launch/`). Then ask:

```
Make a language launch video for https://your-product.com
```

## What it runs

The skill works on your computer. It runs the Node scripts in `skills/language-launch/scripts/`: they open your product's pages in a local headless browser to capture its real screens, then render the film with that browser and ffmpeg, writing MP4s and an editable HTML film to your project. It sends nothing to omnigami or anyone else, and uses no network beyond loading your own product's pages and the fonts and assets in this folder.

## You need

- Claude Code with Opus 5.5
- Node 20 or later
- ffmpeg
- Chrome, Chromium, Edge or Brave

None beyond your Claude plan’s usage. Node, ffmpeg and the browser are free.

## Licence

Free to use. Use the films and anything else the skill makes for anything, commercial work included. Don't redistribute the skill. See [LICENSE.md](LICENSE.md). The bundled fonts keep their own licence (SIL Open Font License, beside them in `reference/assets/fonts/`).

## Credits

Its motion is omnigami’s own. Its example shows Fernwise, a fictional company made for omnigami’s examples, with sample data.

omnigami is not affiliated with Anthropic. More skills at [omnigami.ai](https://omnigami.ai).
