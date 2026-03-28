# Installation

## Package install

Install the Navigo package from the main code repository, not from this documentation repository.

```bash
git clone https://github.com/fym0503/Navigo-release.git Navigo-release
cd Navigo-release
pip install -r requirements.txt
pip install -e .
```

## Build the documentation locally

```bash
pip install -r requirements.txt
sphinx-build -b html . _build/html
```
