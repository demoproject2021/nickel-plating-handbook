---
layout: default
title: "14. Nickel Plating Troubleshooting Decision Tree"
---

# 14. Nickel Plating Troubleshooting Decision Tree

``` text
START: Nickel deposit is unacceptable
|
+-- Does the part pass a water-break test before activation?
|   |
|   +-- NO --> Re-clean. Do not adjust plating chemistry yet.
|   |
|   +-- YES
|
+-- Is adhesion poor or is the deposit peeling?
|   |
|   +-- YES --> Identify substrate
|              |
|              +-- Stainless/passive alloy --> Verify validated activation + nickel strike
|              +-- Steel/copper/brass --> Review oxide removal, transfer delay, cleaning
|
+-- Is the defect concentrated on edges/corners?
|   |
|   +-- YES --> Check calculated current density, anode distance,
|              agitation, temperature and pH for high-current burning
|
+-- Is the defect concentrated in recesses/low-current areas?
|   |
|   +-- YES --> Check contacts, anode coverage, shielding,
|              solution movement and contamination/Hull-cell behavior
|
+-- Is the surface rough or nodular?
|   |
|   +-- YES --> Inspect filtration, anode bags, tank/rack cleanliness,
|              airborne dirt and precipitated solids
|
+-- Is the surface pitted?
|   |
|   +-- YES --> Observe for gas bubbles; check cleaning, agitation,
|              filtration and supplier-approved wetting control
|
+-- Is the deposit hazy, dull or dark across most of the load?
|   |
|   +-- YES --> Verify temperature, pH, current density and rectifier output
|              |
|              +-- All correct --> Run Hull cell / contamination investigation
|
+-- Did the problem begin immediately after an addition or process change?
    |
    +-- YES --> Stop further additions. Review lot, identity, quantity,
               process log and cross-contamination risk.
```

## Troubleshooting order

Use this order to avoid wasting chemistry:

1.  Confirm substrate and preparation.
2.  Confirm electrical contact.
3.  Recalculate surface area/current density.
4.  Verify temperature and pH.
5.  Inspect anode placement.
6.  Observe agitation and gas release.
7.  Inspect filtration and particles.
8.  Review recent additions/process changes.
9.  Run comparative test panels/Hull cell.
10. Investigate contamination analytically if needed.
