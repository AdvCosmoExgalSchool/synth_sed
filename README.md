# ACES24: Synthetic observations and SED fitting workshop


## Installation

Download the repo and cwd into it

Set up a python virtual environment

`python -m venv venv`

Activate the python virtual environment

`source venv/bin/activate`

Download synthesizer 

`git clone https://github.com/flaresimulations/synthesizer.git`

Install synthesizer into the current virtual environment

`pip install synthesizer/`

Download synthesizer test grids

`synthesizer-download --test-grids -d grids/`

Install other required modules:

`pip install -r requirements.txt`


## Synthetic observations

In this section you'll use the synthesizer synthetic observations pipeline to generate synthetic spectra of a galaxy from the TNG50 simulation (insert reference).


