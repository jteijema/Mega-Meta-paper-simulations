# Mega-Meta-paper-simulations

A code repository for:
>Active learning-based Systematic reviewing using switching classification
>models: the case of the onset, maintenance, and relapse of depressive disorders


## Abstract

Systematic reviews and meta-analyses are top of the bill in research. However,
the screening phase requires an enormous effort in reading and labeling
thousands of papers identified via systematic search. Active learning-aided
systematic reviewing offers a solution by combining machine learning algorithms
with user input to reduce screening load. This study explores the performance of
these algorithms and different ways to apply them. This study is subdivided into
four separate studies evaluating and improving this active learning pipeline.
First, the performance and stability of the active learning pipeline were
assessed via simulations and re-analysis of the outcome. Secondly, a
convolutional neural network was developed to improve upon available machine
learning algorithms. Thirdly, the performance of different algorithm
combinations was tested and compared. Finally, algorithm switching models were
built for increased performance. The study concludes with proposals for
improving active learning-aided systematic reviews based on combinations of the
four studies.


## Data

The data used for this paper can be found at https://osf.io/r45yz/. The file is
called `Brouwer_2019_deduplicated.xlsx (Version: 1)`.


## Contents

Folders:
- `plots` - A folder containing generated images.
- `simulation_output` - This folder is available at https://osf.io/3h2tw/ for NB
  simulations files, and https://osf.io/zngmy/ for LR simulations files.
- `simulation_states` - A folder containing the simulation states for different
  simulation runs.
- `results` - Contains files with statistics from the simulations.

Files:
- `state_file_processor.ipynb` - A file with different modules used for
  processing state files.
- `simulations.sh` - A shell script containing commands all ran simulations


## Simulation results
All simulation results can be found at https://osf.io/3h2tw/.


## Licence

The content in this repository is published under the MIT license.


## Contact

For any questions or remarks, please contact the corresponding author: 
>Jelle Teijema: Department of Methods and Statistics, Utrecht University,
>3508TC, Utrecht, The Netherlands; E-mail address: j.j.teijema@uu.nl.

For questions regarding this repository, use the
[issue](https://github.com/JTeijema/Mega-Meta-paper-simulations/issues) tab.
