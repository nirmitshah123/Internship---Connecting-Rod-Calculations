# Connecting Rod Force Analysis

MATLAB script that computes the dynamic loading on a heavy-duty diesel engine
connecting rod across the full crank cycle. Resolves gas pressure and reciprocating
inertia forces at each crank angle to identify the peak compression and peak tension
load cases, which feed the boundary conditions for structural FEA and topology
optimization of the rod.

## Inputs

- Bore, stroke, connecting rod length
- Piston and connecting rod mass
- Engine speed
- Peak cylinder pressure

## Outputs

- Force vs. crank angle across the cycle
- Peak compression and peak tension load cases

## Status

Work in progress. Some input parameters are placeholders pending verification and
are marked as such in the code.
