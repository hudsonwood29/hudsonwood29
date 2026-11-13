# Hudson Wood — Quarto ePortfolio

This folder includes **editable Quarto source** (`.qmd`, `_quarto.yml`, `styles.css`) and a **ready-to-preview website** in `docs/`.

## Preview right now

Open `docs/index.html` in Chrome. Select **Data Visualizations** in the top navigation. All links work locally.

## Publish through GitHub Pages

1. Create a new public repository named `YOURUSERNAME.github.io` on GitHub, replacing YOURUSERNAME with your real GitHub handle. If you already have a portfolio repository, merge the files into it rather than replacing your existing work.
2. Upload **everything in this folder** to the repository root, including the `docs` folder and `_quarto.yml`.
3. On GitHub go to **Settings → Pages**, select **Deploy from a branch**, select `main` and **/docs**, then click **Save**.
4. Your home page will be `https://YOURUSERNAME.github.io/` if the repository has that exact name. Otherwise use `https://YOURUSERNAME.github.io/REPOSITORYNAME/` (and adjust site URLs as needed).
5. After updating any `.qmd`, run `quarto render` in the project root, and then commit/push the changed files. If Quarto regenerates `docs/`, it will replace the supplied preview pages.

## What you must finish before claiming Task 4 is complete

- Confirm the source dataset and all numbers in the GPU bar chart (the original slide uses approximate readings).
- Add team names and links to each teammate’s ePortfolio.
- Add the team's actual **histogram**, **scatter plot**, and **time-series** assertion–evidence slide images and descriptions. The question prompts are placeholders, not results.
- Make sure your team uses distinct dataset columns as required by the course.
- If you have not completed everything, follow your TA's instruction to submit the partial site or screenshots rather than miss the deadline.

Google Search Console indexing is optional and is not needed for publication or grading.
