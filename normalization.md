# Fix 2: Text-Length Normalization of Dialect Feature Counts

**Issue flagged:** The defense panel noted that raw dialect feature counts per song do not account for variation in song length. If KKECHO's songs are simply longer, his higher counts may be an artifact of text length rather than higher density. This fix normalizes by Chinese character count.

**Method:** For each of the 39 coded songs (20 Chengdu, 19 comparison -- CD-KKE-05 "悲惨人生" excluded due to missing lyrics), we counted all Chinese characters (Unicode range \u4e00-\u9fff) in the lyric body (after 作词/作曲 metadata, before 出自专辑). We then computed confirmed dialect features per 100 Chinese characters.

**Note on WYT-04:** CD-WYT-04 ("目不转睛") was also unavailable on KKBOX ("暂无歌词"). The coded corpus therefore contains 20 Chengdu songs across 5 artists: KKECHO (4), Masiwei (5), KnowKnow (4), Wang Yitai (4), PSY.P (3). If the panel's count of 19 comparison songs is correct, one comparison track may have been excluded at an earlier stage; we report all 20 comparison songs coded.

---

## Table 1 (Revised): Chengdu Group -- Dialect Features Normalized by Text Length

| Song ID | Artist | Title | Chinese Chars | Confirmed Dialect Features | Features/100 chars |
|---------|--------|-------|-------------:|---------------------------:|-------------------:|
| CD-KKE-01 | KKECHO | 忏悔录 | 448 | 7 | **1.56** |
| CD-KKE-02 | KKECHO | 青城山下 | 638 | 5 | **0.78** |
| CD-KKE-03 | KKECHO | 抽象画家 | 371 | 3 | **0.81** |
| CD-KKE-04 | KKECHO | 超 | 687 | 17 | **2.47** |
| CD-MSW-01 | Masiwei | 花花公子 | 672 | 0 | 0.00 |
| CD-MSW-02 | Masiwei | Coco Elva Tia | 600 | 0 | 0.00 |
| CD-MSW-03 | Masiwei | P.Y.T | 506 | 2 | **0.40** |
| CD-MSW-04 | Masiwei | House Music | 441 | 2 | **0.45** |
| CD-MSW-05 | Masiwei | Babe | 618 | 5 | **0.81** |
| CD-KN-01 | KnowKnow | R&B All Night | 675 | 0 | 0.00 |
| CD-KN-02 | KnowKnow | Mr. Bentley | 347 | 0 | 0.00 |
| CD-KN-03 | KnowKnow | 坦白 | 526 | 0 | 0.00 |
| CD-KN-04 | KnowKnow | Sometimes | 510 | 0 | 0.00 |
| CD-WYT-01 | Wang Yitai | 危险派对 | 388 | 0 | 0.00 |
| CD-WYT-02 | Wang Yitai | 阿司匹林 | 785 | 0 | 0.00 |
| CD-WYT-03 | Wang Yitai | 别怕变老 | 892 | 0 | 0.00 |
| CD-WYT-05 | Wang Yitai | 人间天堂 | 783 | 0 | 0.00 |
| CD-PSY-01 | PSY.P | 我知道自己会输 | 662 | 0 | 0.00 |
| CD-PSY-02 | PSY.P | 街头艺术家 | 1137 | 0 | 0.00 |
| CD-PSY-03 | PSY.P | 三十多岁的人 | 825 | 0 | 0.00 |

### Chengdu Group Summary

| Artist | Songs | Total Chars | Total Features | Features/100 chars |
|--------|------:|------------:|---------------:|-------------------:|
| KKECHO | 4 | 2,144 | 32 | **1.49** |
| Masiwei | 5 | 2,837 | 9 | **0.32** |
| KnowKnow | 4 | 2,058 | 0 | 0.00 |
| Wang Yitai | 4 | 2,848 | 0 | 0.00 |
| PSY.P | 3 | 2,624 | 0 | 0.00 |
| **CD Total** | **20** | **12,511** | **41** | **0.33** |

---

## Table 2 (Revised): Comparison Group -- Dialect Features Normalized by Text Length

