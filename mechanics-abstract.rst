Dynamics with SymPy Mechanics

Moore, Jason, University of California at Davis

Jason K. Moore received his Ph.D. and M.S. degrees from the University of
California, Davis in Mechanical and Aeronautical Engineering and his B.S. at Old
Dominion University in Norfolk, VA. His dissertation was titled “Human Control
of a Bicycle” and his doctoral work spanned a collaborative project involving
the theory of bicycle dynamics, control, and handling with experimental
validation. His research interests include topics in man–machine interaction,
manual control theory, multibody systems, human biomechanics, human power,
system identification, open science, and computer programming for scientists.
During 2008-09 he was a visiting Fulbright scholar to the Netherlands where he
was a researcher at Delft University of Technology. Jason is also a strong
advocate for opening up our science to the world. He co-founded the UC Davis
Open Science Group where he has co-hosted many prominent leaders in the Open
Science movement for presentations, discussions, and workshops.

The SymPy Mechanics package was created to automate the derivation of the
equations of motion for rigid body dynamics problems. It has been developed
through several Google Summer of Code grants over three years and is capable of
deriving Newton's Second Law for non-trivial multi-body systems using a variety
of methods: from Newton-Euler, to Lagrange, to Kane. The software provides
essential classes based around the concepts of a three dimensional vector in a
reference frame which ease the setup and bookkeeping of the tedious kinematics
including both kinematic and motion constraints. There are also classes for the
automated formulation of the equations of motion based on the bodies and forces
in a system. It also includes automated linearization of the resulting
non-linear models. The software can be used to solve basic physics problems or
very complicated many-body and many-constraint systems all with symbolic
results. I will go over the basic software design, demonstrate its use through
the API along with several classic physics problems and some not-so-trivial
three dimensional multi-body problems.

SymPy Mechanics Documentation:
http://docs.sympy.org/dev/modules/physics/mechanics/index.html
Paper: https://github.com/gilbertgede/idetc-2013-paper
Python Dynamics: https://pydy.org/
Public Speaking Example: http://youtu.be/oKbaHCGK94E
