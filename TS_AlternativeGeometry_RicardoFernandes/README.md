# Alternative Trigger Scintillator

## Summary of my work

I have been working on updating and optimizing the Track Producer (`TrigScint/src/TrigScint/TrigScintTrackProducer.cxx`), especially for the alternative geometry (`ldmx-vertTS-v14-8gev`). Please see my commit from July 2, 2026:

https://github.com/LDMX-Software/ldmx-sw/commit/cd380014bc29c83ff0834eff87641f06c194ab4b

There is also an example configuration file for this geometry (`TrigScint/exampleConfigs/runTSvert.py`).

My main focus was comparing the Trigger Scintillator (TS) performance between `ldmx-vertTS-v14-8gev` and `ldmx-det-v14-8gev`.

## How to run

Follow the LDMX tutorial and generate TS data for both geometries. For the alternative geometry, refer to the example configuration file mentioned above.

## Analysis files

I performed the analysis using Jupyter Notebooks. You can follow the LDMX tutorial for instructions on how to run them.

For more details, open `analysis-code_example.ipynb`. The file is not organized in the most readable way, as they are intended only as an example of how to run the analysis. Most of the code consists of Python plotting and data analysis routines.