| Song ID | Artist | Title | Chinese Chars | Confirmed Dialect Features | Features/100 chars |
|---------|--------|-------|-------------:|---------------------------:|-------------------:|
| CMP-AR-01 | AR / 艾热 | 星球坠落 | 718 | 0 | 0.00 |
| CMP-AR-02 | AR | 巨人 | 792 | 0 | 0.00 |
| CMP-AR-03 | AR | 小人物 | 553 | 0 | 0.00 |
| CMP-AR-04 | AR | 女孩 | 501 | 0 | 0.00 |
| CMP-AR-05 | AR | 乌云中 | 615 | 0 | 0.00 |
| CMP-GALI-01 | GALI | 70% | 634 | 0 | 0.00 |
| CMP-GALI-02 | GALI | 狂恋 | 716 | 0 | 0.00 |
| CMP-GALI-03 | GALI | 6ackPack | 571 | 0 | 0.00 |
| CMP-GALI-04 | GALI | AmberStone | 685 | 0 | 0.00 |
| CMP-GALI-05 | GALI | 玛瑙 | 835 | 0 | 0.00 |
| CMP-JJ-01 | Jony J | 不用去猜 | 1,034 | 0 | 0.00 |
| CMP-JJ-02 | Jony J | My Man | 753 | 0 | 0.00 |
| CMP-JJ-03 | Jony J | 山脚 | 842 | 0 | 0.00 |
| CMP-JJ-04 | Jony J | 喜新恋旧 | 1,154 | 0 | 0.00 |
| CMP-JJ-05 | Jony J | 奴隶 | 870 | 0 | 0.00 |
| CMP-TZT-01 | Tizzy T | 冷战 | 747 | 0 | 0.00 |
| CMP-TZT-02 | Tizzy T | 100 | 884 | 0 | 0.00 |
| CMP-TZT-03 | Tizzy T | 飞船失事 | 679 | 0 | 0.00 |
| CMP-TZT-04 | Tizzy T | 噩梦 | 681 | 0 | 0.00 |
| CMP-TZT-05 | Tizzy T | 头文字T | 869 | 0 | 0.00 |

### Comparison Group Summary

| Artist | Songs | Total Chars | Total Features | Features/100 chars |
|--------|------:|------------:|---------------:|-------------------:|
| AR / 艾热 | 5 | 3,179 | 0 | 0.00 |
| GALI | 5 | 3,441 | 0 | 0.00 |
| Jony J | 5 | 4,653 | 0 | 0.00 |
| Tizzy T | 5 | 3,860 | 0 | 0.00 |
| **CMP Total** | **20** | **15,133** | **0** | **0.00** |

---

## Interpretation: Does KKECHO's Density Survive Normalization?

**Yes -- and the length-normalization defense is defused.** KKECHO's dialect feature density *survives* normalization and actually strengthens the paper's argument in three ways:

1. **KKECHO's density is not explained by song length.** "超" (CD-KKE-04, 687 characters) is not the longest song in the corpus. Several zero-feature songs are longer: PSY.P's "街头艺术家" (1,137 chars), Jony J's "喜新恋旧" (1,154 chars), Wang Yitai's "别怕变老" (892 chars). Despite being a mid-length song, "超" has the highest normalized density at 2.47 features per 100 characters. Meanwhile, the longest Chengdu song (PSY.P's "街头艺术家," 1,137 characters) contains zero confirmed dialect features.

2. **The normalized gap between KKECHO and all other artists remains categorical.** KKECHO's aggregate rate of 1.49 features/100 characters is 4.7 times higher than Masiwei's (0.32/100) and infinitely higher than the remaining 7 artists (all 0.00/100). This is not a gradient that text length could flatten -- it is a binary distinction between artists who embed Sichuan dialect and those who do not, with KKECHO as the clear outlier.

3. **The comparison group's zero-rate holds at every length.** Comparison songs range from 501 characters (AR, "女孩") to 1,154 characters (Jony J, "喜新恋旧"). None contain confirmed Sichuan dialect features regardless of length. This rules out the possibility that longer songs would naturally accumulate dialect features through chance.

4. **Within KKECHO, "超" is denser, not just longer.** Among KKECHO's own 4 songs, "超" (687 chars, 2.47/100) is denser than "忏悔录" (448 chars, 1.56/100), which is a shorter song. The shortest KKECHO song, "抽象画家" (371 chars, 0.81/100), actually has a lower rate than the mid-length "忏悔录." This demonstrates that density varies by song-level stylistic choice, not by text length.

**Conclusion for the paper:** Text-length normalization confirms that KKECHO's dialect embedding is a density phenomenon, not a volume artifact. The stylistic contrast between KKECHO (1.49/100) and the rest of the Chengdu group (0.09/100 pooled, or 0.32/100 for the next-highest Masiwei) is robust to normalization. The comparison group's categorical zero holds across all song lengths. The panel's concern is addressed: KKECHO's songs are not simply longer -- they are denser in Sichuan dialect features per unit of text.

---

## Methodological Note on Character Counts

Chinese characters were counted using the Unicode CJK Unified Ideographs range (\u4e00-\u9fff). This captures all standard Chinese characters including traditional and simplified variants. English words, punctuation, numbers, and romanized text (pinyin) are excluded from the character count. This is appropriate because dialect features are coded within the Chinese-language portions of the lyrics; English code-switching is tracked separately under Category 1c.

Song text was extracted from the lyric body of each scraped source file, excluding page metadata (headers, navigation), credit lines (作词/作曲/编曲), and album attribution (出自专辑). For songs with multiple scrape sources (e.g., KKBOX and Genius), the cleanest available source was used.
