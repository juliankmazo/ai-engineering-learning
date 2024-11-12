# Building Micrograd

This project is a reimplementation of Andrej Karpathy's micrograd, a tiny autograd engine that implements backpropagation over a dynamically built DAG.

## Prerequisites

Before running this project, you need to:

1. Install Python 3.8 or higher
2. Install Graphviz on your system:

### Installing Graphviz

- **Ubuntu/Debian**:

  ```bash
  sudo apt-get install graphviz
  ```

- **macOS**:

  ```bash
  brew install graphviz
  ```

- **Windows**:
  Download and install from [Graphviz Downloads](https://graphviz.org/download/)

## Setup Instructions

The virtual environment is already created. You just need to:

1. Activate the virtual environment:

- **Unix/macOS**:

  ```bash
  source .venv/bin/activate
  ```

- **Windows**:
  ```bash
  .\.venv\Scripts\activate
  ```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Running the Project

Once everything is set up, you can open and run the Jupyter notebook:

```bash
jupyter notebook main.ipynb
```

## Requirements

See `requirements.txt` for the complete list of dependencies.

## License

This project is open source and available under the MIT License.
