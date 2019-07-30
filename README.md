# NH19-Visualization

A collection of notebooks demonstrating plotting with matplotlib

### Installation

Visualisation tools change quite regularly, so the first step is to install an anaconda environment with the correct packages.
Don't forget to type `y` when conda asks you if you want to install some packages :smiley_cat:

```
conda create -n nh19-visualization python=3.7 nb_conda_kernels jupyter
```

Activate that environment and then install all the packages listed in the [requirements.txt](requirements.txt) file in this repository.

*If you don't run this command from inside of the repository then change `requirements.txt` to include the path (relative or absolute) to the file.*

```
conda activate nh19-visualization
pip install -r requirements.txt
```

Finally, make sure you can see this environment in [jupyter lab](https://jupyterlab.readthedocs.io/en/stable/).

```
python -m ipykernel install --user --name nh19-visualization
```

