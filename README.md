## open-dis-python

[![Build Status](https://travis-ci.org/open-dis/open-dis-python.svg?branch=master)](https://travis-ci.org/open-dis/open-dis-python)
[![PyPI Version](https://shields.mitmproxy.org/pypi/v/opendis.svg)](https://pypi.org/project/opendis/)

A Python 3 implementation of the Distributed Interactive Simulation (DIS) 7 standard.
Initially generated by [xmlpg](https://github.com/open-dis/xmlpg).

## Library installation

For users who want to add it as a dependecy of their own projects:

```bash
pip install .
```

For developers of this library:
```bash
pip install -e .
```

## Run examples

Run a receiver:

```bash
cd examples
python3 dis_receiver.py
```

In another terminal, run the sender:

```bash
python3 dis_sender.py
```

You should also see the traffic on the net in Wireshark on your localhost interface.

Press `Ctrl+\` to stop the process.

## Documentation

You can auto generate API docs from the project source code:
```bash
pip install pdoc
pdoc --html --html-dir docs opendis
```

The docs will be generated in the `docs/opendis` folder.
