# Sichuan Dialect Perception and Textual Absence

### The Perception-Text Mismatch in Chengdu Hip-Hop Lyrics

> Listeners hear Sichuan dialect as the defining sound of Chengdu hip-hop. A 40-song coded corpus shows it is near-absent from the written lyrics. The dialect lives in performance, not in text, and Chinese orthography is why.

This repository contains the complete coded corpus, interview transcripts, coding instruments, and verification data for the paper. All 40 songs are coded line-by-line with verbatim textual warrants for full auditability.

---

## Key Finding

When Chengdu CDC-affiliated hip-hop lyrics are systematically coded for Sichuan dialect features, the textual record does not match what listeners report hearing:

| Group | Songs Coded | Confirmed Dialect Features | Median Per Song |
|---|---|---|---|
| Chengdu (CDC) | 20 | 26 | **0** |
| Comparison | 20 | 0 | **0** |

The median is zero for both groups. 65.4% of all confirmed features came from one artist (KKECHO). The other four Chengdu artists are textually indistinguishable from the comparison group on dialect.

### By Artist (Chengdu Group)

| Artist | Songs | Confirmed Dialect (1a+1b+1d) | Code-Switching (1c) | Total Cat 1 |
|---|---|---|---|---|
| KKECHO | 4 | **17** | 23 | 44 |
| Masiwei | 5 | 9 | 0 | 9 |
| PSY.P | 3 | 0 | 0 | 0 |
| Wang Yitai | 4 | 0 | 0 | 0 |
| KnowKnow | 4 | 0 | 0 | 0 |

### The Explanation

Chinese characters are logographic: they encode meaning, not pronunciation. A rapper can write standard Mandarin characters and perform them in full Sichuan dialect (merged consonants, shifted tonal contours, Sichuan-specific vowel qualities). The written text captures none of this. The only dialect features visible in text are lexical items with no standard Mandarin equivalent. KKECHO uses these; the other artists do not.

---

## Theoretical Framework

The study bridges three literatures:

- **Hip-hop sociolinguistics:** Hip-hop globally functions as a site of linguistic identity construction through dialect choice (Alim, 2006; Pennycook, 2007; Androutsopoulos, 2009).
- **Sociolinguistic identity theory:** Dialect features index regional identity through multiple orders of social meaning (Silverstein, 2003; Bucholtz & Hall, 2005; Eckert, 2012).
- **Chinese orthography and dialect:** Logographic writing systems do not encode the phonological variation that carries dialect identity in speech (Duanmu, 2007; Qian, 1997).

No prior study had tested whether the Sichuan dialect that listeners perceive in Chengdu hip-hop appears in the written lyrics, or examined the implications of the orthographic gap for corpus-based dialect research in Chinese music.

---

## Corpus

**42 songs selected, 40 coded** (2 excluded for unavailable lyrics).

**Chengdu group** (20 coded, 5 CDC-affiliated artists):
Wang Yitai (4), KKECHO (4), Masiwei (5), KnowKnow (4), PSY.P (3)

**Comparison group** (20 coded, 4 Mandarin-dominant artists from non-Southwestern regions):
Jony J / Fujian (5), GALI / Shanghai (5), Tizzy T / Guangdong (5), AR / Xinjiang (5)

Selection: top-streamed post-2017 lead studio tracks per artist. Comparison artists exclude Southwestern Mandarin regions (sister dialects) and English-heavy bilingual artists (confound control). Lyrics sourced from KKBOX.

---

## Coding Protocol

Four-category scheme, applied line-by-line with AI-assisted coding (Claude, Anthropic), researcher verification, and native Mandarin speaker confirmation of all dialect codes.

| Category | What It Measures |
|---|---|
| **1. Dialect Features** | Sichuan lexical items, pronunciation markers, code-switching, grammar |
| **2. Cultural References** | Geographic, food, customs, historical, music scene |
| **3. Thematic Content** | Regional pride, personal narrative, social commentary, etc. |
| **4. Rhyme and Flow** | Rhyme density, dialect-dependent rhymes (first verse only) |

Every code requires a verbatim textual warrant. Ambiguous items flagged UNCERTAIN and excluded from confirmed counts.

---

## Repository Structure

```
coded/                            Line-by-line coded lyrics, all 40 songs
  WYT-PSY-coded.md               Wang Yitai (4) + PSY.P (3)
  KKE-coded.md                   KKECHO (4), including "Chao" analysis
  MSW-coded.md                   Masiwei (5)
  KN-coded.md                    KnowKnow (4)
  JJ-coded.md                    Jony J (5, comparison)
  GALI-coded.md                  GALI (5, comparison)
  TZT-coded.md                   Tizzy T (5, comparison)
  AR-coded.md                    AR (5, comparison)
interviews/
  interview-1-teacher.md          Full transcript, Chinese + English
  interview-2-friend.md           Full transcript, Chinese + English
corpus-metadata.md                Song corpus with Spotify play counts and KKBOX URLs
coding-scheme.md                  Four-category coding protocol with definitions
sample-coded-lyrics.md            Worked examples: KKECHO "Chao" + Jony J comparison
verification-audit.md             Three-layer verification procedure and uncertain items
normalization.md                  Text-length normalization (characters per song, features/100 chars)
consent-form.md                   Informed consent template
field-notes.md                    Dated fieldwork observations, Chengdu, July 2025
```

---

## Citation

```
Hardcastle, A. (2025). Heard but Not Written: Sichuan Dialect Perception and
Textual Absence in Chengdu Hip-Hop Lyrics.
```

## License

MIT

## Author

**Auric Hardcastle** · [LinkedIn](https://linkedin.com/in/auric-hardcastle) · [GitHub](https://github.com/AuricHardcastle)
