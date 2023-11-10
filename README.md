# mamba-insatll-env-instead-of-conda
mamba can intsall conda env fast than conda 

**using mamba to install conda env**



Adding mamba to resolve your conda environment (https://anaconda.org/conda-forge/mamba) if you can write there 
conda install -c conda-forge mamba

to avoid using the hard coded (far-away) mirror...

then just 

mamba env create -n KarmaDock -f package_env.yaml

Or use the explicit files
mamba create -n env_name -f packge-conda-list--explicit.yml
or
mamba env create -n env_name -f package-conda-env-export.yml



