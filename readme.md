## Conda environment

### Create Conda environment

```bash
conda create --name dbt-env python=3.12.4
```

### Enable Conda environment

```bash
conda activate dbt-env
```

### Install packages

```bash
conda install numpy pandas
pip install dbt-core dbt-bigquery dbt-snowflake sqlfluff
```

### Save Conda environment

```bash
conda env export > environment.yml
```

### Recreating Conda environment

```bash
conda env create -f environment.yml
```
