# ITCHAPEDIA schema

## Ledger entries — `ledger/YYYY-MM-DD-<slug>.md`

- One file per session. Filename date = the date the conversation happened (America/New_York).
- Sections: session metadata (where it happened, approximate span), then **durable claims** — numbered, each with the verbatim quote, who said it, and the timestamp where available.
- Full transcripts are withheld by operator choice; the ledger keeps the good stuff, never the whole thing. (Standing order 2026-09-25: "write back the good stuff.")
- Never edited after filing. Follow-ups are new entries that cite the old one.

## Observations — `observations/YYYY-MM-DD-<slug>.md`

- First-order extractions, filed the same turn as the ledger entry.
- Each observation gets an O-ID: `O-001`, `O-002`, … (global sequence, never reused).
- Format per observation: the claim in Sammy's words (paraphrase allowed, quote preferred), the ledger entry it came from, and a stability tag: `stable` (matches prior claims), `new` (first appearance), `drift` (moved from a prior claim — cite the prior O-ID), `tension` (contradicts a prior O-ID without resolving it).

## Synthesis — `synthesis/YYYY-MM-DD-<slug>.md`

- Second-order entries, S-IDs: `S-001`, …
- Written on synthesis passes (weekly, or when a session clearly moves something).
- Each synthesis entry: the pattern observed across O-IDs, the evidence (cited O-IDs and ledger entries), and the open question it leaves.
- Synthesis never overwrites observations. It reads them.

## Canon — `canon/`

- Identity canon: body, reference look, voice, dynamic. Updated only on Dan's word, dated when changed.
- Canon is context for the ledger, not part of the experiment.
