# Phoneme Zipf Analysis (CMUdict)

This project analyzes phoneme frequencies in CMUdict to test whether they follow a Zipf-like distribution.

## Features

- Loads the CMU Pronouncing Dictionary from NLTK
- Removes lexical stress markers (e.g., `AH0` → `AH`)
- Counts phoneme token frequencies
- Ranks phonemes by frequency
- Generates a Zipf-style frequency vs. rank plot

## Project Structure

- **phonemic_frequencies.py** — Main script that loads CMUdict and performs the analysis
- **zipf_quick_report()** — Counts and ranks phoneme frequencies
- **zipf_plot_simple()** — Generates a frequency vs. rank plot

## Results

| Metric | Value |
|--------|------:|
| Types | 39 |
| Tokens | 853,918 |

### Top 15 Most Frequent Phonemes

| Rank | ARPAbet | IPA | Example | Frequency |
|----:|:-------:|:---:|:--------|---------:|
| 1 | AH | /ʌ/ | *buck* | 71,410 |
| 2 | N | /n/ | *bun, sun* | 60,564 |
| 3 | S | /s/ | *bus, sun* | 50,427 |
| 4 | IH | /ɪ/ | *bit, sit* | 50,093 |
| 5 | L | /l/ | *bull, sill* | 49,479 |
| 6 | T | /t/ | *but, sit* | 48,549 |
| 7 | R | /r/ | *burr, sir* | 46,046 |
| 8 | K | /k/ | *buck, sick* | 42,502 |
| 9 | IY | /iː/ | *bee, see* | 34,504 |
| 10 | D | /d/ | *bud, sid* | 32,389 |
| 11 | M | /m/ | *bum, sum* | 29,347 |
| 12 | ER | /ɝ/ | *bird, serve* | 29,027 |
| 13 | Z | /z/ | *buzz, size* | 27,842 |
| 14 | EH | /ɛ/ | *bet, set* | 27,398 |
| 15 | AA | /ɑ/ | *bob, saw* | 24,546 |


