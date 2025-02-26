SubSurface Normalization and De-Normalization

Normalization

Normalization is a process used to remove the effects of irreducible water saturation and trapped saturations from relative permeability data. The main purpose is to create a standardized representation of relative permeability curves that can be compared across different rock samples or reservoir conditions.

The normalized saturation for a given phase (oil, gas, or water) is calculated using:
S_{i,normalized} = (S_i - S_{ir}) / (1 - S_{wr} - S_{or} - S_{gr})

Where:

S_i is the phase saturation at any given point
S_{ir} is the residual (immobile) saturation for each phase
S_{wr}, S_{or}, and S_{gr} are irreducible water, residual oil, and residual gas saturations, respectively.

De-Normalization
De-normalization is the reverse process, converting normalized relative permeability data back to its original form, considering specific irreducible and residual saturations of a particular reservoir region.

The de-normalized relative permeability can be calculated using:
k_{ro,denormalized} = k_{ro,normalized} × k_{ro,@Swc}
k_{rw,denormalized} = k_{rw,normalized} × k_{rw,@Sor}

Where:
k_{ro,denormalized} and k_{rw,denormalized} are the de-normalized relative permeabilities for oil and water
k_{ro,normalized} and k_{rw,normalized} are the normalized relative permeabilities
k_{ro,@Swc} is the relative permeability of oil at connate water saturation
k_{rw,@Sor} is the relative permeability of water at residual oil saturation

Applications in Petroleum Industry
Reservoir Characterization: Comparing relative permeability data from different parts of a reservoir.
Upscaling: Improving accuracy of reservoir simulations by upscaling core-scale measurements to field-scale models.
Prediction of Relative Permeability: Predicting relative permeability curves for new rock/fluid conditions.
Reservoir Simulation: Providing essential inputs for reservoir simulation models.
Enhanced Oil Recovery (EOR) Planning: Aiding in the design and optimization of EOR processes.
