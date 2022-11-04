# SH_backend_notebooks
Notebooks to demonstrate basic usage of the Sentinel Hub openEO backend. This repository consists of 5 notebooks (/notebooks)
- 1_SH_backend_basic_endpoints: Call some basic endpoints and show responses
- 2_SH_backend_mean_NDVI: Calculate mean NDVI over time (as synchronous and batch job) and export the result (locally, via signed URL)
- 3_SH_backend_CLC: Showcase of large scale batch processing
- 4_Commercial_Data: Showcasing how to order and download commercical data using the openEO api commercial data extension
- SAP02_On-demand_preview: Showcase how on-demand preview functionality can be called

This project uses Python 3.8.8

### Install new package

```
pipenv install [package]
```

### Running notebooks

Copy `.env.example` file and rename the copied file to `.env`. Fill out the needed values (needed for notebook 4_Commercial_Data)

Install packages 

```
pipenv install
```

Switch to folder with notebooks and start jupyter notebook

```
cd notebooks
pipenv run jupyter notebook
```