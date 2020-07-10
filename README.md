# GNU Octave for KISS Linux

This repository contains packages for GNU Octave and its dependencies that aren't in the community repos.


## Packages

`octave`: minimal Octave, no gui but plotting abilities.  
`octave-gui`: same as above but with the Qt gui.

Planned: `octave-full`

## Requirements

This repository requires the community repos and a fortran compiler.

### Enable gfortran in the base gcc package

In `/var/db/kiss/repo/core/gcc/build`, edit the `./configure` command to add `fortran` to the enabled languages list then rebuild gcc.
