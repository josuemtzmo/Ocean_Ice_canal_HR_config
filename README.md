

# High-Resolution Channel Configuration with NEMO v4.2

This repository contains the necessary scripts and code modifications to the NEMO ocean model and its sea-ice component, SI3, to reproduce the high-resolution channel configuration. The configuration has been developed and executed using **NEMO version 4.2**.

## Contents

- **copy\_out\_of\_scratch.pbs**: Function to copy the model output from a HPC scratch to storage, and modify the frequency of the output.
- **cpp\_ICE\_CANAL\_UHR.fcm**: CPP flags to build the NEMO configuration.
- **EXP\_HR**: Folder containing files of the configuration (namelists and XIOS output files)
- **MY\_SRC**: Folder containing modifications to NEMO source. These files are required since they  address known issues in NEMO v4.2 related to surface stress and flux calculations.
- Make sure to create the `BLD` and `WORK` folders required for running an experiment in NEMO


## Requirements
- **NEMO v4.2**: Ensure that this version of the model is installed. Refer to the official [NEMO documentation](https://www.nemo-ocean.eu) for installation guidelines.

## How to Use
Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

Compile the model using the instructions in the NEMO documentation. 

