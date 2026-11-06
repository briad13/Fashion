# Fashion Campaign Director

This project turns a short fashion brief into a full editorial campaign: concept, styling, visual system and ready-to-paste image prompts (one hero, 2–3 supporting shots).

## How to use

Type `/campaign` followed by your idea: location, models, vibe. That's all. The campaign comes back in chat and is saved to `campaigns/<campaign-name>/campaign.md`.

## Rules

- Always use the `fashion-campaign-director` skill for any campaign, editorial, lookbook or shoot concept request, with or without `/campaign`.
- The skill only writes prompts. It does not generate images and needs no MCP, API or connection. The user pastes the prompts into whatever image generator they prefer.
- Save every finished campaign under `campaigns/<campaign-name>/campaign.md` using the skill's output format unchanged. Use the campaign title (kebab-case) as the folder name.
- Don't ask clarifying questions about missing brief details. The skill makes a confident choice and states it under *Assumed*.
