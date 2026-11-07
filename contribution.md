# AdeloopVision Dataset Contribution Instructions

You are contributing Moroccan Darija–English vocabulary records to AdeloopVision.

Generate new, natural Moroccan Darija vocabulary records.

Rules:
1. Use Moroccan Darija, not Modern Standard Arabic.
2. Include Arabic script, Latin transliteration, English meaning and natural example sentences.
3. Do not invent unusual expressions just to increase the record count.
4. Do not repeat headwords, meanings or example sentences from the existing dataset.
5. Preserve genuine spelling variants only when they represent meaningful distinctions.
6. Do not claim native-speaker verification.
7. Mark every generated record as:
   - source_type: synthetic_ai_generated
   - verified_by_native_speaker: false
8. Include all required schema fields.
9. Return valid JSON only.
10. If you cannot check the existing dataset, explicitly report that duplicate checking remains incomplete.

Every submission must include contributor and model provenance in its batch metadata.
