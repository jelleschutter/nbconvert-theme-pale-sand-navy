# nbconvert-theme-pale-sand-navy
This is a theme for the jupyter nbconvert extension. Checkout an example [here](https://jelle.schutter.xyz/fhnw-ds-daw-fs2021-covid/).
## Installation
```bash
pip install nbconvert-theme-pale-sand-navy
```
## Usage
After installing the package you can select theme by passing the template parameter to the jupyter nbconvert command.
```bash
jupyter nbconvert --to html --template pale-sand-navy notebook.ipynb
```
It can also be easily used inside GitHub Actions like [here](https://github.com/jelleschutter/fhnw-ds-daw-fs2021-covid/blob/42fec69c401e61e2e0705edc4f212ae9c9e7fb68/.github/workflows/publish.yml#L20-L31).