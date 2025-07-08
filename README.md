# SSA 2026 Cloud Workshop

Modules:

1. Jupyter & GeoLab
2. Data in and Data out
3. Dask
4. GPU (machine learning, LLMs - llamafile?)

## Jupyter & GeoLab

### Notebook fundamentals

- Notebook navigation
- Managing kernels
- Terminal
- Storage
  - home
  - S3
  - tmp
  - scratch 

### Package management

- Environments
  - Conda
  - Pip

- Packages
  - Pinned packages
  - Manage packages
    - Notebook
    - Terminal

### Git
- git client
- gh 
- basic git
  - remote & origin
  - branches
  - pull / add / commit / push

## Data In and Out

- SAGE
  - auth
  - AWS Open Data program
  - dataselect
  - S3
  - packages - obspy
 
- GAGE
  - auth
  - rinex via https://gage-data.earthscope.org/archive/
  - tiledb
 
- Data in
  - boto3
    - s3
    - RDS
    - ec2
  - Where to put data
    - home
    - tmp
    - scratch

- Data/Results out
  - save local
  - save S3
  - save to RDS

- Plots/Graphs out
  - save matplotlib
  - save seaborn
  - save latex

## Dask

- Computing with Multiple Cores
  - Concurrent programming, multi-threading, parallel processing
  - Lazy evaluation, dask delayed, dask compute
- Task graphs and scheduling
  - Visualize tasks
  - Mult-threading vs parallel process, the GIL
- Building pipelines
  - Delayed objects, lazy evaluation, compute
  - Functions and delaayed objects
- Dask arrays
  - Chunking, numpy vs dask arrays
  - Dask array methods
  - Custom functions over chunks
- Dask dataframes, multi-dimensional arrays
  - Read parquet, arrow, miniseed
  - Xarray

## GPU - machine learning / LLM / JupyterAI

- pytorch
- JupyterAI for coding
- running local LLM
