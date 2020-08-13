# RESPONSE OF A LAYERED EARTH TO A PLANE WAVE, INSIGHT INTO THE MAGNETOTELLURIC METHOD
## Winner Plot

Thibaut Astic, PhD student in Geophysics at the University of British Columbia,
Geophysical Inversion Facility

<p align="center">
<img src="Movie_MT.gif" width="77%"/>
<p>

- The movie in context: https://em.geosci.xyz/content/maxwell3_fdem/natural_sources/MT_N_layered_Earth.html#

- The winner announcement page: https://scipy2016.scipy.org/ehome/146062/332971/index.html

- The video of the winner announcement: https://www.youtube.com/watch?v=vH-9FlaOl74

The magnetotelluric (MT) method is a widely used geophysical technique, in particular for
imaging geothermal systems, that is sensitive to Earth structures as shallow as tens of
meters to depths of hundreds of kilometers. The source energy is electromagnetic waves,
generated in the atmosphere by lightning strikes and interactions with solar wind and
Earth's magnetic field. These waves travel as plane waves through the atmosphere and
ground. The animation is built to visually explore the physics of wave propagation and
relate them to observed data. This enhances intuition and comprehension of the
equations and highlights the dynamic nature of the wave propagation, unlike the static
nature of data.

Electromagnetic waves are governed by Maxwell’s equations and hence are sensitive to
contrasts in physical properties that can be interpreted in terms of geologic structure and
fluid content. The diagnostic physical property for MT is electrical conductivity 𝜎 (or its
inverse resistivity 𝜌). The impact of contrasts in dielectric permittivity 𝜀 and magnetic
permittivity 𝜇 is expected to be negligible.

Any wave that hits the Earth gets refracted vertically because of the extreme contrast in
conductivity, regardless of the angle of incidence. It is thus sufficient to model a vertically
propagating plane wave. For our modelling we assume a 1D layered Earth.

The panels of the figure allow us to break down the physics into simpler pieces. The
lower-right panel illustrates the reflection and transmission of the wave at interfaces. At
the Earth’s surface, most of the downward propagating wave is reflected while the
transmitted part diffuses downward. The upper-right panel shows the total (sum of their
up and down going) electric and magnetic fields. The depth of investigation is regulated
by a damping effect on the transmitted wave’s amplitude due to the increase of conductivity.

Data in an MT survey are electric and magnetic fields measurements, which are the sum
the Earth's responses but also the unknown natural field sources. The unknown source
is overcome by using the ratio of the electric and magnetic fields, called the impedance.
Impedance is a complex number whose amplitude is used to estimate an apparent
resistivity while its phase provides information about changes in resistivity. Impedances
are measured at many frequencies, as the depth of investigation increases as the
frequency decreases. This is illustrated in the left panel displaying MT data. The
measured apparent resistivity is equal to the resistivity of the upper layer when sampling
at high frequencies, there is little contribution from the second layer. At intermediate
frequencies, we measure an averaged apparent resistivity as well as an increase in the
phase. At low frequencies, the apparent resistivity is converging to the lower layer
resistivity while the phase stabilizes to its normal value of 45 degrees.

This animated plot has been realized for http://em.geosci.xyz, an educational initiative at
the University of British Columbia aiming to provide interactive resources and case
histories for electromagnetic geophysics to promote its use for solving exploration,
geotechnical and environmental problems.
