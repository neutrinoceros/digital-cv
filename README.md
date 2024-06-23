# Clément M.T. Robert (@neutrinoceros)

## About me

I am a research software engineer, holding a PhD in astrophysicist.
I am passionate about software development and maintenance, and an advocate for
free open-source software.

## Experience in software development and maintenance

I am currently under contract with the Astropy Project for which I provide user
and developer support.

I am also a volunteer co-maintainer of several popular open source
libraries within the scientific Python landscape,
first and foremost [`yt`](https://yt-project.org) (since 2019) and the
various parts of its ecosystem ([`unyt`](https://github.com/yt-project/unyt),
[`cmyt`](https://github.com/yt-project/cmyt),
[`ewah_bool_utils`](https://github.com/yt-project/ewah_bool_utils)), as well as
[`h5py`](https://github.com/h5py/h5py) (since 2024) and
[`cmasher`](https://github.com/1313e/CMasher) (since 2023).

Within these organizations, I collaborate with many different actors (co-maintainers,
users, developers of dependencies and dependent code, ...). `astropy` and `yt` integrate
and inter-operate with many other popular libraries in the ecosystem (most proeminently
`numpy` and `matplotlib`, but also each other). Maintaining this complex compatibility
network gave me the opportunity to collaborate (report, discuss, and fix problems) with
most of these actors.

In addition to contributing features and bug fixes, I volunteer my time to improve and
maintain the health of the project via
- building and testing infrastructures
- packaging and distribution automation
- code quality (APIs consistency and user experience)
- documentation


### Notable projects and pull requests

I wrote over 3000 pull requests and maintained a couple dozen projects of
various sizes since I joined GitHub. Here's a selected sample

- [I rewrote 99% of yt's gateway function to improve user
  experience](https://github.com/yt-project/yt/pull/2695)
- During my post-doc, I wrote various tools to facilitate my daily tasks, which are all
  open source
    - [a Python library for reading and writing configuration files](https://github.com/neutrinoceros/inifix)
    - [a command-line interface for my utility scripts](https://github.com/neutrinoceros/idefix_cli)
    - [a Cython-powered post-processing tool to reduce simulation
      data](https://github.com/neutrinoceros/gpgi)
    - [a new extension for `yt`](https://github.com/neutrinoceros/yt_idefix)
- Other than projects I started, maintained or regularly participated in,
  I have, most notably, successfully contributed patches and documentation to
  [`matplotlib`](https://github.com/matplotlib/matplotlib/pulls?q=is%3Apr+sort%3Aupdated-desc+author%3Aneutrinoceros+is%3Aclosed),
  [`numpy`](https://github.com/numpy/numpy/pulls?q=is%3Apr+sort%3Aupdated-desc+author%3Aneutrinoceros+is%3Aclosed),
  [`cartopy`](https://github.com/SciTools/cartopy/pulls?q=is%3Apr+sort%3Aupdated-desc+is%3Amerged+author%3Aneutrinoceros),
  [`sympy`](https://github.com/sympy/sympy/pulls?q=is%3Apr+sort%3Aupdated-desc+is%3Amerged+author%3Aneutrinoceros),
  [`pyupgrade`](https://github.com/asottile/pyupgrade/pulls?q=is%3Apr+sort%3Aupdated-desc+is%3Amerged+author%3Aneutrinoceros)
  and
  [`CPython`](https://github.com/python/cpython/pulls?q=is%3Apr+sort%3Aupdated-desc+is%3Amerged+author%3Aneutrinoceros).


## Academic experience

### Post-doc (2020-2023)
I am currently employed as a contractual researcher at [IPAG](https://ipag.osug.fr),
where I am collaborating with Geoffroy Lesur on the development of the GPU-accelerated
Magneto-Hydrodynamics (MHD), High Performance Computing (HPC) simulation code
[Idefix](https://github.com/idefix-code/idefix). Idefix is written in `C++` and powered
by the `Kokkos` library.

I developed a new physics module for Idefix*, to combine on-grid hydrodynamics with
super-particles representing astrophysical "dust" (solid matter, not subject to
pressure).

>*: This module is not available in the public version of Idefix at the moment.


### PhD in Astrophyics (2016-2020)
> Doctorat en Sciences de la Terre et de L'Univers, *Université de Nice*, **2020**

My thesis was supervised by Héloïse Méheut and François Ménard.
I worked on hydrodynamics of planet-forming disks. Specifically, I studied the migration
of giant planets via planet-disk interactions, and I worked on connecting simulations to
observations in the context of dusty clumps formed by giant vortices.

I produced, developed, and analyzed hydrodynamics simulations with Fargo (`C`, then
`C++`) and MPI-AMRVAC (`Fortran90`). I used mcfost (`Fortran90`) to produce synthetic
observations of my models, using a glue code I developed in `Python` to automate the
conversion pipeline.

In addition to the features I needed for my own research, I contributed to all codes I
used with tests, automation, and bug fixes.

### Bibliography
The list of scientific publications, including my thesis, that I lead or contributed to,
is currated on [my orcid page
(0000-0001-8629-7068)](https://orcid.org/0000-0001-8629-7068).

## Education

### Master's: Astronomy and Astrophysics
> Master d'Astronomie, Astrophysique et navigation spatiale, *Université Paris VII*, **2016**

### Bachelor's: Fundamental Physics
> Licence de Physique Fondamentale, *Université Paris VII*, **2014**

### Preparatory classes
> Physique & Science pour l'Ingénieur, *Lycée Raspail (Paris)*, 2013
> Physique, Chimie  & Science pour l'Ingénieur, *Lycée Lavoisier (Paris)*, 2011
