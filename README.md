Installation guide:
1. Download [Anaconda](https://www.anaconda.com/download) using default options
2. Add the location of the Anaconda-installation to PATH in "environment variables".
3. Download [Git](https://git-scm.com/download/win)
4. Download [Visual Studio Code](https://code.visualstudio.com/download)
5. in VS-code, install the "Python" extension. 
6. Download [Visual Studio Community compiler](https://visualstudio.microsoft.com/vs/features/cplusplus/). Remember to add C/C++ features for installation.
7. Clone this repository from GitHub by i) opening the Anaconda Prompt, ii) navigating to the location on disk where you want the files cloned to, iii) write `git clone https://github.com/ThomasHJorgensen/NumericalSetup.git` and hit enter.
8. In Anaconda Prompt install required Python packages by typing `pip install econmodel consav`

To learn more about how this code uses OpenMP and NLopt to parallelize and solve numerical optimization problems, respectively, see [EconModelNotebooks](https://github.com/NumEconCopenhagen/EconModelNotebooks).
