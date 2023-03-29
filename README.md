# Pubmed Banana

Any term grows exponentially in PubMed, even "banana".

> This idea comes from a blog post published some time ago. If you find the original psot, please let me know so I can credit it.

## Setup your environment

Clone the repository:

```bash
git clone https://github.com/MDverse/mdda.git
```

Move to the new directory:

```bash
cd mdda
```

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

Install [mamba](https://github.com/mamba-org/mamba):

```bash
conda install mamba -n base -c conda-forge
```

Create the `pubmed-banana` conda environment:
```
mamba env create -f binder/environment.yml
```

Load the `pubmed-banana` conda environment:
```
conda activate pubmed-banana
```

Note: you can also update the conda environment with:

```bash
mamba env update -f binder/environment.yml
```

To deactivate an active environment, use

```
conda deactivate
```

## Run the notebook

Start Jupyter Lab:

```bash
jupyter lab
```

Then open the `pubmed-banana.ipynb` notebook.