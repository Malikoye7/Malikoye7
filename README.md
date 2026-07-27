<div align="center">

# Malik Oyewole

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1400&color=2FA57C&center=true&vCenter=true&width=640&lines=Java+developer;M.+Applied+Computing+%40+University+of+Windsor;I+build+systems+that+survive+messy+real-world+data" alt="Java developer — M. Applied Computing at the University of Windsor" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-malik--atanda--oyewole-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/malik-atanda-oyewole) [![Email](https://img.shields.io/badge/Email-oyewolemalik16%40gmail.com-2FA57C?style=flat-square&logo=gmail&logoColor=white)](mailto:oyewolemalik16@gmail.com) ![Location](https://img.shields.io/badge/Windsor,%20ON-152238?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

## `~/whoami`

Master of Applied Computing student at the **University of Windsor**, working mostly in Java on crawlers, search engines and hand-built data structures.

Everything below is the same problem in a different costume: **take data from sources that disagree with each other, aren't always up, and change their layout without warning — and still return one answer you can trust.**

```
🔭  Building      a multi-source FX platform that reconciles five live feeds into one consensus rate
🧩  Strongest     data structures, algorithms, and the reasoning behind picking one over another
🎯  Looking for   internship / co-op roles in backend or software engineering
⚡  Opinion       the interesting part of a problem is deciding what to do when the inputs are wrong
```

---

## `~/stack`

<table>
<tr><td><b>Languages</b></td><td>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</td></tr>
<tr><td><b>Libraries</b></td><td>

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white) ![Jsoup](https://img.shields.io/badge/Jsoup-1F425F?style=flat-square) ![Gson](https://img.shields.io/badge/Gson-4285F4?style=flat-square&logo=google&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)

</td></tr>
<tr><td><b>Tooling</b></td><td>

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) ![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipseide&logoColor=white) ![Chrome](https://img.shields.io/badge/Headless%20Chrome-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

</td></tr>
<tr><td><b>Foundations</b></td><td>

![DSA](https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms-152238?style=flat-square) ![Concurrency](https://img.shields.io/badge/Concurrency-152238?style=flat-square) ![Scraping](https://img.shields.io/badge/Web%20Scraping-152238?style=flat-square) ![REST](https://img.shields.io/badge/REST%20APIs-152238?style=flat-square) ![Testing](https://img.shields.io/badge/Unit%20Testing-152238?style=flat-square)

</td></tr>
</table>

---

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

### [Real-Time Multi-Source Currency Converter](https://github.com/Malikoye7/Real-Time-Multi-Source-Currency-Converter)

Crawls **five live FX sources plus a real bank**, measures how far they disagree, drops any source more than 3% from the median, and draws the reasoning on screen — one bar per source.

Search over the crawled corpus, typo-tolerant currency lookup, role-based admin panel, 146 tests.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Jsoup](https://img.shields.io/badge/Jsoup-1F425F?style=flat-square) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

`BFS crawl` · `inverted index` · `Trie` · `max-heap` · `Levenshtein DP`

</td>
<td width="50%" valign="top">

### [Word Frequency Analyzer](https://github.com/Malikoye7/word-frequency-analyzer)

A **256-bucket hash table and QuickSort written from scratch** — no `HashMap`, no `Collections.sort`, no shortcuts.

4,817 raw tokens reduced to 435 ranked unique words.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

`custom hash table` · `separate chaining` · `QuickSort`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Trie Autocomplete](https://github.com/Malikoye7/trie-autocomplete)

Autocomplete on a **custom Trie**, `O(L + W)` prefix search — L to walk the prefix, W to collect every word underneath it.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

`prefix tree` · `DFS collection` · `complexity analysis`

</td>
<td width="50%" valign="top">

### [Forex Rate Scraper](https://github.com/Malikoye7/forex-rate-scraper)

**Selenium**-driven scraper for Bank of Canada daily rates, exported to CSV. The page builds its table client-side, so a plain HTTP request returns no numbers at all.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

`headless Chrome` · `explicit waits` · `CSV export`

</td>
</tr>
</table>

---

## `~/toolbox`

Structures and algorithms I've implemented by hand, and what I used each one for:

| Structure / algorithm | Used for | Where |
|---|---|---|
| Trie (prefix tree) | word completion ranked by corpus frequency | `trie-autocomplete`, converter |
| Hash table, separate chaining | word counting without `HashMap` | `word-frequency-analyzer` |
| Inverted index — nested `HashMap` | keyword search, per-page frequency | converter |
| Max-heap (`PriorityQueue`) | page ranking, top-N, bounded suggestions | converter |
| Levenshtein edit distance (DP) | spell check + typo-tolerant currency search | converter |
| BFS with `ArrayDeque` + `HashSet` | crawler frontier and visited set | converter |
| QuickSort | ranking words by frequency | `word-frequency-analyzer` |
| Median + weighted average | reconciling five disagreeing rate sources | converter |

---

<div align="center">

**Open to internship and co-op opportunities.**

[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/malik-atanda-oyewole) [![Send me an email](https://img.shields.io/badge/Send%20me%20an%20email-2FA57C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oyewolemalik16@gmail.com)

</div>
