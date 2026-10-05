# Li-ion Battery Health: SoH and RUL Prediction

## Project Overview
Prediction of State of Health (SoH) and Remaining Useful Life (RUL) for
Li-ion cells, using the NASA Battery Data Set (PCoE).

- **SoH:** current capacity divided by nominal capacity.
- **RUL:** number of cycles remaining before end of life.
- **End of life:** 30% capacity loss (2 Ah → 1.4 Ah).

## Motivation
Every cycle, the SEI layer on the graphite anode cracks as the graphite expands and contracts during lithium intercalation, then reforms and consumes cyclable lithium. A thicker SEI also raises internal resistance: the voltage drops more, the cell heats up and apparent capacity falls. SoH and RUL are how this chemistry shows up in the data. I worked out this mechanism from the chemistry before reading the literature, and this project tests it against real cells.

## Dataset
- **Source:** NASA Prognostics Center of Excellence (PCoE), Battery Data Set. Cells B0005, B0006, B0007, B0018.
- **Access:** [NASA Prognostics Center of Excellence (PCoE) Battery Data Set - Data Set 5](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
- **Citation:** B. Saha and K. Goebel (2007). "Battery Data Set", NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA.
- **Format:** charge, discharge and impedance cycles stored in nested
  MATLAB (.mat) structures.

## Methods
_To be filled._

## Status
**In progress.** Data exploration is starting, no results yet.

## Key Results
_To be filled._

## Future Work
_To be filled._

## Structure
_To be filled._