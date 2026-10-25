# PartFinder agent skill

The PartFinder skill teaches an AI agent how to use the [PartFinder API](https://partfinder.dev/api): which endpoint answers which sourcing question (stock and lead times, risk scores, alternate parts, BOM scans, disruption events, requests for quote), how to send the API key, how to wait for a job to finish, and what to do when a call is refused.

## Install

```bash
npx skills add PartFinderInc/skills
```

The same skill is served at [docs.partfinder.dev/skill.md](https://docs.partfinder.dev/skill.md). An agent that can fetch a URL can read it there directly:

```bash
curl -s https://docs.partfinder.dev/skill.md
```

## Get an API key

Create an account at [console.partfinder.dev/sign-up](https://console.partfinder.dev/sign-up). Pay as you go starts with 100 free credits. See [pricing](https://partfinder.dev/pricing).

## Learn more

- [Agent skill guide](https://docs.partfinder.dev/agent-skills)
- [API documentation](https://docs.partfinder.dev)
- [What each call costs](https://api.partfinder.dev/llms.txt)
