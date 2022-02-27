class: center, middle, inverse

# Reproducibility and FAIR principles

---

## Reproducibility and FAIR principles

<img src="img/turing-way/8-fair-principles.jpg" style="width: 50%;"/>

.cite[(c) [Scriberia](http://www.scriberia.co.uk) for [The Turing Way](https://the-turing-way.netlify.com), CC-BY.]

For a discussion of FAIR in the context of software, see:

https://softdev4research.github.io/4OSS-lesson/.

---

## FAIR principles and data visualization

Which problems can you anticipate?

--

### Findable

.quote["On which of my external hard-drives is my script?"]


### Accessible

.quote["Can you please give me access to your plotting scripts?"]


### Interoperable

.quote["How can I convert this file format?"]


### Reusable

.quote["I wish I could reuse this visualization pipeline for my new data!"]

---

## Reproducible and reusable plots

- Ask yourself: what problems do I anticipate when rerunning this in 12 months?
- Document all tools and dependencies used .emph[with versions]

---

class: center, middle, inverse

# Reproducible and reusable plots

---

## Jupyter notebooks

.left-column50[
<img src="img/jupyter/medicean-stars.png" style="width: 50%;"/>

**One of the first notebooks: Galileo's drawings of Jupiter and its Medicean
Stars** from Sidereus Nuncius. Image courtesy of the History of Science
Collections, University of Oklahoma Libraries (CC-BY).
]

.right-column50[
- **Code, text, equations, figures, plots**, etc. are interleaved, creating a *computational narrative*.
- [*"an environment in which users execute code, see what happens, modify and
  repeat in a kind of iterative conversation between researcher and
  data"*](https://www.nature.com/articles/d41586-018-07196-1)
- The name "Jupyter" derives from Julia+Python+R, but today Jupyter kernels
  exist for [dozens of programming languages](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels).
]

---

## Example

.left-column50[
<img src="img/jupyter/gravity.jpg" style="width: 60%;"/>

Discovery of gravitational waves.
]

.right-column50[
As a case example, let us have a look at the analysis published together with the
discovery of gravitational waves. [This
page](https://losc.ligo.org/tutorials/) lists the available analyses
and presents several options to browse them.

- A quick look at short segments of data can be found at
  [https://github.com/losc-tutorial/quickview](https://github.com/losc-tutorial/quickview)
- The notebook can be opened and interactively explored
  using Binder by clicking the "launch Binder" button.
]

---

## Another example

.left-column50[
<img src="img/jupyter/activity_inequality.png" style="width: 100%;"/>

Stanford Activity Inequality Study.
]

.right-column50[
Researchers in the Stanford Activity Inequality Study measured daily
activity from cell phone tracking data for over 700,000 users in
different countries across the world.
- All data and notebooks are available at
  [https://github.com/timalthoff/activityinequality](https://github.com/timalthoff/activityinequality)

For **more examples**, head over to the [Gallery of interesting Jupyter
Notebooks](https://github.com/jupyter/jupyter/wiki).
]

---

## R Markdown

Same idea as in the Jupyter notebook.

Example:
- https://github.com/clauswilke/dataviz (the source code for https://clauswilke.com/dataviz/)
- Compare these two:
  - https://github.com/clauswilke/dataviz/blob/master/proportional_ink.Rmd
  - https://clauswilke.com/dataviz/proportional-ink.html

---

<img src="https://opendreamkit.org/public/images/use-cases/reproducible_logbook.png" style="width: 75%;"/>

.cite[Juliette Taka, Logilab and the OpenDreamKit project (2017), https://opendreamkit.org/2017/11/02/use-case-publishing-reproducible-notebooks/]

---

## .emph[Demo]: visualization pipeline on [Binder](https://mybinder.org/)

- Python/[Altair](https://altair-viz.github.io/) on [Jupyter](https://jupyter.org/) served via [Binder](https://mybinder.org/):
  https://github.com/bast/jupyter-binder-example
- R/[ggplot2](https://ggplot2.tidyverse.org/) on [RStudio](https://rstudio.com/)/[R Markdown](https://rmarkdown.rstudio.com/) served via [Binder](https://mybinder.org/):
  https://github.com/bast/rstudio-binder-example
- All plots in this slidedeck are reproducible on Jupyter notebooks: https://github.com/bast/data-visualization


### Other fantastic tools which I will not demonstrate

- [Data-Driven Documents](https://d3js.org/) with [gallery of examples](https://observablehq.com/@d3/gallery)
- Interactive plots with [Shiny](https://shiny.rstudio.com/gallery/)

---

## Progression

- Learn the very basics
  - Learn a bit of Python
  - Or R
- It can be a good idea to start learning right away in a notebook
  - Python: Jupyter
  - R: R Markdown in R Studio
- Later try Binder
- Later learn how to get a DOI for your Binder
- Now your plotting recipe can be cited and is reproducible

### This takes time and it is OK to take time
