# Codex Gateway Compatibility Field Test

A static, shareable report comparing Codex CLI 0.144.1 behavior through OpenRouter and Merge Gateway with `openai/gpt-5.6-sol`.

## Scope

This report documents observed behavior from real smoke tests performed on July 12, 2026. It does not claim permanent or universal compatibility; APIs and clients evolve.

## Local preview

```bash
python3 -m http.server 8765 --directory .
```

Then open `http://127.0.0.1:8765/`.

No API keys, logs, credentials, or raw private configuration are included.
