# mlwpy_code
Code from the Pearson Addison-Wesley book Machine Learning with Python for Everyone

### Versioning Note
The code here is the latest/greatest version.  Updated releases are planned annually in August.  The version here has been updated to work with the most recent versions of its dependencies (e.g., scikit-learn and pandas). If you want a quick link to the latest release (with convenient downloads), [click here](https://github.com/mfenner1/mlwpy_code/releases/latest).

If you want the exact version of the code that came with the book, you'll want the 1.0 release which you can
  * [view the source of](https://github.com/mfenner1/mlwpy_code/tree/v1.0)
  * [or download directly](https://github.com/mfenner1/mlwpy_code/releases/tag/v1.0).  


### Python Environment Setup
See `make_environments.md` ([here](https://github.com/mfenner1/mlwpy_code/blob/master/make_environments.md)) for details.

### Package Versions
Here are the versions of important packages as of the August 2019 code update.  As a reminder, you can install specific versions of packages using anaconda/conda [as documented here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html#installing-packages).  For example, `conda install scikit-learn=0.20`.  

My plan is to update the book software to the most recent versions of software around once a year (likely near August/September).  I'll update the software versions listed here when I do so.  The full list of package versions is available in `book_base_env.yml` produced by `conda env export > book_base_env.yml`.

```  
matplotlib                3.1.0  
numpy                     1.16.4
pandas                    0.25.0
patsy                     0.5.1
pymc3                     3.7     (conda-forge)  
py-xgboost                0.9  
scikit-learn              0.21.2  
scipy                     1.3.1
seaborn                   0.9.0
statsmodels               0.10.1  
tensorflow                1.14.0
```
