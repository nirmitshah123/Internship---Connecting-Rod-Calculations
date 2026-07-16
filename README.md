Computes the dynamic loading on a heavy-duty diesel engine connecting rod across the full crank cycle. Takes engine geometry (bore, stroke, rod length) and peak cylinder pressure as inputs, then resolves gas pressure and reciprocating inertia forces at each crank angle to find the peak compression and peak tension cases. Output feeds the boundary conditions for structural FEA and topology optimization of the rod.
Inputs: bore, stroke, connecting rod length, piston and rod mass, engine speed, peak cylinder pressure
Outputs: force vs. crank angle, peak compression / peak tension load cases
