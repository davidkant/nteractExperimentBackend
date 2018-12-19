# nCoda-nteract Application Playground Backend

This repository describes the configuration of playground Python kernels for nteract music applications.

Click "binder" below, and binder will use this repository's files to set up a Python kernel in a Docker container for you; it will include everything in the apt and requirements files in this repo, and you can interact with it using the classic jupyter notebook (the interface that will open when you click the banner below).

To try out some [Abjad](http://abjad.mbrsi.org/), you'll need to make a new Python3 notebook and start by executing the following two lines in a cell:

```
%load_ext abjadext.ipython
import abjad
```

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/nCoda/nteractExperiment/master)

(*To add: music21, numpy, librosa, @davidkant's music AI Python library*)
