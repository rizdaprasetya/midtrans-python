# Midtrans

To install the package:

```
pip install midtrans
```

### For maintainer

To install on development mode:

```
python setup.py develop
```

To install on local machine:

```
pip install .
```

To install the package with a symlink:

```
pip install -e .
```

To make the distribution, execute:

```
python setup.py sdist
```

To make the distribution, and publish it so other can install without cloning this repository:

```
python setup.py register sdist upload
```

### Testing

The library test units are written in pytest. After successful install of
`pytest`, just simply execute `pytest` at the root directory to run
the unit testings.