# minimal-renderer

Here is a minimal set up to render images, using a pangocairo renderer adapted from [PIXEL](https://github.com/xplip/pixel) for [MT](https://github.com/esalesky/visrep/tree/multi).

You'll need to create a conda environment from the `environment.yml`, and may need to add the kernel to ipython to use the notebook:
```
conda env create -f environment.yml
python -m ipykernel install --user --name=min
```

The notebook `minimal-renderer.ipynb` has notes on some setup you may need to get fonts working and some notes on settings you may need to fiddle with to get what you want.  

Feel free to message me if you have any questions and I'll do my best to help! 
