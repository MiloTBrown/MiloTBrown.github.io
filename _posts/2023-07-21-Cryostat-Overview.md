---
date: 2023-07-21 17:00:00
layout: post
title: Quantum Optics Cryostat at Leiden University
subtitle: The coolest article ever!
description: A description of the cooling apparatus I encountered during my research at Leiden University
image: https://res.cloudinary.com/drdsw7wbb/image/upload/v1701898587/Cryostat_Leiden_dn9pcv.jpg
category: research
tags:
  - research
  - quantum optics
  - cryostat
  - physics
  - superfluid helium
author: milo_brown
---
In the summer of 2023, I had the incredible opportunity to travel to the University of Leiden and research quantum optics in Professor Dirk Bouwmeester's Lab. While in the Netherlands, my research direction pivoted from characterizing optical membranes to aligning optical imaging to image superfluid helium vortices. One of the most interesting pieces of equipment in the lab is the cryostat itself. In the following article, I will describe some of the most interesting elements of the cryostat I encountered in Leiden.

## Introduction
In quantum optics research, isolating an optical cavity from its environment via cooling is essential when working with single photons. The Boumeester Quantum Optics group at the university of Leiden uses a cryostat (a device that cools samples to near absolute zero) to maintain this isolation. An image of the cryostat without shielding to protect from radiative heat transfer is shown in the image above. The cryostat uses superfluid helium and demagnetization cooling to cool to below 1 milliKelvin. In the following article, I will discuss in more detail how the cryostat cools and isolates the optical devices.

## Superfluid Helium
The cryostat cools gaseous Helium to liquid Helium by compressing Helium gas and then ejecting it through a small nozzle repeatedly, cooling by adiabatic expansion. An adiabatic process cools the gas by transferring (thermal) energy as external work, causing no heat transfer between the gas and its surroundings. As the gas expands, it does work on its environment, decreasing the internal energy of the gas. 

Helium will cool to superfluid Helium past the lambda point. The lambda transition occurs at 2.17 K, but Helium cools to liquid Helium at around 4 Kelvin. The cryostat can cool the Helium further by introducing Helium 3 to the liquid Helium 4. Helium 3 is an isotope of Helium with two protons and only one neutron. A fermion has a spin multiple of ½ and a boson has an integer spin. Since neutrons (along with protons and electrons, of which Helium has an even number) have a spin of ½, Helium 3 (with one neutron) is a fermion, and Helium 4 (with 2 neutrons) is a boson. Fermions and bosons behave differently – for instance, fermions obey the Pauli exclusion principle, which means that two identical fermions cannot occupy the same space. In other words, two fermions with the exact same quantum numbers cannot exist. Bosons do not follow the same restriction and can therefore bunch together. By introducing the fermionic Helium 3 isotope to the liquid Helium 4, the liquid helium can continue to cool through further adiabatic expansion.

## Adiabatic Nuclear Demagnetization Cooling
The next stage in the cooling process brings the temperature from 20 milliKelvin to less than 1 milliKelvin. Before the cryostat cools, a strong magnet aligns the spin states of a special metal. After the cryostat begins to cool, the magnet is turned off, and the magnetic spin states return to random directions. This increases the possible combinations of magnetic spin states, which increases the entropy in the metal. Since the product of entropy and temperature should remain constant, the increase in entropy causes a decrease in temperature.

## Mechanical Low Pass Filter
A low pass filter in electronics allows signals with a frequency lower than a specifically designed cutoff frequency to pass through, while higher frequencies are filtered out. A low pass filter includes a resistor (voltage/current), a capacitor (charge/voltage), and sometimes an inductor (magnetic flux/current). Since charge, voltage, and current are related through derivatives, this forms a second order differential equation that can be mimicked by the same form of differential equation in damped mechanical oscillation. Therefore, we can build a mechanical low pass filter using masses and springs. The mechanical low pass filter in the cryostat at the university of Leiden is calibrated to exclude the specifically measured frequency of vibrational noise in the lab. 

## Unique Thermal Isolation Material
Lancaster University revealed in a press release and video that LEGO toy bricks can act as an extremely effective thermal insulator. The cryostat at Leiden University uses lego pieces as a thermal insulator between the liquid helium and the demagnetization-cooling element near the bottom of the cryostat. Note here that there has been some discussion of switching to sapphire.


