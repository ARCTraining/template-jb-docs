# A template jupyter book documentation repository

This is a template repository that can be used when generating documentation using [Jupyter-books](https://github.com/executablebooks/jupyter-book) and hosting the site via GitHub pages.

## Working with this project locally

You can get this project working locally by using the environment.yml file to create a conda environment that contains all the dependencies required to get started.

```{bash}
$ git clone https://github.com/ARCTraining/template-jb-docs.git

$ conda env create -f environment.yml
```

To build the html content locally you can use the `jupyter-book` command line tool:

```{bash}
# navigate to the repository root
$ cd template-jb-docs
# sometimes worth running jupyter-book clean book/ to remove old files
# build the book
$ jupyter-book build book/
```
### Windows

Jupyterbook is no longer supported on [Windows](https://jupyterbook.org/en/stable/advanced/windows.html) (since Windows 10). The [official documentation](https://jupyterbook.org/en/stable/advanced/windows.html) suggests using [Windows Subsystem for Linux 2 (WSL2).](https://learn.microsoft.com/en-us/windows/wsl/install) 
