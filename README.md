# FOURIER-PROPAGATE-SIM

## Overview
FOURIER-PROPAGATE-SIM is a Python script for simulating the propagation of light through an optical system using Fourier optics principles. It provides a framework for analyzing the behavior of light waves as they pass through various optical elements such as lenses, apertures, and masks.

## Features
- **Telescope Pupil Modeling**: Define circular or elliptical apertures for the telescope pupil.
- **Apodization**: Apply Gaussian apodization to modify the amplitude distribution of the telescope pupil.
- **Illuminance Profile**: Access and incorporate illuminance profiles from external files for different wavelength bands.
- **Focal Plane Visualization**: Visualize the focal plane to observe the intensity distribution after Fourier transformation.
- **Pupil Plane Visualization**: Visualize the pupil plane to observe the amplitude distribution at the telescope pupil.
- **Dynamic Apodization Adjustment**: Dynamically adjust the apodization function and observe its effect on the optical system.

## Usage
1. **Setup**: Mount Google Drive to access external files containing illuminance profiles.
2. **Telescope Pupil Definition**: Define the shape and apodization of the telescope pupil using the provided functions.
3. **Illuminance Profile Selection**: Choose the desired wavelength band and load the corresponding illuminance profile.
4. **Optical System Simulation**: Simulate the propagation of light through the optical system and observe the results in the focal and pupil planes.
5. **Dynamic Adjustment**: Optionally, dynamically adjust the apodization function and observe its effect on the optical system.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Pandas
- SciPy

## File Structure
- `Illum_Iband.txt` and `Illum_Rband.txt`: External files containing illuminance profiles for specific wavelength bands.

## Acknowledgments
This project was developed as part of [Narit Astronomical Research Institute](https://narit.or.th/en/) (NARIT)'s simulation toolkit for optical systems.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
