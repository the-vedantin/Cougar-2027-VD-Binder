# Cougar Racing — 2027 Vehicle Dynamics Binder

Interactive design binder for the 2027 car's suspension and vehicle dynamics.
Everything in it — geometry, kinematic curves, dynamics, loads, the 3D model —
is generated from the single solved Vahan model, config **v27**
(pushrod outboard pivots mounted on the control arms and clear of the wheel and
driveshaft, with motion ratios, ARB rates and roll centres preserved; 60.92 s on
the RoseLap 2018 map).

**View it: https://the-vedantin.github.io/Cougar-2027-VD-Binder/**

Or download `index.html` and open it locally — fully self-contained, works
offline. Use the left sidebar to rotate/zoom the car model, search, and jump
between chapters; "Every Number" is the master lookup table.

## Tire data acknowledgment

Tire-derived figures in this binder are generated from **FSAE Tire Test
Consortium (TTC)** data, measured at the **Calspan Tire Research Facility
(TIRF)**. Per the FSAE TTC Participant Agreement, the published figures are
**de-identified** — the tire make/model is withheld. Please do not attempt to
re-identify the tire or repost the tire-derived figures separately from this
acknowledgment.

Built with [Vahan](https://github.com/the-vedantin/SUSDYN), the team's
suspension kinematics + vehicle dynamics tool.
