# Imaging-Sorting Integration
Project that provides scripts to show exemplary integration of image generation, atom detection, and sorting

## Installation
Firstly, clone the project using
```
git clone https://github.com/jonaswinklmann/imaging-sorting-integration.git
```
Navigate to the project folder and execute
```
git submodule update --init --recursive
```
to pull all submodule recursively.

To execute the script, several additional packages are required:

1. State reconstruction: Either https://github.com/david-wei/state\_reconstruction or custom version https://github.com/jonaswinklmann/state\_reconstruction_performance
2. https://github.com/david-wei/libics
3. https://github.com/caps-tum/neutral-atom-imaging-simulation
