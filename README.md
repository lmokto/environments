#### Conda environments

#### Export and create conda environments with yml

```
conda env export > envname.yml
conda env create -f envname.yml
```

#### Activate and deactivated env

```
conda activate envname
conda deactivate
```

#### List all the conda env available, create a new, remove and clone.

```
conda info --envs
conda create --name envname
conda remove --name envname --all
conda create --name clone_envname --clone envname
```
