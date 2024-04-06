# CReM example

CReM is a genetic algorithm that utilises 'chemically meaningful' operations, see original [CReM README](CREM_README.md) for details.

## Installation

After cloning this repo, setup the python environment with your favorite environment manager (conda/mamba).

    conda env create -f molscore_environment.yml

## Usage

I have modified the main script to include molscore scoring functions. This is a minimal working version to run configs or benchmarks.

    python molscore_crem.py --molscore <path_to_config|name_of_benchmark|dir_of_configs> --smiles_file <path_to_smiles> --db_fname <path_to_db>

**Note**: Be sure to create or download the fragment database, see [original instructions](CREM_README.md). 