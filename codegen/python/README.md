## Python algebras.

These algebras are generated by the ganja.js code generator and provide a clean, low threshold implementation
of a range of geometric algebras. Each file contains a class implementing the algebra (using flat storage),
overloaded operators for all common GA operators, and some simple numerical examples.

| sig   | filename        | name                         |
|-------|-----------------|------------------------------|
| 0,1   | c.py            | complex numbers              |
| 1,0   | hyperbolic.py   | hyperbolic numbers           |
| 0,0,1 | dual.py         | dual numbers                 |
| 2,0   | r2.py           | 2D Vectors                   |
| 3,0   | r3.py           | 3D Vectors                   |
| 1,1   | mink.py         | Minkowski                    | 
| 0,2   | quat.py         | Quaternion                   |
| 3,1   | spacetime.py    | Spacetime                    | 
| 4,1   | cga.py          | Conformal Geometric Algebra  |
| 3,0,1 | pga3d.py        | Projective Geometric Algebra |