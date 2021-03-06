# Quasars Probing Galaxy Clusters

An astrophysical coding based project focused on processing quasar spectral data from the [SDSS eBOSS Data Release 14](https://dr15.sdss.org), and combining these results to analyse data from the [Clusters Around Radio-Loud AGN (CARLA) Spizter Survey](http://arxiv.org/abs/1304.0770) in order to study the environments of proto galaxy clusters in the distant Universe. The full project write-up can be found in the [Research Project Report pdf file](Research_Project_Report.pdf).

## Motivation and Project Aims

Through studying the effect of intervening neutral hydrogen in the spectra of high redshift QSO we have been able to advance current techniques used to understand protoclusters
that coalesce under gravity to form the cosmic structures we see in the universe today. This
project analyses the preceding methods by which these structures have been studied, as well as
detailing a new line of research, first crafted for use in the study of other QSO in the line of sight
to background quasars. This work utilised this quasar probing technique
to study protoclusters by measuring absorption of their neutral hydrogen content in the spectra of
background quasars.

## Outline of Code

The code of the project is split into two main components, Continuum Fitting and Spectrum Stacking. The original spectra are first fit using the scripts in the Continuum Fitting folder in order to produce fitted spectra. The fitted spectra are then stacked to produces results, a sample of the various scripts used to do this can be found in the Stacking Scripts folder. These scripts are generic outlines of multiple versions of code used to produce all of the final results for the scientific data. Due to the sheer volume of spectral data involved in this project, only a small sample of approximately 20 spectra (original and their fitted counter-parts) are showcased in this repository.

## Authors

* **Jason Lunn** - [jasonleelunn](https://github.com/jasonleelunn)
* **Alex Woods** - [alexwoodsy](https://github.com/alexwoodsy)

## Acknowledgments

* University of Nottingham - Department of Physics and Astronomy
* Assistant Professor Dr Nina Hatch (Project Supervisor)

## Example Spectra Stacking Figures

The two figures below visualise the spectral flux stacking method used in this project. Multiple continuum fitted quasar sight line spectra are aligned according the the galaxy cluster's rest frame, and then averaged together in an attempt to find a Lyman alpha absorption signal.

![Unstacked Quasar Spectra for CARLA Cluster J085051.80+152215.0](Stacking_Figures/J085051\.80\+152215\.0_unstacked.svg "Unstacked Quasar Spectra for CARLA Cluster J085051.80+152215.0")
![Stacked Quasar Spectra for CARLA Cluster J085051.80+152215.0](Stacking_Figures/J085051\.80\+152215\.0_stacked.svg "Stacked Quasar Spectra for CARLA Cluster J085051.80+152215.0")

## Changelog

* Uploaded all relevant files
* Updated README

## Built With

```
* Python
* TOPCAT
