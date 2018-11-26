## Overview

This project is a small exploration of a class which wraps the
roaringbitmaps compressed bitmap implementation to employ variable
sampling to control the size of the structure. 

## Getting Started

this assumes you have docker and kubernetes working, ie that `docker`
and `kubectl` are working. if that is the case do the following to
generate the docker images, create the k8 deployments and services:

```
$ virtualenv .py
$ pip install -r requirements.txt
```

## Running

to check out the notebook:

```
$ jupyter notebook
```

and run the buffers from top to bottom.







