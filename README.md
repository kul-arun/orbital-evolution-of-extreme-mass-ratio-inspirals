# Orbital Evolution of Extreme Mass Ratio Inspirals

In this project, we analyse the orbital evolution of Extreme Mass Ratio Inspirals (EMRIs) in stationary and axisymmetric spacetimes, according to Einstein's general theory of relativity. A spacetime with a [modified Johannsen metric](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.102.064041) is chosen to evolve the system. The following tasks are performed in this project:

* Evolve the orbits of the secondary around the primary using the geodesic approximation.
* Test the accuracy of the orbital evolution using a constraint equation.
* Visualise the orbits using 3D Cartesian coordinates.
* Model the associated gravitational waveform using the Einstein-quadrupole approximation.
* Investigate the Liouville integrability of the equations of motion using Poincaré surface of section and Rotation number curve.


## Theoretical Knowledge

The relevant physics and assumptions that went into the calculations are included in `theory.pdf`.

## Installation

* **Python**

Install Python 3.9 or higher. Create a virtual environment in the desired directory via:

```
python3 -m venv <virtual-environment-name>
```

Example: To create a virtual environment called `orbital-analysis`, use

```
python3 -m venv orbital-analysis
```

Activate the virtual environment with:
```
source <path-to-virtual-environment>/bin/activate
```

The virtual environment can be deactivated with:
```
deactivate
```

* **Jupyter Notebook**

Install Jupyter Notebook. It can be installed using `pip` through:
```
pip install notebook
```
To run the notebook:
```
jupyter notebook
```
* **Additional Requirements**

Install the necessary packages listed in `requirements.txt` via:
```
pip install -r requirements.txt
```
