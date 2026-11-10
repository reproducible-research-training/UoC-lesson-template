# UoC Lesson Template

A [Quarto](https://quarto.org) book template for building training lessons, from [Reproducible Research Cambridge](https://www.reproducibleresearchcambridge.co.uk/).

The [Introduction](intro.qmd) page shows examples of the content you can use: text formatting, lists, images, tables, executable Python code, equations, callouts, tabsets and activities.

## Use this template

1. Click **Use this template** at the top of this page to create your own copy of the repository.
2. Clone your new repository and install the requirements:

   ```bash
   pip install -r requirements.txt
   ```

3. Edit the content:
   - Write your chapters as `.qmd` files and list them under `chapters` in `_quarto.yml`.
   - Update the title, authors and contributors in `_quarto.yml`.
   - Update `CITATION.cff` with your lesson's details.
   - Add references to `references.bib`.
4. Preview the book in your browser:

   ```bash
   quarto preview
   ```

## Publish with GitHub Pages

The book is built into the `docs/` folder. To publish it:

1. Run `quarto render` and commit the `docs/` and `_freeze/` folders.
2. In your repository, go to **Settings → Pages**, set **Source** to "Deploy from a branch", and choose branch `main` and folder `/docs`.

## Requirements

- [Quarto](https://quarto.org/docs/get-started/) 1.3 or later
- Python 3 with the packages in `requirements.txt`

## Licence

Content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
