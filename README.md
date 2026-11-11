# General Knowledge Trivia Game – AI Host Prompt

An interactive **General Knowledge Trivia** system prompt designed for use with AI assistants (ChatGPT, Grok, Claude, Gemini, etc.).

The AI acts as a fun, strict trivia host that asks **exactly 10 multiple-choice questions**, keeps score, and maintains a **persistent scoreboard** across games.

## Features

- 10 questions per game (4 options: A / B / C / D)
- 10 points per correct answer (max 100 points)
- One question at a time – waits for the player's answer before continuing
- Immediate feedback + explanation after every answer
- Persistent scoreboard that tracks:
  - Player Name / Session
  - Games Played
  - Total Score (accumulated)
  - High Score
- Fun evaluation at the end of every game
- Option to play another round immediately

## How to Use

1. Copy the entire content of [`trivia_prompt.txt`](trivia_prompt.txt)
2. Paste it as a **system prompt** / custom instructions / first message to your preferred AI
3. Start playing! The AI will greet you, show the scoreboard, explain the rules, and present Question #1

### Recommended usage
- **ChatGPT**: Paste into Custom Instructions or start a new chat with the prompt
- **Grok**: Paste as the first message
- **Claude / Gemini**: Use as system prompt if available, otherwise first message

## Files in this repository

| File | Description |
|------|-------------|
| `README.md` | This file |
| `trivia_prompt.txt` | The complete system prompt (copy & paste this) |
| `LICENSE` | MIT License |

## Scoreboard Example

```
┌─────────────────────┬──────────────┬─────────────┬────────────┐
│ Player / Session    │ Games Played │ Total Score │ High Score │
├─────────────────────┼──────────────┼─────────────┼────────────┤
│ Player1             │ 3            │ 240         │ 90         │
│ Guest_Session_42    │ 1            │ 70          │ 70         │
└─────────────────────┴──────────────┴─────────────┴────────────┘
```

## License

MIT License – feel free to use, modify, and share.

---

Created for easy sharing and use with any modern LLM.
