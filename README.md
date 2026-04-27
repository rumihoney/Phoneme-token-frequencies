Phoneme Zipf Analysis (CMUdict)

This project analyzes phoneme frequencies in CMUdict to test whether they follow a Zipf-like distribution.

What's included:
- phonemic_frequencies.py → main script that loads CMUdict, processes phonemes, and runs the analysis
- zipf_quick_report → function that counts and ranks phoneme frequencies
- zipf_plot_simple → function that plots frequency vs rank

How results were obtained:
- CMUdict entries were loaded using NLTK
- Stress markers were removed (e.g., AH0 → AH)
- All phoneme tokens were collected into a single list
- Frequencies were counted and ranked
- A Zipf-style plot (rank vs frequency) was generated

Results:
- 39 phoneme types
- 853,918 total tokens
- Frequency decreases rapidly with rank, showing a Zipf-like pattern

Top phonemes:
- AH → 71410
- N  → 60564
- S  → 50427
- IH → 50093
- L  → 49479


