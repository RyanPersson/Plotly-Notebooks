### Install Instructions:

1. Install your preffered version of Conda. I personally prefer [miniconda](https://docs.conda.io/en/latest/miniconda.html).

2. Run `git clone https://github.com/RyanPersson/Plotly-Notebooks.git`

3. `cd Plotly-Notebooks`

4. Run `conda env create --file environment.yml` (equivalent of npm install, environment.yml is like pacakge.json in practice).

5. Run `conda activate linear-algebra-class`

6. Run `jupyter notebook`

7. Navigate to `localhost:8888` in your browser. (or use the link with the token which `jupyter notebook` supplies)

8. go to `plotly-spherical-harmonics.ipynb`

9. Execute all jupyter cells in sequence by running `Shift+Enter`

10. Set `m` & `n` to whatever values & run to see cool spherical harmonics!