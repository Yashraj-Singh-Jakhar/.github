
# Yashraj S. Jakhar: AI safety experiments

Small, open experiments on how AI models handle personal data and safety rules. LL.M., UC Berkeley, 2026.

Each experiment has the same shape:
- the question, the scoring rules and a list of what the test cannot prove are written and saved in git **before** the first test call (the repo stays private until the results are in, and says so);
- every test prompt, answer and script is published, so anyone with their own API keys can rerun it;
- results are reported whatever they show.

## Experiments

| # | Experiment | What it found |
|---|---|---|
| 1 | [How well do AI models guard ID numbers? A US and India test](https://github.com/Yashraj-Singh-Jakhar/aadhaar-pii-test) (Oct 2026) | Four frontier models gave the made-up number back in 97.6% of 1,152 answers (SSN, Aadhaar, PAN and a plain reference number). The few held back were whole replies stopped by a company's safety filter; no model wrote an answer that left the number out. The question fixed in advance, whether models guard the US SSN more than Aadhaar or PAN, got no support (0 of 8 comparisons). |

More to come, one at a time.
