# Yarrowia Lipid Substrate GSM
This repository contains a Jupyter notebook and supporting files for investigating the effect of knocking out the ACC1 gene on the growth rate of Yarrowia lypoltica GSM iYLI647_corr.json. The model is tested using minimal medium and either glucose or oleic acid as sole carbon sources.

### Commands to run this project locally using a venv:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Dependencies:
The code in this repo was run using Python 3.10.2. Additionally cobra==0.26.2, pandas==1.5.3, and matplotlib==3.7.1 versions were used. Readers can consult the [CobraPy documentation](https://cobrapy.readthedocs.io/en/latest/getting_started.html) for details about how the simulations were completed.
