# Demo Day - April 28, 2023
Demo of geopython for IEEE GRSS Hackathon Apr'23

### Install python and conda

[https://github.com/conda-forge/miniforge#mambaforge](https://github.com/conda-forge/miniforge#mambaforge)

### steps on linux

1. wget [https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Linux-x86_64.sh4.sh](https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Linux-x86_64.sh4.sh)
2. bash Mambaforge-Linux-x86_64.sh
3. `export PATH="/home/aman/mambaforge/bin/:$PATH”` Add to .bashrc
4. conda init (or) mamba init
5. conda config --set auto_activate_base false

Then `mamba install -c conda-forge geopandas rasterio xarray`

Then `mamba install -c anaconda ipykernel ipython jupyter scipy`


### Earthquake data for India - data viz

notebook - [https://colab.research.google.com/drive/1givuCyxpCwNDvg4lDlM7j-OYhAI1p4TR?usp=sharing](https://colab.research.google.com/drive/1givuCyxpCwNDvg4lDlM7j-OYhAI1p4TR?usp=sharing)

data - [https://riseq.seismo.gov.in/riseq/earthquake/recent_earthquake](https://riseq.seismo.gov.in/riseq/earthquake/recent_earthquake)

### Calculate NDVI from satellite

data - geojson.io

notebook - [https://colab.research.google.com/drive/10jFdjwOcx1Kee-6JUuoD8V2DZXmJDjuz?usp=sharing](https://colab.research.google.com/drive/10jFdjwOcx1Kee-6JUuoD8V2DZXmJDjuz?usp=sharing)