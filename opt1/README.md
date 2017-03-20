# Prerequisites

Prerequisites are listed in the included env.yml file. Items listed under pip
can be installed via:
```bash
pip install <package_name>
```

Items not listed under pip should still be installable via pip, though the
conda spec does allow for non-python packages (e.g. gcc, R, fortran).

If you're using anaconda (a highly recommended distribution of python),
installation is much simplified:
```bash
conda env create -f env.yml
```

# Usage
If installed via conda:
```bash
source activate <env_name> # if running on windows, just 'activate <env_name'
```
otherwise the prerequisites should be installed in your current environment.

Then, for both methods:
```bash
jupyter notebook <path_to_this_folder>
```

In most situations, the jupyter server page opens automatically. If not, copy
and navigate to the url that jupyter notebook prints at start.