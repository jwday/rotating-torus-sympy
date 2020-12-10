# Dynamic Modeling of a Rotating Torus in Free Space using Sympy
This project was a quarter-long final project in UC Davis's MAE 233 'Multi-body Dynamics' graduate course, where we were introduced to Kane's Method of dynmic modeling and SymPy (Symbolic Python) to apply this method to an exercise of our choosing. My interest in long-duration space travel led me to explore the dynamics of a theoretical space station design which utilizes rotation as a means of simulating gravity through centrifugal force, i.e. Space Station V from Stanley Kubrick's "2001: A Space Odyssey".

![2001 Station](https://i.stack.imgur.com/43Kvi.gif)

The .ipynb included in this repo contains all of the necessary formulation to generate the equations of motion and integrate them through time to observe the resultant motion. The system is modeled as a single rotating torus with four point-masses equidistant along the circumference. Two opposing point-masses are fixed, referred to as "ballast masses", while the other two are prescribed to move toward one end of the torus. During that transition, we can observe the resultant change in motion of the torus as the center of mass shifts away from the geometric center.

![Rotating torus](https://github.com/jwday/rotating-torus-sympy/blob/main/torus.gif =250x)

Future work would involve placing constraint equations on the ballast masses to observe their response to the change in motion. The impetus for this work is to develop a theoretical means for *passively* stabilizing (read: keeping the rotation axis coincident with the geometric center and perpendicular to the geometric plane of the torus) the system amid internal disturbances.
