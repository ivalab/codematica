# codematica

Robotics Mathamatica code associated to the different things we've studied.



## Description

Depending on how it was developed, the code may have two parts.  One is
an intro notebook that contains the baby steps we performed to get the
full version working with confidence.  Then there is the actual notebook
with the actual working version.

Name | Provides
-----| --------
hopper  | Raibert's hopper and variations.
dcrawler | Discrete crawler (or what I call the Franken-crawler).
hexapod | Simple hexapod model (tripod gait).
 | 
hilare | Hilare robot (e.g., wheelchair robot model).
kincar | Kinematic car.
nonhol3kin | Simple standard form 3-state (kinematically) nonholonomic system.
nonhol5kin | 5-state (kinematically) nonholonomic system. Requires second order averaging.
 | 
nonhol3dyn | Simple standard form 3-state (dynamic) nonholonomic system.  Lifted form of kinematic version.
snakeboard | The snakeboard.


Some of the above have known equations of motion, so there should be no
surprises.  However, if memory serves, I may have worked out some of
the equations of motion using
[BKMM](http://www.cds.caltech.edu/~marsden/bib/1996.html) (Title:
*Nonholonomic Mechanical Systems with Symmetry*) and used the
controllers from the
[Thesis](http://ivalab.ece.gatech.edu/Publi/Vela_thesis%5B2003%5D.html).  
Accordingly, there should be controllers for some of them designed to
manage the nonholonomic aspects.  Sometimes, though, it was easier to
get it done in Matlab than Mathematica.  Some of the differential
equations were not solveable in Mathematica due to self-referencing of
past control efforts (the continuous averaging-based controllers).

**NOTE** Currently only the hopper is included.  All of the code was
writen 10 years ago, so I need to update it to Mathematica's current
functionality.  What was once in specialized packages now seems to be
default, plus certain plotting options havebeen superceded by others.

