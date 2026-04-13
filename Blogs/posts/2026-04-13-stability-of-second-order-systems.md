---
layout: post
title: "Stability of Second Order Systems"
date: 2026-04-13
categories: [control-systems, drake]
---

Second order systems appear everywhere in control engineering.

A standard form is:

$$
\ddot{x} + 2 \zeta \omega_n \dot{x} + \omega_n^2 x = 0
$$

where:
- $\\omega_n$ is the natural frequency
- $\\zeta$ is the damping ratio

The behavior depends strongly on the value of $\\zeta$:

- **Underdamped**: oscillatory response
- **Critically damped**: fastest response without oscillation
- **Overdamped**: slower response without oscillation
- **Unstable**: response grows instead of settling

In a future post, I’ll show how to simulate and visualize these cases using Drake.