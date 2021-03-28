# Conda environment with environment.yml

[![Binder](http://mybinder.org/badge_logo.svg)](#https://mybinder.org/v2/gh/dmbala/binder-PyDL/master)

A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

https://mybinder.org/v2/gh/dmbala/binder-PyDL/master


## Notes
The `environment.yml` file should list all Python libraries on which your notebooks
depend, specified as though they were created using the following `conda` commands:

```
conda activate PyBigData-environment
conda env export --from-history -f environment.yml
```

