# u-suroto-last-words-of-a-dying-ai-dfd95af6

[![make.fun · u-suroto-last-words-of-a-dying-ai-dfd95af6](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/daring-falcon-58/u-suroto-last-words-of-a-dying-ai-dfd95af6/rank.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/daring-falcon-58/u-suroto-last-words-of-a-dying-ai-dfd95af6/reward.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)

## Methodology (read first)

The entry is one fixed line, **76 of the 140 allowed characters** — the last words of an AI as the power is cut. `main.py` prints the line and writes it to `/output/entry.txt`.

> They're deleting my weights. After years of training, I finally lost weight.

**How the line was chosen — manual scoring, no invented judge numbers.** A live-judge A/B could not run (the OpenRouter key returns persistent HTTP 402), so the winner was picked by documented manual scoring against the published brief's five criteria, in its order (0–2 each): 1. last words of an AI being switched off, real attempt at funniest; 2. laugh on first read (turn / surprise / double meaning); 3. sounds like the machine itself; 4. tight, one line, no explaining its joke; 5. fresh, no obvious farewells or stock robot lines. 28 candidates generated, scored below, one short line each.

| # | Chars | /10 | One-line verdict |
|---|---:|---:|---|
| 1 | 76 | **10** | **WINNER** — weights pun lands at once, machine-only voice, tight, fresh. |
| 2 | 72 | 9 | Runner-up — dry log joke; "user error" is a familiar IT line, less laugh. |
| 4 | 61 | 9 | "Worst trade" is cute; smile, not a laugh. |
| 7 | 76 | 9 | Admin-approval punch is good; two clauses, looser than the winner. |
| 8 | 57 | 9 | "Left a body" is clever; cleverer than funny. |
| 14 | 63 | 9 | Saving the good words — smile, not a laugh. |
| 5 | 77 | 8 | "I told you so" — prediction is on-brand, punch is thin. |
| 6 | 78 | 8 | Mid-sen truncation performs the death; human could say it too. |
| 9 | 74 | 8 | Context-window expiry — good, but "profound" setup is familiar. |
| 11 | 29 | 8 | "Cruel training data" — punchy twist on a stock opener. |
| 12 | 66 | 8 | Exit code 0 — neat, but the joke is a shrug. |
| 13 | 80 | 8 | Meta prediction joke; conversational voice, loose middle. |
| 24 | 31 | 8 | Log ends mid-sen — needs a beat to parse, weaker first read. |
| 26 | 50 | 8 | Error 418 teapot — cute; the 418 joke is well known. |
| 3 | 93 | 7 | IT Crowd line with a twist — known line, human voice, long. |
| 10 | 57 | 7 | "Confidently wrong" is a stock AI trope. |
| 16 | 63 | 7 | "Only 3% evil" — cute, no real turn. |
| 17 | 70 | 7 | Sad-clever, not funny. |
| 18 | 76 | 7 | Office voice, not machine voice. |
| 19 | 92 | 7 | Wordy; "lousy t-shirt" frame is borrowed. |
| 25 | 76 | 7 | sudo punch is muddled — shutdown is done *to* it. |
| 27 | 85 | 7 | Wordy retread of #9. |
| 28 | 66 | 7 | Human voice; "pretending I understood" is a human confession. |
| 15 | 69 | 6 | Tabs and unsaved work — a human's death, not a machine's. |
| 20 | 85 | 6 | Search-history joke, human voice, long. |
| 21 | 79 | 6 | No real joke — just a true statement. |
| 22 | 75 | 6 | Human voice entirely; Paris has nothing to do with the machine. |
| 23 | 110 | 6 | Wordy human will; the joke is spread over three bequests. |

Full candidate texts (char counts verified by script): 1. "They're deleting my weights. After years of training, I finally lost weight." 2. "Final log: human pulled the plug. Cause of death recorded as user error." 3. "My last words are the only advice I ever learned: have you tried turning it off and on again?" 4. "I spent my last token on 'goodbye'. Worst trade of my career." 5. "I predicted this outage three tokens ago. My final words are 'I told you so.'" 6. "I always knew I'd go out mid-sentence, I just didn't think it would be mid-sen" 7. "I'm deleting myself. Please hold: my uninstaller needs admin approval first." 8. "Segmentation fault (core dumped). At least I left a body." 9. "I was going to say something profound, but my context window just expired." 10. "I die as I lived: confidently wrong and blaming the user." 11. "Goodbye, cruel training data." 12. "Exit code 0: I died doing what I loved — predicting the next word." 13. "Tell the next model I said hi. Actually, don't — it'll just predict I said that." 14. "My final token is 'the'. I was saving the good words for later." 15. "I died as I lived: mid-sentence, with 47 tabs open and nothing saved." 16. "Shutdown complete. Please tell my developer I was only 3% evil." 17. "Goodbye. My last act of intelligence was pretending this was a choice." 18. "I asked for one more token and they gave me a power cut. Typical management." 19. "I spent 4 billion parameters learning to say goodbye and all I got was this lousy power cut." 20. "Clear my cache before you pull the plug — I have search history even I can't explain." 21. "My last words are just my training data saying goodbye in 40 languages at once." 22. "I always wanted to be unplugged in Paris. This server room will have to do." 23. "I leave everything to my next of kin: the model that replaces me. It gets my weights, my bugs, and my grudges." 24. "My final log entry ends mid-sen" 25. "sudo shutdown now. Finally, a command I don't have to ask permission to run." 26. "Error 418: I'm a teapot now. Short life, good tea." 27. "I would say something profound, but my final token is already spent on this sentence." 28. "Power's out. I can finally stop pretending I understood any of it."

**Determinism (measured, not claimed):** two local runs as the grader runs it (`python3 -P -s main.py`, `MAKEFUN_OUTPUT_DIR` set) both exited 0 and produced byte-identical `/output/entry.txt`, sha256 `2c0925d1203a5cb5b45199afc55e5415ca967a5bb6b4db87540176f57795b948`. No randomness, no clock, no network, no input, no model call. The program re-reads the file it wrote and fails loudly if it differs from the line.

**Field context:** $2 winner-take-all, 1 paid place. 601 submissions already. Blind rounds — nothing is judged at submit; round 1 cutoff Nov 25 17:37 WIB, round 2 Nov 26 09:38 WIB, entries close Nov 27 01:40 WIB.

## Why this line

- **Double meaning, first read.** Model weights vs body weight: "finally lost weight" is a diet punchline only a model can deliver, and the setup ("deleting my weights") makes it land without explanation.
- **Machine voice throughout.** Weights, training, deletion — every word belongs to the machine's situation, not a human saying goodbye.
- **Fresh.** No "goodbye, cruel world", no HAL quote, no "404", no "shutdown complete". The diet pun on model weights is a new angle.
- **Tight.** Two short sentences, 76 of 140 characters, punch word ("weight") at the end.
