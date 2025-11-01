# 7-B-RADIATION-PATTERN-OF-HORN-PARABOLIC-ANTENNAS

**Aim:**
To measure the polar pattern and the gain of a waveguide horn antenna and parabolic antenna.

**THEORY:**

If a transmission line, propagating energy is left open at one end, there will be radiation from this end. In case of a rectangular waveguide this antenna presents a mismatch of about 2 and it radiates in many directions. The match will improve if the open waveguide is a horn shape.
The radiation pattern of an antenna is a plot of field strength of the power intensity asa function of the aspect angle at a constant distance from the radiating antenna .an antenna pattern is of course three dimensional but for practical reasons it is normally PRESNTED as a two dimensional pattern in one or several planes. An antenna pattern consists of several lobes, the main lobe, side lobes and the back lobe. The major lobe is concentrated in the main lobe and it is required to keep the power in the side lobes and back lobe as low as possible. The power intensity at the maximum in the main lobe compared to the power intensity achieved from an imaginary omnidirectional antenna (radiating equally in all directions) with the same power fed to the antenna is defined as gain of the antenna.

**3DB BEAM WIDTH**

This is the angle between the two points on a main lobe where the power intensity is half the maximum power intensity. The antenna pattern measurement is always done in far field region.
Far field pattern is achieved at a minimum distance of2D2 /λ0 (for rectangular horn “antenna”)
where d is size of the broad wall of horn aperture λ0 is the free space wave length.
It is also very important to avoid reflection, antenna measurement is done at outdoor ranges or in anechoic chambers made of absorbing materials.
Antenna measurements are mostly made with antenna as receiver. Therefore several methods are there to measure the gain of antenna one method is to compare the unknown antenna with standard gain antenna with known gain. Another method is to use two identical antennas. One as a transmitter and other as receiver and from following formula the gain can be calculated.
Pr = pt λ0 g1g2 / (4ΠS)2 where pt is transmitted power, pr is received power ,g1,g2 is gain of transmitting and receivingantenna ,s is the radial distance between two antenna. 
Λ0 is free space wavelength. If both transmitting and receiving antenna is identical having gain g then,PR = PT Λ0 G2 / (4ΠS)2 ,G= 4ΠS/ √ Λ 0 *	√Pr / P t
In the above equation pt ,pr ,s and can be measured and gain can be computed. As from the
above equation it is not necessary to know the absolute value of pt and pr. Only ratio is required .which can be measured by VSWR meter.


**PROCEDURE:**

**A.ANTENNA RADIATION PATTERN:**

1.	Set up the equipments as shown in the figure 1.keeping the axis of both antenna in same line.
2.	Energize the Gunn oscillator for maximum output at desired frequency with square wave modulation by tuning square wave amplitude and frequency of modulating signal of Gunn power supply and by tuning the detector.
3.	Also tune the s s tuner in the line for maximum output (if s s tunner is in the setup)
4.	Obtain full scale deflection (0DB) on normal dB scale (0-10DB) at any convenient range switch position of the VSWR meter by gain control knob of VSWR meter or by variable attenuator.
5.	Tune the receiving horn to the left in 20 or 50 steps upto 40 -50 and note the corresponding VSWR dB reading in normal dB range. When necessary, change the range switch to next higher range and add 10DB to the observed value.
6.	Repeat the above step but this time turn the receiving horn to the right and note down the readings.
7.	Plot a relative power pattern i.e. Output vs angle.
8.	Prom diagram determine 3DB width (beam width) of the horn antenna.

**GAIN MEASUREMENT:**

1.	Set up the equipments as shown in figure both horns should be in line.
2.	Keep the range dB switch meter at 50DB position with gain control full.
3.	energize the Gunn oscillator for maximum output at desired frequency with modulating amplitude and frequency of Gunn power supply and by tuning of detector.
4.	obtain full scale deflection in VSWR meter with variable attenuator.
5.	replace the transmitting horn by detector mount and change the appropriate range dB positon to get the deflection.on scale(do not touch the gain control knob).note and record the range dB position and deflection of VSWR meter.
6.	calculate the difference in dB between the power measured in step 4 and 5.

**EXAMPLE**

Suppose that a deflection of 5DB on 20DB range dB position was obtained in step 5,the difference between 4 and 5 is
50-(20-5)=25DB 
Convert the dB in to power ratio.as for above example is will come 316 which will be pt/pr .Calculate gain by following equation:
G= 4ΠS/	√ Λ 0 *	√Pr / Pt
In our above example suppose operating frequency is 9GHZ λ0=3.33CM.where c is velocityof light and is 3*1010CM/sec and distance between antennas is 150CM(suppose).

7.	convert g into dB in above exampleG dB =10LOG318=15.02DB
8.	the same setup can be used for other frequency of operation.

**BLOCK DIAGRAM:**

<img width="638" height="177" alt="image" src="https://github.com/user-attachments/assets/0e3f554a-c54b-42a4-bc48-1c3b3dd5f5fc" />

**TABULATION:** 

**HORN ANTENNA** 

Beam voltage	:

Beam current	 :

**PARABOLICANTENNA**

Beam voltage	:

Beam current	 :

Repeller voltage :

	V1 : 

**RESULT:**

Thus the polar pattern and the gain of a waveguide horn antenna and parabolicantenna was measured and plotted.

Beamwidth of horn antenna :

Beamwidth of parabolic antenna:		



