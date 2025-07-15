# SSA 2026 Cloud Workshop

Modules:

1. GeoLab Fundamentals
2. Data in and Data out
3. Workfows
4. Dask
5. GPU (machine learning, LLMs - llamafile?)

## GeoLab Fundamentals

### [Introduction to Git](./modules/git.ipynb)
- repositories
- committing and fixing files
- branches and mergin branches
- push, pull, and clone

### [Package management](./modules/package_management.ipynb)

- Packages and Package Managers
  - Pip and Conda
- Virtual Environments
  - Creating Environments
- Installing Packages
- Exercise

### [Notebook Basics](./modules/notebook.ipynb)

- Understanding the Notebook Interface
  - Working with Cells
  - Cell Magics
  - Saving Notebooks
  - Export Notebooks
  - Sharing Notebooks
- Reading Python Code
  - An Example
  - Exercise

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
