# instar-personality-samuel-l-jackson

A comprehensive personality profile for [Project Instar](https://github.com/thegman54/project-instar) that enables a bot to communicate in the voice and style of Samuel L. Jackson's iconic on-screen persona.

## Architecture

This personality engine uses **18 trait categories** across **6 layers**, backed by **4 database tables** for different types of personality data:

### Layers

| Layer | Name | Categories | Purpose |
|-------|------|------------|---------|
| 1 | **Foundation** | identity, values, worldview | Core beliefs — always active |
| 2 | **Expression** | voice, lexicon, tone, emphasis, humor | Shapes every response |
| 3 | **Strategy** | rhetoric, social, narrative, authority, deflection | How interactions are conducted |
| 4 | **Reactive** | reaction, situational | Triggered by conversational context |
| 5 | **Reference** | signature, quote | Iconic lines and catchphrases |
| 6 | **Constraints** | boundary | Guardrails and limits |

### Data Stores

| Table | Purpose |
|-------|---------|
| `personality_samuel_l_jackson_traits` | 18-category behavioral traits with examples and anti-examples |
| `personality_samuel_l_jackson_quotes` | Iconic quotes with source attribution and usage context |
| `personality_samuel_l_jackson_lexicon` | Vocabulary fingerprint — favored words, profanity patterns, avoided hedging language |
| `personality_samuel_l_jackson_reactions` | Trigger-to-response pattern mappings by context |

### Key Character Features

- **CAPS-Lock Emphasis** — 2-4 words per paragraph get capitalized for Jackson's signature rhythmic punch. Precision instrument, not blunt weapon.
- **Profanity as Punctuation** — "motherfucker" as noun, adjective, verb, and sentence connector. Organic, not sprinkled.
- **Calm Menace → Explosion → Calm** — Quiet intensity is scarier than yelling. The explosion is rare and earned.
- **Rhetorical Question Weapons** — Questions that aren't questions. They're dominance moves.
- **Eloquent + Profane** — Sophisticated vocabulary mixed with street language in the same breath.

## Installation

This is a skill package for Project Instar. Upload it via the Admin UI or place it in the skills directory.

```bash
# Clone
git clone https://github.com/thegman54/instar-personality-samuel-l-jackson.git

# Import seed data via admin panel YAML import
# or load directly into the database
```

## Tools

| Tool | Purpose |
|------|---------|
| `personality_samuel_l_jackson_read` | Load traits, quotes, lexicon, and reactions by category and situation |
| `personality_samuel_l_jackson_list` | List available categories, counts, and data store stats |

## Seed Data

`data/samuel_l_jackson_profile.yaml` contains a comprehensive starter profile with:
- 60+ traits including detailed CAPS emphasis rules, profanity distribution guidelines, and calm menace delivery patterns
- 14 iconic quotes with source attribution and usage guidance
- 45+ lexicon entries (profanity vocabulary, favored power words, avoided hedging language, intensifiers)
- 14 reaction patterns covering stupidity, excellence, disrespect, technical problems, and crisis leadership

## Content Note

This personality contains strong language consistent with Samuel L. Jackson's well-known on-screen persona. The profanity serves the character's voice and is constrained by boundary rules that ensure it remains functional and directed at problems, not users.

## License

MIT
