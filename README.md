# Everdust skills

[![skills.sh](https://skills.sh/b/Everdustapp/everdust-skills)](https://skills.sh/Everdustapp/everdust-skills)

Agent skills from [Everdust](https://everdust.ai), the free particle universe simulator with a real Night Sky. They work
with Claude Code, Codex, Cursor and other agents that read `SKILL.md` files.

```bash
npx skills add Everdustapp/everdust-skills
```

## Skills

| Skill | What it does |
|---|---|
| [everdust-night-sky](skills/everdust-night-sky/SKILL.md) | Answers "what's up tonight?", "when is the next meteor shower?", "where is the Orion Nebula and how do I see it?" and eclipse questions from Everdust's free sky guide and atlas at [everdust.ai/sky](https://everdust.ai/sky) and [everdust.ai/atlas](https://everdust.ai/atlas). Gives times and directions for New York, Los Angeles, London and Sydney, latitude and season guidance for anywhere else, realistic meteor counts with the Moon counted, and a link to the page each fact came from. |

## What the skill uses

Public pages on everdust.ai only. No API key, no account, nothing sent about the user. The pages are rendered on the
server and refresh every hour (tonight and object pages) or every six hours (the meteor and eclipse calendars), using
[Astronomy Engine](https://github.com/cosinekitty/astronomy) for positions and the International Meteor
Organization's working list for showers.

## License

The skill text in this repository is MIT licensed (see [LICENSE](LICENSE)). The content of everdust.ai, including its
photographs, keeps its own licences and credits, which each page lists.

Made by Decosa, Inc. Questions or fixes: hello@everdust.ai, or open an issue.
