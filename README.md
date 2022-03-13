# DM42 Programs

This is a my personal collection of programs for the [SwissMicros
DM42](https://www.swissmicros.com/product/dm42) pocket calculator which is
based on the excellent [Free42](https://github.com/thomasokken/free42)
simulator by Thomas Okken of the classic HP-42S calculator by Hewlett Packard.

Most of the programs are related to the requirements in atomic physics
experiments but there is also some electronics and further completely
unrelated stuff around.

Even though the programs should be mostly compatible with the original HP-42S
they do make use of some of the convenience functions offered by Free42 and
for graphical output the advanced capabilities of the DM42 platform are also
partially relied on.

## Short introduction to the individual programs

In the following we will quickly present each of the programs in the present
collection.

###B-F

This program calculates the energy difference (in MHz) between the two lowest
hyperfine Zeeman levels, often denoted |1> and |2>, of Lithium-6 given the
applied magnetic field (in Gauss) using the Breit-Wigner formula. It is
intended for use with the Solver application so it can also be used to convert
a frequency difference back into a magnetic field.

###BTOOL

This is a collection of currently three programs for often neede calculations
with Gaussian beams selected by a menu system. 'Imax' calculates the peak
intensity given the beam power and the waist size, and the Rayleigh length is
calculated by 'zR' given waist and wavelength. Finally 'Focus' is intended to
calculate the beam waist of a Gaussian beam that is focussed by a lens.
Parameters are the WAIST size and its position Z0 of the incident beam, its
wavelength LAMBDA and the focal length F of the lens.

###CAPA

This is a simple converter program for capacitor values. It converts between
the nominal capacitance and the code number often printed on small capacitor
packages.

###CMag

###CONST

###CPCTR

###DB

###DIPOLE

###E_b

###FORT_structure_overview

###FORT_with_subprograms

###FPLOT

###FRQCNV

###HLi6

###LATTICE

###NTH

###OHM

###PLOT

###PREFIX

###PROPAG

###P-WAVE

###R2T

###RESISTOR

###TQLI

###TRED2

###V60

## Contact

For any comments and/or bug reports please report to the author, schaefer@scphys.kyoto-u.ac.jp.
