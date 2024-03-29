---
layout: post
title: "Lorenz System"
date: 2024-01-20
description: "Animation of a chaotic solution of the Lorenz System"
github_url: https://github.com/matejfric/lorenz-system/
img_url: /assets/img/lorenz-system/lorenz63.gif
tags: [Chaos Theory]
---

<!-- /assets/img/lorenz-system/lorenz63.png -->

The [Lorenz system](https://en.wikipedia.org/wiki/Lorenz_system) is a system of ODEs:

$$
\begin{align*}
\frac{\mathrm{d}x}{\mathrm{d}t} &= \sigma (y - x), \\
\frac{\mathrm{d}y}{\mathrm{d}t} &= x (\rho - z) - y, \\
\frac{\mathrm{d}z}{\mathrm{d}t} &= x y - \beta z.
\end{align*}
$$

Below is an example of the Lorenz attractor, a chaotic solution of the Lorenz system for parameters \\( \sigma=10, \rho=42, \beta=8/3 \\), and initial conditions \\( x_0=[0,10,20], y_0=1, z_0=20 \\).

<img src="/assets/img/lorenz-system/lorenz63.gif" alt="lorenz63.gif" class="center_img" >
