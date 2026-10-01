The raw data used in the article “Magnetic order and novel quantum criticality in the strongly interacting quasicrystals”.

# Data for the manuscript

This repository contains the numerical data used to generate the figures in the main text and Supplemental Material of the manuscript.

## Directory structure

- `main_data/` contains the data corresponding to the figures in the main text.
- `SM_data/` contains the data corresponding to the figures in the Supplemental Material.

The filenames are labeled according to the corresponding figure numbers in the manuscript.

## Note on the Binder-ratio convention

In the main text, the Binder ratio is defined as

\[
R = \frac{\langle M_2\rangle^2}{\langle M_4\rangle}.
\]

However, the Binder-ratio data stored in the following two files use a different, but equivalent, convention:

- `main_data/Fig5_a.txt`
- `SM_data/FigS4.txt`

For these two files, the quantity reported is the conventional Binder cumulant

\[
U = 1-\frac{\langle M_4\rangle}
{3\langle M_2\rangle^2}.
\]

The two definitions are related by

\[
U = 1-\frac{1}{3R},
\]

or equivalently,

\[
R=\frac{1}{3(1-U)}.
\]

Thus, the data in `Fig5_a.txt` and `FigS4.txt` are presented using the \(U\) convention rather than the \(R\) convention adopted in the main text. This difference is purely a matter of convention and does not affect the determination of the crossing point or the associated finite-size scaling analysis.

## Data usage

The data files are provided in plain-text format. Column definitions, when necessary, are given in the corresponding file headers.

For questions regarding the data or analysis, please contact the authors.
