Code for reproduction of the experiment presented in the article:

Longitudinal quantification of Fibre Bundle Capacity addresses structural connectivity biases in surgical resection cohorts
R.E. Smith, P. Pruckner, D.F. Abbott
Preprint pending

## Prerequisites

1.  Must have a valid *MRtrix3* installation,
    with commands present in `PATH`

2.  Must have a fairly recent Python3 installed.

    (If Python3 is too old,
    command "tabulate" may yield an ImportError)

3.  Commands must be executed from the root directory of the repository.

## Reproduction

1.  Command `build` populates directory `phantoms/`.

2.  Command `recon` populates directory `connectomes/`.

3.  Command `tabulate` generates a LaTeX table summarising the results of the demonstration.
