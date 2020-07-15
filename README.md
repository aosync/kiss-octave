# GNU Octave for KISS Linux

This repository contains packages for GNU Octave and its dependencies that aren't in the community repos.


## Packages

`octave`: minimal Octave, no gui but plotting abilities.  
`octave-gui`: same as above but with the Qt gui as a requirement.

Note: the octave build system detects available dependencies and enables their according features, so you can cherry pick the dependencies
you want and go for `octave` if you want finer control. Here's [a list of optional dependencies](https://wiki.octave.org/Building) available.
What the different packages actually do is explicitly requiring the needed libraries in `depends`.

## Requirements

This repository requires the community repos and a fortran compiler.

### Enable gfortran in gcc

Go to your personal repo directory and fork gcc with `kiss fork gcc`, then go into the build file and set fortran as the enabled language in the `./configure` command. Then build and install that package.
