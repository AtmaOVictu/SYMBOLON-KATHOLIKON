# The empty wordlist — your dictionary becomes your judge

Fill one row per word. Your judge is your source; the verdict is yours.

## Fields

- **word** — the headword, exactly as in your source
- **mark** — ⊢ (you hold a verbatim citation) or ⚠ (open, with a measured reason)
- **source** — where the citation lives (dictionary, edition, page or URL)
- **gloss** — the verbatim citation: copy it exactly; a paraphrase is a fall
- **access** — when you read the source (a datum of measurement, not a promise)

## Template

```json
{
  "meta": { "name": "your-wordlist", "language": "…", "sealed": "…" },
  "entries": [
    { "word": "…", "mark": "⊢", "source": "…", "gloss": "…verbatim…", "access": "…" },
    { "word": "…", "mark": "⚠", "source": null, "gloss": "…measured reason it stays open…", "access": "…" }
  ]
}
```

## Four rules

1. **Entry before utterance.** A word used as measured must carry a verbatim citation — or it stays ⚠. Unverified is not forbidden; unverified is marked.
2. **Two hands.** Never seal your own verification; a claim needs an independent witness.
3. **Named falls, scarred corrections.** Falls are recorded with their names; corrections keep the scar.
4. **Your judge is your source.** The verdict is yours — not ours, not a model's.
