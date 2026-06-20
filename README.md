# Leipzig2026
This repo contains a Jupyter notebook with code developed for the 2026 Leipzig Lexicography Master Class.

Goal of the code is to demonstrate a computational approach to semantics (PMI-SVD word embeddings), illustrated with a graph (in Bokeh) displaying the closest neigbors of four or five words for street/road/way in Sumerian. The data used are derived from [ORACC](https://oracc.museum.upenn.edu), in particular the collection of (Sumerian) literary texts ([epsd2/literary](https://oracc.museum.upenn.edu/epsd2/literary)) and the corpus of Old Babylonian laments and related texts ([obel](https://oracc.museum.upenn.edu/obel)).

If you wish to use and adapt the code for your own purposes, take the following steps.

- install [Anaconda](https://www.anaconda.com/download) (this installs Jupyter Lab and a host of other tools).
- download the [current repo](https://github.com/niekveldhuis/Leipzig2026) from Github and leave it in a directory of your choice.
- use the Terminal (OS X) or Anaconda Powershell Prompt (Windows; installed with Anaconda) to create the Leipzig_lexicography environment.
    - navigate to the directory you just created
    - create the environment with `conda env create -f environment.yml` (this takes some time).
    - activate the environment with `conda activate Leipzig_lexicography`.
- now open `jupyter lab` (still from your terminal/Anaconda Powershell prompt).

This will open a window where you can open and run the file `Leipzig2026.ipynb`.

About: 
- [Anaconda](https://www.anaconda.com/docs/getting-started/main)
- [environments](https://www.dataschool.io/intro-to-conda-environments/)
- [PMI-embeddings](https://github.com/asahala/pmi-embeddings/tree/main)

      
