# SymPy Codegen Survey 2022

Analysis of the results from the SymPy codegen survey 2022.

The analysis can be seen at https://sympy.org/sympy-codegen-survey/

Note, the full data from the survey are not provided here because the survey stated that all responses would remain private.

## Generate HTML

HTML versions of the analysis notebook can be generated using [nbconvert](https://nbconvert.readthedocs.io/en/latest/index.html).

### With Code

Run::

```bash
$ jupyter nbconvert --to=html analysis.ipynb --out=docs/analysis-with-code.html
````

### Without Code

Run::

```bash
$ jupyter nbconvert --to=html --no-input analysis.ipynb --out=docs/analysis.html
```
