

# High-Resolution Channel Configuration with NEMO v4.2

This repository contains the necessary scripts and code modifications to the NEMO ocean model and its sea-ice component, SI3, to reproduce the high-resolution channel configuration. The configuration has been developed and executed using **NEMO version 4.2**.

## Contents
- **Scripts**: Preprocessing, configuration, and submission scripts to set up and run the channel configuration.
- **Code Modifications**: Custom changes made to NEMO and SI3 to enable the specific dynamics and resolution required for the high-resolution channel setup.
- **Bug Fixes**: Includes files that must be added to the `MY_SRC` directory to address known issues in NEMO v4.2 related to surface stress and flux calculations.

## Requirements
- **NEMO v4.2**: Ensure that this version of the model is installed. Refer to the official [NEMO documentation](https://www.nemo-ocean.eu) for installation guidelines.

## How to Use
Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

Compile the model using the instructions in the NEMO documentation. 

