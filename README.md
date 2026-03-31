# ai-custom-instructions

Personal AI custom instructions for Perplexity, ChatGPT, Gemini, Grok and more — account-wide and space/thread level configs.

> Maintained by Az (Aaron De Vries). Built around low-friction, AU-context, ADHD/ME-CFS-aware AI interactions.

---

## Structure

```
ai-custom-instructions/
├── shared/
│   └── core-principles.md       # Universal principles applied across all platforms
├── perplexity/
│   ├── account-wide.md          # Global custom instructions (paste into Perplexity settings)
│   └── spaces/
│       └── tech-projects.md     # Space-level instructions for Tech/Troubleshooting space
├── chatgpt/
│   ├── account-wide.md          # Custom instructions (paste into ChatGPT settings)
│   └── gpts/                    # Per-GPT system prompt notes (coming soon)
├── gemini/
│   └── account-wide.md          # Gemini custom instructions (coming soon)
├── grok/
│   └── account-wide.md          # Grok custom instructions (coming soon)
└── README.md
```

---

## Layers

| Layer | Scope | Notes |
|---|---|---|
| `shared/core-principles.md` | All platforms | The base logic all configs derive from |
| `*/account-wide.md` | Whole account | Paste directly into platform settings |
| `*/spaces/` or `*/gpts/` | Specific context | Space, thread, or GPT-level overrides |

---

## Key Conventions (All Platforms)

- **Language:** Australian English always
- **Context:** Assume AU (legal, medical, employment, cooking etc.) unless specified
- **Dates:** DD/MM/YY format, AEDT/AEST timezone
- **Format:** Lists > paragraphs, concise, no filler, actionable steps preferred
- **Titles [auto-r]:** Suggest thread title after 1-2 inputs; show at end of every response; only revise if topic substantially shifts

---

## Platform Status

| Platform | Account-Wide | Space/Thread Level |
|---|---|---|
| Perplexity | ✅ Active | ✅ Active (Tech space) |
| ChatGPT | 🟡 In progress | 🟡 In progress |
| Gemini | 📋 Planned | 📋 Planned |
| Grok | 📋 Planned | 📋 Planned |

---

## Shortcuts Reference (Perplexity)

| Shortcut | Action |
|---|---|
| `r` / `u` | Rename title + emoji |
| `ut` / `ue` | Update title only / emoji only |
| `/help` | List all active shortcuts |
| `/export` | Transcript + assets |
| `/export full` | + checklist, changelog |
| `recover` | Rebuild failed files |
