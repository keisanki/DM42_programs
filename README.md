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

### B-F: Lithium level splitting from Breit-Wigner formula

This program calculates the energy difference (in MHz) between the two lowest
hyperfine Zeeman levels, often denoted |1> and |2>, of Lithium-6 given the
applied magnetic field (in Gauss) using the Breit-Wigner formula. It is
intended for use with the Solver application so it can also be used to convert
a frequency difference back into a magnetic field.

### BTOOL: Gaussian beam tools

This is a collection of currently three programs for often needed calculations
with Gaussian beams selected by a menu system. 'Imax' calculates the peak
intensity given the beam power and the waist size, and the Rayleigh length is
calculated by 'zR' given waist and wavelength. Finally 'Focus' is intended to
calculate the beam waist of a Gaussian beam that is focused by a lens.
Parameters are the WAIST size and its position Z0 of the incident beam, its
wavelength LAMBDA and the focal length F of the lens.

### CPCTR: Conversion between capacitor values and codes

This is a simple converter program for capacitor values. It converts between
the nominal capacitance and the code number often printed on small capacitor
packages. Either enter the capacity (in Farad, e.g. 1ᴇ-7) and push `→CODE` or
give the code (e.g. 104) and push `→VAL` for the conversion.

### CMag: Magnetic coil set value to field conversion

### CONST: Collection of physical constants

### DB: Various power conversions from and to dBm

### E_b: Estimate binding energy of two-species Feshbach molecules

### FORT: Calculate trap parameters of a crossed beam optical trap

### FPLOT: Advanced function plotter for the DM42 display

### FRQCNV: Convert laser frequencies to wavelengths to energies and more

### HLi6: Lithium level splitting by diagonalization of the Hamiltonian

### LATTICE: Calculation of lattice Raman-Nath interference patterns

### NTH: Central density of a thermal gas

### OHM: Convert between colors and numerical resistor values

### PLOT: Original HP42S function plotter for use with IR printer

### PREFIX: Beautify numerical outputs by proper use of prefix letters

### PROPAG: Propagate a Gaussian laser bean through an optics system

### P-WAVE: Calculation of the p-wave threshold energy

### R2T: Conversion between NTC resistance and actual temperature

### TQLI: Numerical recipes TQLI routine to diagonalize symmetric tridiagonal matrices

### TRED2: Numerical recipes TRED2 routine to reduce symmetric matrix to tridiagonal one

### V60: Helps you through your favorite V60 coffee brewing routine

## Contact

For any comments and/or bug reports please report to the author, schaefer@scphys.kyoto-u.ac.jp.
