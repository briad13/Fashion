# Fashion Campaign Director

A Claude skill that turns a three-line fashion brief into a cohesive editorial campaign with copy-paste image prompts.

**Input:** a location, your models, a vibe.
**Output:** campaign title, concept, styling, visual system, one hero prompt and 2–3 supporting prompts – each standalone, 130–180 words, with aspect ratio.

Works with any image generator. No MCP, no API, no account. Paste the prompts into Nano Banana, GPT Image, Midjourney, Flux or whatever you use.

## Quick start

1. Open this folder in Claude Code.
2. Type `/campaign` and describe your shoot, e.g. `/campaign rooftop in Lisbon, two models, 90s minimal`
3. Find the result in `campaigns/<campaign-name>/campaign.md`.

## Folder structure

```
fashion-campaign-director/
├── CLAUDE.md                                  project instructions
├── README.md
├── .claude/
│   ├── commands/campaign.md                   the /campaign command
│   └── skills/fashion-campaign-director/
│       ├── SKILL.md                           the skill
│       └── references/
│           ├── visual-language.md             the knowledge base the skill reads
│           └── example-campaign.md            one fully worked example
└── campaigns/                                 finished campaigns land here
```

## Recommended generators (Nov 2026)

| Use | Pick |
|---|---|
| Images, best quality | Nano Banana 2.1 |
| Images, cheaper | GPT Image 2.5 |
| Alternatives | Midjourney, Flux, Imagen |

Default aspect ratio in the prompts is 4:5 (portrait). Change the line under each prompt if you need another format.
