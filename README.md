# Open OnDemand RStudio App for Delta

Interactive RStudio app for Delta's Open OnDemand portal

## Requirements

On compute nodes (NOT the Open OnDemand node):

 - [Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) and relevant modules for MATLAB
 - Apptainer

## Installation

 1. Clone this app to OOD's app directory (/var/www/ood/apps/sys by default).
 2. Build the Apptainer image and place it into a path that matches the command in `template/script.sh.erb`.
 3. Adjust cluster name and Lmod module names in form.yml to match the system.

## Acknowledgements

 - [OSC/bc_osc_jupyter](https://github.com/OSC/bc_osc_jupyter)
 - [matlab-proxy](https://github.com/mathworks/matlab-proxy)
