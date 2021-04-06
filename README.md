This repo holds the analysis described in [this reddit post](LINK).
It uses Pushshift's API to download reddit comments and huggingface's implementation of DistilBert for sentiment classification.

To run the code, install [conda](https://docs.conda.io/en/latest/miniconda.html), and use it to install the packages found in the environment file:

```
conda env create -f environment.yml
conda activate scott
```

If your jupyter notebook is having trouble finding the modules it needs, you can install the conda environment as a kernel with the command
```
python -m ipykernel install --user --name scott --display-name "scott"
```
