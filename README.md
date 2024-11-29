# Git exercises
***by: Francesco Turini***

Git Exercises from the Bicocca Courses, git repository aviable [here](https://github.com/fturini98/Git_exercises.git).

## Egocentric:
For make sure that the rules must be passed to push, go to **GitHub**, and in the repository **settings/Branches** enable the following rules in the **Protect matching branches** for the main branch:
- Requires status checks to pass before merging
- add **only** the action: Egocentric

### To push on this branch:
To push on the main you mast pass by a pull request:
- use a other barnch as: developing
- push changes to it
- ask for a pull request
- pass the actions test
- then merge on GitHub

# Ditch Overleaf
Using this github workflow is possible to generate a pdf during the pull request starting form the file in the **RawTex**:
- The main file is the main.txt file, to change it, you mast change:
    - it's name in the *RawTex* folder
    - the **FILE** variable with the new name in the **Lezione6.yml** file

The **generated pdf** will be aviable in the **actions' artifacts folder** 