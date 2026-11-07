# AdeloopVision Datasets

Datasets for Moroccan Darija language and multimodal research.

## Data policy

- Language code: `ary` (Moroccan Arabic).
- Synthetic examples are explicitly labeled `synthetic_ai_generated`.
- Synthetic records are not native-speaker-verified.
- Do not use synthetic records as gold evaluation data.
- Native-speaker review is required before promoting records to verified training or benchmark splits.
- Preserve provenance and consent for all user-contributed data. Do not commit private or identifying information.

## Daily Darija–English data

Daily files belong in `darija-english/daily/YYYY-MM-DD.json`.

Each record should contain:
`id`, `language`, `target_language`, `darija_ar`, `darija_latin`, `english`, `category`, `example_darija_ar`, `example_darija_latin`, `example_english`, `source_type`, `verified_by_native_speaker`, and `created_at`.

## Quality workflow

1. Generate varied, contextually natural examples.
2. Validate schema, duplicates, spelling variants, and translation alignment.
3. Keep generated and human-reviewed records in separate quality states.
4. Record reviewer and review date when a native speaker verifies an entry.
