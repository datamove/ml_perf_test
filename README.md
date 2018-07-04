# ml_perf_test
Utilities and notebooks with some performance tests for typical ML tasks

'''
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh
. ~/miniconda3/etc/profile.d/conda.sh
conda create --name testmkl pip numpy scipy scikit-learn joblib
conda activate testmkl
conda install -c conda-forge lightgbm
'''

To make sure you use packages based on Intel MKL, run python shell, import numpy and then check what libs are loaded, the list should contain some mkl libs
For example:
'lsof -p 5971 | grep mkl'
where 5971 is PID of your python shell process.

## Run
python tfidf_bench.py

# LINPACK
## Download

## Run


