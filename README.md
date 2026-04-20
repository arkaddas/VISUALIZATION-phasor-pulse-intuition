# VISUALIZATION-group-velocity-intuition

A small MATLAB repo for building intuition about **phasor realignment**, **beating**, and **pulse** / **envelope formation** from multiple oscillatory components.

This can also help understand how the slipping of the phasors result in the pulse and thus how group velocity can be related to the slipping of phasors.

This project visualizes how individual complex phasors evolve and how their vector sum grows and shrinks as they drift in and out of alignment.

<img width="900/6" height="450/6" alt="image" src="https://github.com/arkaddas/VISUALIZATION-group-velocity-intuition/blob/main/phasor_slip_pulse.gif?raw=true)"/>


## What this shows

For components of the form

```LaTeX
e^{j(kx - \omega t)}
```


the repo shows:

- individual phasors in the complex plane
- the normalized vector sum of those phasors
- the time evolution of the resultant magnitude
- how a moving observation frame changes what you see
- how the aligned peaks make the pulse
- the velocity of the pulse is group velocity

This is useful for understanding ideas related to:

- beating
- coherence
- envelope formation
- group velocity
- superposition of oscillatory components
- intuition behind analytic-signal style representations

## Files

- `matlab/demo_phasor_slip_pulse_group_velocity.m`  
  Main interactive visualization.

## Quick start

Open MATLAB, navigate to the `matlab/` folder, and run:

```matlab
demo_phasor_slip_pulse_group_velocity
