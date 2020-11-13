# Conda environment with environment.yml

[![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/conda_environment/master?filepath=index.ipynb)  
P1  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Sridhar701Pitt/OptimizationPresentationMATH/master?filepath=Presentation%20-%20Optimization%20with%20Python%20P1.ipynb)  
P2  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Sridhar701Pitt/OptimizationPresentationMATH/master?filepath=Presentation%20-%20Optimization%20with%20Python%20P2.ipynb)  

A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

http://mybinder.org/v2/gh/binder-examples/conda_environment/master?filepath=index.ipynb  
https://mybinder.org/v2/gh/Sridhar701Pitt/OptimizationPresentationMATH/master?filepath=Presentation%20-%20Optimization%20with%20Python%20P1.ipynb

## Notes
The `environment.yml` file should list all Python libraries on which your notebooks
depend, specified as though they were created using the following `conda` commands:

```
conda activate example-environment
conda env export --from-history -f environment.yml
```

Note that the only libraries available to you will be the ones specified in
the `environment.yml`, so be sure to include everything that you need! 

Also note that if you skip the `--from-history`, conda may include OS-specific
packages in `environment.yml`, which you would have to manually prune from
`environment.yml`.  For example, confirmed macOS-specific packages that should
be removed are:

* libcxxabi=4.0.1
* appnope=0.1.0
* libgfortran=3.0.1
* libcxx=4.0.1
