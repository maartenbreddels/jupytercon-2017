# jupytercon-2017
Material for my talk at JupyterCon 2017
* Links
  * vaex (binning/statistics of datasets with a billion rows on N-dimensional grids)
    * http://vaex.astro.rug.nl
    * https://vaex.readthedocs.io/en/latest/
    * https://github.com/maartenbreddels/vaex
  * ipyvolume (3d visualization)
    * https://ipyvolume.readthedocs.io/en/latest/
    * https://github.com/maartenbreddels/ipyvolume
* To run the notebooks you need vaex, ipyvolume and ipywebrtc
  * `conda install -c conda-forge vaex ipyvolume ipywebrtc`
 * Or using pip
   * `pip install --pre vaex`
   * `pip install ipyvolume ipywebrtc`
   * `jupyter nbextension enable --sys-prefix --py widgetsnbextension`
   * `jupyter nbextension enable --sys-prefix --py ipywebrtc`
   * `jupyter nbextension enable --sys-prefix --py ipyvolume`
 
