# Amphetype

Amphetype is an advanced typing practice program.

## Installation

To install Amphetype, install a Python version between 3.8 and 3.11 (since [Amphetype requires Python 3.6+](https://gitlab.com/franksh/amphetype#gnulinux) and [Apple Silicon only works between 3.8 and 3.11 inclusive](https://github.com/pypa/cibuildwheel?tab=readme-ov-file#what-does-it-do); I chose 3.8.18) in `pyenv`:

```bash
pyenv install 3.8.18
```

Then create a virtual environment for Amphetype:

```bash
pyenv local 3.8.18
python -m venv .venv
source .venv/bin/activate
which python
# /path/to/amphetype/.venv/bin/python
pip install amphetype
chmod +x ./Amphetype.sh
```

## Running

You can run Amphetype by running the script I created.

```bash
./Amphetype.sh
```

["Your average speed -10 WPM and 97% accuracy is a good starting point."](https://forum.colemak.com/topic/2201-training-with-amphetype/)

## Credits

All credit goes to the [original project](https://gitlab.com/franksh/amphetype). This repo is just for my own use on my own machine.
