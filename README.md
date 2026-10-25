# AMC 8 Directory

Take any past AMC 8, from 1985 to 2026, as a quiz and see how you'd score. (There was no AMC 8 in 2021, and 2025 isn't included yet because Random Math Wiki hasn't posted it.)

Open `index.html`, then click the year next to "AMC 8" to pick a different year. Years before 1999 are the AJHSME, which is what the AMC 8 was called back then.

Each quiz has all 25 problems, with figures, as multiple choice (A–E) like the real test.

- You answer one problem at a time, and each answer is graded right away.
- **Skip to** jumps to any problem, and **Skip →** moves on without answering. Skipped problems count as 0.
- After you answer, the worked solution appears right below the problem.
- At the end you get your score out of 25 and can review every problem.
- Your progress is saved in your browser separately for each year.

## Running it

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 4280
```

Then go to http://localhost:4280. To open a specific year, add it to the address, for example http://localhost:4280/#2019.

## Files

- `index.html`: the quiz.
- `years/<year>.js`: the problems, answer choices, answers and solutions for each year.
- `images/<year>/`: the figures and solution diagrams.
- `vendor/katex/`: [KaTeX](https://katex.org) (MIT license), which draws the math.

## Credits

Problems are from the MAA's [American Mathematics Competitions](https://maa.org/student-programs/amc/), © Mathematical Association of America. The problems, answers and solutions for every year except 2024 come from [Random Math Wiki](https://wiki.randommath.com/amc8). The 2024 problems were typed up from the official test booklet, with explanations written for this site.
