# Chassis Engineering

## Overview
Tubular spaceframe designed for the solar vehicle context — structural integrity without unnecessary mass.
Final chassis: **32 kg**, torsional rigidity: **1800 Nm/deg**.

## Material — Why AISI 4130 Chromoly?

Most student teams default to AISI 1018 mild steel or Al 6061-T6. We chose 4130 Chromoly for three reasons:

| Property | 4130 Chromoly | Mild Steel (1020) |
|---|---|---|
| Yield Strength | ~435 MPa | ~207 MPa |
| Fatigue Resistance | High (Cr-Mo alloying) | Moderate |
| TIG Weldability | Excellent | Good |

Same safety factor, thinner walls, less mass — that's the whole game on a solar car.

## Design & Validation
- Modelled in **SolidWorks Weldments** with real section profiles per member
- FEA run for worst-case brake, cornering, and bump load scenarios
- Torsional rigidity test: rear suspension plane fully constrained, torque applied at front, 
  angular deflection measured → **1800 Nm/deg**
- Mass tracked per member throughout; members with poor stiffness-to-mass ratio were removed 
  or rerouted to more efficient load paths

## Fabrication
Fabricated at **Mecrox Tech Pvt. Ltd., Gurugram** with on-site oversight.  
Tube notching (profiling tube ends for tight mating joints) done manually.
