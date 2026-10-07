# Mission: translate *The Quiet Morning* into Kesh

**Kesh** is a constructed language produced by the `conlang` toolkit — a seeded base (inventory and syllable shapes) generated and then deliberately extended. This project translates the fixed 111-sentence English story *The Quiet Morning* into Kesh.

## Success measures

- All **111 sentences** translated in `the_quiet_morning_kesh.csv` (`index,english,kesh`).
- Every form legal under Kesh's inventory and phonotactics; untranslatable items quarantined as `[slot]`.

## Sources of truth

- The model `out/kesh.json`; the frozen spec `spec/kesh.yaml`.
- The toolkit — the `conlang` package.
