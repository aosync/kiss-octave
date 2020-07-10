# GNU Octave for KISS Linux

This repository contains packages for GNU Octave and its dependencies that aren't in the community repos.


## Packages

`octave`: minimal Octave, no gui but plotting abilities.  
`octave-gui`: same as above but with the Qt gui.

Planned: `octave-full`

## Requirements

This repository requires the community repos and a fortran compiler.

### Enable gfortran in gcc

Go to your personal repo directory and fork gcc with `kiss fork gcc`, then go into the build file and set fortran as the enabled language in the `./configure` command. Then build and install that package.
