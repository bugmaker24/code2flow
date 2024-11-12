
Installation
------------

```bash
cd code2flow
pip install .
```

If you don't have it already, you will also need to install graphviz. Installation instructions can be found [here](https://graphviz.org/download/).



Usage
-----

To generate JSON by a python script and depth

```bash
code2flow --downstream-depth depth --target-function "(global)" -o out.json mypythonfile.py
```

To generate a DOT file, run something like:

```bash
code2flow --downstream-depth depth --target-function "(global)" mypythonfile.py
```


