# Template code
This is repository that can be used as a template to use with the [main code](https://gitlab.cern.ch/cms-phys-ciemat/nanoaod_base_analysis.git) of the NanoAOD-base-analysis, which aims to process NanoAOD datasets, allowing to generate different root files, histograms and plots with the desired selection of events, variables and branches.

Make a fork of this repository, so you can use it as an example for your own analysis.

## User guide:

Information about the code, how to install it, setting a configuration to use it and more useful information about this framework cand be found [here](https://nanoaod-base-analysis.readthedocs.io).

## Installation

```
git clone git@github.com:jaimeleonh/nba_template.git
cd nba_template
git clone https://gitlab.cern.ch/cms-phys-ciemat/nanoaod_base_analysis.git --branch py3 nanoaod_base_analysis/
source setup.sh
law index --verbose #to do only after installation or including a new task
```
