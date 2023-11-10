# mamba-insatll-env-instead-of-conda
mamba can intsall conda env fast than conda 

**using mamba to install Karmaforge**



Adding mamba to resolve your conda environment (https://anaconda.org/conda-forge/mamba) if you can write there (not possible on /c7/shared )
conda install -c conda-forge mamba

I have forked KarmaDock to avoid using the hard coded Chinese mirror...

https://github.com/truatpasteurdotfr/KarmaDock

then just 

mamba env create -n KarmaDock -f karmadock_env.yaml

Or use the explicit files
mamba create -n KarmaDock -f 20231108-1603-KarmaDock-conda-list--explicit.yml
or
mamba env create -n KarmaDock -f 20231108-1603-KarmaDock-conda-env-export.yml



