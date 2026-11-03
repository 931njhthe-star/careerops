# General English vocabulary dataset — provenance and limitations

This folder contains ten ranked JSON files (`general-01.json` through `general-10.json`) with 1,000 entries each.

## Sources
- **Ranking**: [first20hours/google-10000-english](https://github.com/first20hours/google-10000-english). Based on frequency counts from the Google Trillion Word Corpus. The numbers indicate order within that source, **not** CEFR difficulty or modern spoken-English rank. It includes abbreviations, names, proper nouns, and web jargon.
- **Korean meanings, phonetics and CEFR metadata**: [Open English-Korean Dictionary / LexiSnap](https://github.com/jhseo1211/open-english-korean-dict), licensed under [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The dictionary combines sources with their own licenses; follow the upstream attribution and share-alike requirements when redistributing adaptations of its content.
- **Sample bilingual sentences**: [Tatoeba-Challenge](https://github.com/Helsinki-NLP/Tatoeba-Challenge) and [Facebook Research LASER](https://github.com/facebookresearch/LASER), including community-contributed parallel sentences. Individual sentence rights, attribution, and translation quality may differ; review upstream terms before further redistribution.
- **Previously authored CareerOps examples**: retained where the target word matches the ranked list.

## Quality and scope
- Entries with a **meaning** have a dictionary-derived or manually curated Korean gloss. A gloss can be incomplete, archaic, or contextually wrong, so it is not a substitute for a reviewed learner's dictionary.
- **examples** contain bilingual sentences sourced from an aligned corpus or existing reviewed examples. They are not necessarily sense-disambiguated for every polysemous English word.
- Entries without two good examples have deliberately **not** been padded using fake, boilerplate or metalinguistic 'examples'.
- Example sets are for reference; the dataset does not guarantee sentence naturalness, grammar, or translation precision.
- The CSV/JSON files are static; users do not need to download external dictionaries at runtime.

## Learning progress
- All 10,000 ranked entries are available for learning in 10 levels × 20 sets × 50 words.
- Browser-local study progress is maintained separately from this dataset.
