# Contributing 

## Quarto

The web pages are built using https://quarto.org See [their Get Started section](https://quarto.org/docs/get-started/) and the [guide](https://quarto.org/docs/guide/) for hints on usage.

## Github.com and branches

To add to the repo, you can either [create a fork of this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks), edit there, and then [make a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork), or ask for direct access to this repo, and create a branch for your edits there.

Once the changes are merged into the `main` branch, the CI will run, and update the `gh-pages` branch to contain the new web page, which will then be served on the public URL.

## Adding pages and sections

To add a page, simply create a `.qmd` file with your desired content.

New sections need to be added in the `_quarto.yml` file in the root of this repository.

