# Donors for Charity

Our goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000
see notebook fopr details.

## Environment

run the following command:

```BASH
brew install cmake
```

Please use either the [requirements](requirements.txt) file and run the following commands...

```BASH
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

... or you can make use of the [`Makefile`](Makefile) we included in this project. 

```BASH
make setup
```

