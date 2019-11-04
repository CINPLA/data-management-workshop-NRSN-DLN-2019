# data-management-workshop-NRSN-DLN-2019
Resources for the workshop


# Installation
Install GIT [Windows](https://git-scm.com/downloads)

Install [Anaconda](https://www.anaconda.com/distribution/) with Python 3.7 version

Install [Github Desktop](https://desktop.github.com/), if you do not like to use the terminal so much.
 * [Setup](https://help.github.com/desktop/guides/getting-started-with-github-desktop/setting-up-github-desktop/)

Install [Atom](https://atom.io/)

## For Windows users
You need build tools for Microsoft visual C++, if not already installed go to
https://visualstudio.microsoft.com/downloads/, click "Tools for Visual Studio 2019"
and download the bottom most alternative ("Build Tools for Visual Studio 2019").
Then start the downladed app and follow instructions.
Note: you only need the build tools when prompted in the app.

### Cloning this repository
This can either be done with Github Desktop
or with a terminal. When we say terminal, in Windows we mean Anaconda prompt.
However, all code that starts with `git` can be done with Github Desktop.

Make a folder where you want to have it, e.g. c:\apps\

With the terminal run

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
cd c:\apps
git clone https://github.com/CINPLA/data-management-workshop-NRSN-DLN-2019.git
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

### Anaconda
Windows: Search for anaconda and open Anaconda prompt.

Mac: open a terminal

Create a new Anaconda environment with:

```
conda env create -f environment.yml
```

Then, enter the environment using

```
activate datamanagement
```

If the environment needs to be updated use
```
conda env update -f 
```
### Ipywidgets in Jupyter
If widgets does not show you might have to run the following, and restart the notebook

```
jupyter nbextension install --py widgetsnbextension --user
```

<!-- Install GIT [LFS](https://git-lfs.github.com/)

[Nice intro video to LFS](https://www.youtube.com/watch?v=uLR1RNqJ1Mw) -->
