# AMC Directory

Take any past AMC 8, AMC 10 or AMC 12 as a quiz and see how you'd score.

Open `index.html`. Click the competition name in the header to switch between AMC 8, AMC 10 and AMC 12, and click the test next to it to pick a year (and the A or B test, for AMC 10 and 12).

| Competition | Tests |
| --- | --- |
| AMC 8 | 1985–2026, except 2021 (no contest) and 2025 (not posted yet). Years before 1999 are the AJHSME, the AMC 8's old name. |
| AMC 10 | 2000–2025, A and B tests from 2002, plus the 2021 Fall A test. Missing: 2020, 2021 Fall B and 2021 Spring B. |
| AMC 12 | 2000–2025, A and B tests from 2002. Missing: 2019, 2020 and both 2021 Fall tests. |

The missing tests aren't on Random Math Wiki yet.

Each quiz has all 25 problems, with figures, as multiple choice (A–E) like the real test.

- You answer one problem at a time, and each answer is graded right away.
- **Skip to** jumps to any problem, and **Skip →** moves on without answering.
- After you answer, the worked solution appears right below the problem.
- At the end you get your score, scored like the real test: 1 point per correct answer on the AMC 8 (out of 25), and on the AMC 10 and 12, 6 points per correct answer and 1.5 per skipped problem (out of 150).
- Your progress is saved in your browser separately for each test.

## Running it

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 4280
```

Then go to http://localhost:4280. To open a specific test, add it to the address, for example http://localhost:4280/#amc10-2023A or http://localhost:4280/#amc8-2019.

## Files

- `index.html`: the quiz.
- `data/index.js`: the list of every test.
- `data/<competition>/<test>.js`: the problems, answer choices, answers and solutions for one test.
- `images/<competition>/<test>/`: the figures and solution diagrams.
- `vendor/katex/`: [KaTeX](https://katex.org) (MIT license), which draws the math.

## Credits

Problems are from the MAA's [American Mathematics Competitions](https://maa.org/student-programs/amc/), © Mathematical Association of America. Problems, answers and solutions come from [Random Math Wiki](https://wiki.randommath.com), except the 2024 AMC 8, which was typed up from the official test booklet with explanations written for this site. Where the wiki's solution doesn't state a clear answer, the answer was worked out by hand from the solution.
