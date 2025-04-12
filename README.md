FORTRAN code for calculating synthetic seismograms based on a layered viscoelastic half-space earth model.

Highlights:

(1) orthonormal propagator algorithm for numerical stability (more efficient than the reflectivity method)

(2) complex frequency technique for supressing the time-domain aliasing problem

(3) wave-number-domain differential filter technique for suppressing numerical phases

(4) various partial solution options

(5) different shallow structures at source and receiver site

(6) earth flattening transformation

Related codes

MSEIS – for marine seismic application

QSEIS2D - for quasi 2D structure model (only teleseismic applications)

For Windows user, the executable file is provided under folder "WindowsEXE". Linux user may compile the source codes with "gfortran" via a single command like, e.g.,

~>cd .../SourceCode

~>gfortran -o qseis2006 *.f -O3

to get the excutable code qseis2006.

After start the executable code, the program ask for an input file in the ASCII format. An example input file is provided under folder "InputFile". You may change the input data included in this file for your own applications.

References

Wang, R., (1999), A simple orthonormalization method for stable and efficient computation of Green's functions, Bulletin of the Seismological Society of America, 89(3), 733-741.

Wang, R., and H. Wang (2007), A fast converging and anti-aliasing algorithm for Green’s functions in terms of spherical or cylindrical harmonics, Geophysical Journal International, doi: 10.1111/j.1365-246X.2007.03385.x.
