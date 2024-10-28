## Notebooks

To view notebooks online visit [nbviewer](http://nbviewer.jupyter.org/github/hfmark/notebooks/tree/main/).

If you want to run notebooks locally, you will need to install the relevant dependencies. These are essentially the dependencies of [rf](https://github.com/trichter/rf), plus [telewavesim](https://github.com/paudetseis/Telewavesim) for the harmonic decomposition demo.
The easiest way to install the dependencies is via [anaconda](https://conda.io/miniconda.html):

```
conda create -n notebooks python=3.8 obspy cartopy geographiclib shapely h5py mtspec tqdm fortran-compiler jupyterlab
conda activate notebooks
pip install obspyh5 rf telewavesim
```

After that, clone the notebooks repository or download individual notebooks.
Navigate to the folder of the repository and run `jupyter-lab` to play with the code.
