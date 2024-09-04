# nso-24-stats
Statistics material for the 2024 UCSF Neuroscience Orientation

# Usage

## Using GitHub Pages
Visit the most recently deployed version of the site at https://maxinelevesque.github.io/nso-24-stats/.

## Locally
This project was typeset with [Quarto](https://quarto.org). Their installation instructions are [here](https://quarto.org/docs/get-started/).

### `conda` dependencies
To create a [`conda`](https://docs.anaconda.com/miniconda/) environment with the needed dependencies, you can run this from the `slides` directory:

```bash
conda env create -f environment.yml -p {/path/to/repo}/slides/.conda
```

Run Quarto from within this environment by activating it; from within the `slides` directory, you can run:

```bash
conda activate ./.conda
```

### Preview in browser
With Quarto installed and the environment activated, in the `slides` directory, run:

```bash
quarto preview
```

### Building outputs
With Quarto installed and the environment activated, in the `slides` directory, run:

```bash
quarto render
```

The static site will be built in the `docs` directory (for use with GitHub Pages).