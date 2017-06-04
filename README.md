# Notes on the Lefschetz fixed-point formula for étale cohomology
These are the sources of my lecture notes for a lecture in the seminar 
*An Overview of Deligne’s Proof of the Weil Conjecture*
at the University of Regensburg 2017, supervised by
[Prof. Dr. Moritz Kerz](http://www.mathematik.uni-regensburg.de/kerz/)
and 
[Dr. Federico Binda](https://fedebinda.wordpress.com/),
which was held at 12/06/2017.
The precise topic is *Poincaré duality and Lefschetz fixed-point formula*.

## Structure
- main file (for compilation): `lefschetz_formula.tex`
- bibliography: `lefschetz_formula.bib`

## Compilation
(Tested) preliminaries: `TeXLive 2016` distribution

For compilation execute the following commands

```bash
lualatex lefschetz_formula.tex
biber lefschetz_formula
lualatex lefschetz_formula.tex
```
