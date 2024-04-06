# GraphGA example

GraphGA is a genetic algorithm, see original [GraphGA README](GBGA_README.md) for details.

## Installation

After cloning this repo, setup the python environment with your favorite environment manager (conda/mamba).

    conda env create -f molscore_environment.yml

## Usage

I have modified the main script to include molscore scoring functions. This is a minimal working version to run configs or benchmarks.

    python molscore_GB_GA.py --molscore <path_to_config|name_of_benchmark|dir_of_configs>