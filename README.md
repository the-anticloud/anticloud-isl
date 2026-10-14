# ISL

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-voxelization-lightgrey)

> Anticloud-hardened packaging of the upstream project `ISL` in category **VOXELIZATION**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** VOXELIZATION · **Upstream:** https://github.com/JWarmenhoven/ISLR-python · **Upstream pin:** `4100e941914519eea18385daadc9b3dab99ca8e2` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# ISLR-python
This project contains Python code for a selection of tables, figures and LAB sections from the first edition of the book <A target="_blank" href='https://www.statlearning.com/'>'An Introduction to Statistical Learning with Applications in R'</A> by James, Witten, Hastie, Tibshirani (2013).<P>

 For **Bayesian data analysis** using PyMC3, take a look at <A href='https://github.com/JWarmenhoven/DBDA-python'>this project</A>.

**2018-01-15**:<BR>
Minor updates to the project due to changes/deprecations in several packages. The notebooks have been tested with <A href='http://nbviewer.jupyter.org/github/JWarmenhoven/ISLR-python/blob/master/Notebooks/Python%20module%20versions.ipynb'>these package versions</A>. Thanks @lincolnfrias and @telescopeuser.
<P>

**2016-08-30**:<BR>
Chapter 6: I included Ridge/Lasso regression code using the new <A href='https://github.com/civisanalytics/python-glmnet'>python-glmnet</A> library. This is a python wrapper for the Fortran library used in the *R* package *glmnet*. 
<P>

<IMG src='Notebooks/ISL%20Cover%202.jpg' height=20% width=20%> <P>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%203.ipynb'>Chapter 3 - Linear Regression</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%204.ipynb'>Chapter 4 - Classification</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%205.ipynb'>Chapter 5 - Resampling Methods</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%206.ipynb'>Chapter 6 - Linear Model Selection and Regularization</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%207.ipynb'>Chapter 7 - Moving Beyond Linearity</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%208.ipynb'>Chapter 8 - Tree-Based Methods</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%209.ipynb'>Chapter 9 - Support Vector Machines</A><BR>
<A href='http://nbviewer.ipython.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Chapter%2010.ipynb'>Chapter 10 - Unsupervised Learning</A><P>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/ISL-python/blob/master/Notebooks/Simulate.expected.misclassification.rate.ipynb'>Extra: Misclassification rate simulation - SVM and Logistic Regression</A><P>
This great book gives a thorough introduction to the field of Statistical/Machine Learning. The book is available for download (see link below), but I think this is one of those books that is definitely worth buying. The book contains sections with applications in R based on public datasets available for download or which are part of the <A target="_blank" href="https://cran.r-project.org/web/packages/ISLR/index.html">R-package ISLR</A>. Furthermore, there is a Stanford University online course based on this book and taught by the authors (See <A target="_blank" href='https://www.edx.org/school/stanfordonline'>course catalogue</A> for current schedule).<P>
Since Python is my language of choice for data analysis, I decided to try and do some of the calculations and plots in Jupyter Notebooks using:

 - pandas
 - numpy
 - scipy
 - scikit-learn
 - python-glmnet
 - statsmodels
 - patsy
 - matplotlib
 - seaborn

It was a good way to learn more about Machine Learning in Python by creating these notebooks. I created some of the figures/tables of the chapters and worked through some LAB sections. At certain points I realize that it may look like I tried too hard to make the output identical to the tables and R-plots in the book. But I did this to explore some details of the libraries mentioned above (mostly matplotlib and seaborn). Note that this project is <STRONG>not a standalone tutorial</STRONG> and that you probably should have a copy of the book to follow along. Suggestions for improvement and help with unsolved issues are welcome!
See Hastie et al. (2009) for an advanced treatment of these topics.<P> 

#### References: 
James, G., Witten, D., Hastie, T., Tibshirani, R. (2013). <I>An Introduction to Statistical Learning with Applications in  R</I>,  Springer Science+Business Media, New York.
https://www.statlearning.com/

James, G., Witten, D., Hastie, T., Tibshirani, R. (2021). <I>An Introduction to Statistical Learning with Applications in  R, Second Edition</I>,  Springer Science+Business Media, New York.
https://www.statlearning.com/

Hastie, T., Tibshirani, R., Friedman, J. (2009). <I>Elements of Statistical Learning</I>, Second Edition, Springer Science+Business Media, New York.
http://statweb.stanford.edu/~tibs/ElemStatLearn/

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `Notebooks/`
- Snapshot size: **35 files**, **0 lines of code** (measured; see Benchmarks)
- Primary languages: `.csv` (21), `.ipynb` (10), `.md` (2), `.jpg` (1), `.xlsx` (1)
- Upstream commit pinned for this packaging: `4100e941914519eea18385daadc9b3dab99ca8e2`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

See Hastie et al. (2009) for an advanced treatment of these topics.<P>

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

James, G., Witten, D., Hastie, T., Tibshirani, R. (2013). <I>An Introduction to Statistical Learning with Applications in  R</I>,  Springer Science+Business Media, New York.
https://www.statlearning.com/

James, G., Witten, D., Hastie, T., Tibshirani, R. (2021). <I>An Introduction to Statistical Learning with Applications in  R, Second Edition</I>,  Springer Science+Business Media, New York.
https://www.statlearning.com/

Hastie, T., Tibshirani, R., Friedman, J. (2009). <I>Elements of Statistical Learning</I>, Second Edition, Springer Science+Business Media, New York.
http://statweb.stanford.edu/~tibs/ElemStatLearn/

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 35 |
| Lines of code | 0 |
| Dependency references | 0 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `ISL` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2017 Jordi Warmenhoven

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `ISL` (category: VOXELIZATION)
- **Upstream URL:** https://github.com/JWarmenhoven/ISLR-python
- **Pinned commit (SHA):** `4100e941914519eea18385daadc9b3dab99ca8e2`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`1c5d5bd2480fc74357b6eb2ec15e2da58d71fbcd4ea910cf1c74f198e1a61887`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

