# A Docker Environment for `Pytket` and its Interfaces

## Architecture

Heavily based off of previous work from the [Hephaestus series](https://github.com/Quantum-Computing-at-Davis/Hephaestus) of Docker images.

Contains the following packages already installed and ready to use

* `networkx`
* `jupyter`
* `matplotlib`
* `pytket`
  * `pytket-qiskit`
  * `pytket-cirq`
  * `pytket-pyquil`
  * `pytket-projectq`
  * `pytket-pyzx`
  * `pytket-aqt`
  * `pytket-honeywell`
  * `pytket-qsharp`

## Usage

Copy and paste `Dockerfile` and `docker-compose.yml` into a folder you want to use to experiment/develop with Pytket. 

Then just run:

```
docker-compose up
```

and copy-paste the Notebook URL that comes up in the terminal.