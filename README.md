# cpu-gpu-utilisation-logging-python

Log CPU and GPU utilisation at regular intervals, with Python.

Why? So you can save the utilisation to disk and look at it later.

Also, when you only have a single point of access to a server (for instance you have a notebook running on Kaggle, Google Colab, or similar), you can spin up a background process which logs the CPU and GPU utilisation while the rest of your notebook is running without disrupting it.
It can otherwise be difficult to check on the GPU, since you can't open a second connection (or screen, etc) to the server and tab over to it while the code is running.

An alternative [bash/shell implementation is also available](https://github.com/scottclowe/cpu-gpu-utilisation-logging).

## Demo

A Kaggle kernel showing the CPU and GPU logger in action is available here:
https://www.kaggle.com/scottclowe/cpu-and-gpu-usage-logging-demo

## Dependencies

- Python
- nvidia-smi

An alternative [bash/shell implementation is also available](https://github.com/scottclowe/cpu-gpu-utilisation-logging).
