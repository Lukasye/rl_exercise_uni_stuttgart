# rl_exercise_uni_stuttgart
Welcome to the Reinforcement Learning lecture offered by the University of Stuttgart! Here you can find the programming assignment for the exercises. The configuration files for the virtual environments can be found in the `environments` directory. You can find more information on the [ILIAS](https://ilias3.uni-stuttgart.de/ilias.php?baseClass=ilrepositorygui&ref_id=3649799) page. Have fun!

If you have any questions about the installation, feel free to ask in the forum ~

## Installation
Clone the repository or download the configuration yaml file for your machine and install with the following command:
```
conda env create -f <name_of_os>.yml
```
For conda beginners: [Getting started with conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html)

## Troubleshooting
1. Numpy don't support `np.int` since version 1.20. You may use `np.int64` or `np.int32` instead or switch to an older version.
