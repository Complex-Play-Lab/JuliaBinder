# Getting Started

Click this button [![Binder](https://mybinder.org/badge_logo.svg)](${BINDER_URL}) to run this project!

You'll find everything you need in `main.ipynb`!

# Files in this Project

- `README.md` That's what you're reading right now! This file is machine generated by the `build_readmd.sh` file.
- `apt.txt`, `Project.toml`, `Manifest.toml`, `config.jl`, and `postBuild` These are used to specify the exact environment needed for our code to run.
- `main.ipynb` This is where your code runs! It is a Jupyter notebook configured to use the [Julia](https://julialang.org/) programming language. It shows an example of running Epistemic Network Analysis to compare two Shakespeare plays.

# Making Edits

Changes that you make on binder are temporary. You can download your files from binder, or you can make your own repo that lives on github.

To make your own repo copy of this project that you can edit:

1. Create a [copy of this template](${GENERATE_URL}). It will need to be a public repo, but you can name it whatever you want
2. Create a [github personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). It will need the `repo` and `workflow` scopes
3. Open your project on binder (the binder button in your README will automatically update to link to your project!)
4. Make edits to your project on binder like you normally would
5. Open a terminal on binder and run:
```sh
git pull
git add --all
git commit -m "some friendly message here"
git push
```
When prompted to enter your password, enter your personal access token instead.

# Model Card

Last updated: ${DATE_STRING}

Inspired by [Model Cards for Model Reporting (Mitchell et al.)](https://arxiv.org/abs/1810.03993).

## Model Details

TODO: Intro paragraph about the model, the model type, the researchers, the data, the training, and the uses

## Papers

TODO: Link papers about/using the model

## Model Use

TODO: Paragraph about the intended/valid uses of the model

TODO: Paragraph about example *non*-intended/*invalid* uses of the model

## Data

TODO: Exact details on the data, how it was obtained, how it was cleaned, and what population(s) it does and does not represent

## Performance

TODO: Exact details on how the model was trained and evaluated, and the statistical results of those tests

## Limitations

TODO: Reiterate limitations mentioned above and fully elaborate the "so what" of those limitations

## Contact

If you have questions or comments about this model, please contact:

- TODO
