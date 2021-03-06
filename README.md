# Code Miner Toolkit

* `apisan-to-salento.py`: converts a trace from APISan to Salento.
* `c-to-salento.py`: takes an archive of compilable C source files and produces Salento traces.
* `salento-filter.py`: removes terms from a given Salento JSON dataset; can use IDF, stop-words, and vocabulary files.
* `salento-repl.py`: analysis a Salento JSON dataset for anomalies with a REPL user interface.
* `salento-split.py`: splits a Salento JSON dataset into K parts or by package name.
* `salento-txt.py`: converts a salento trace into text (useful for interoperability purposes).
* `salento-trace-viz.py`: generates a GraphViz visualization of a given sequence.
* [`salento-train.py`](docs/salento-train.md): automates the various steps of training an API usage model. [Read the documentation of salento-train.](docs/salento-train.md)

# Documentation

* [Tutorial: On identifying anomalies in source code](docs/tutorial.md)
* [Tutorial: Training an API-Usage Model](docs/salento-train.md)
* [Salento 2.0: internal details about the anomaly metrics](docs/salento-2.0.md)
