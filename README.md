# TON-Pool Miner

Miner from [TON-Pool.com](https://ton-pool.com/)

## Instructions

You need to have Python 3 and packages `pyopencl`, `numpy`, and `requests` installed.

For Linux users, you can run `pip3 install pyopencl numpy requests` to install the packages. If you are running old version of Python, try `pip3 install "pyopencl<2018.3"` and `pip3 install "numpy<1.15"`.

For Windows users, you can run `pip3 install numpy requests` to install the later two packages. You need to go to https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopencl and download an `pyopencl` binary.

## Usage

```
python3 miner.py [pool addr] [wallet address]
```

## License

GPLv3