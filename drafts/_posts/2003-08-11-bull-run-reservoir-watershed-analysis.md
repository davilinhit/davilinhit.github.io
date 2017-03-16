--- 
layout: landscape
title: Bull Run Watershed Analysis
subcat: geology
image: /img/thumbs/bullrun.png
description: Bull Run Reservoir watershed. Uses MathJax.
mathjax: true
num: 1
status: Complete
---

Bull Run Watershed is the primary source of drinking water for the city of Portland, Oregon. Bull Run Lake contains the headwaters for the Bull Run mainstem, which collects tributary inflow from approximately 277 sq. km. on its way to two city-operated reservoirs, #1 and #2. 

Rain provides 90-95% of the water in the watershed (Portland Water Bureau, 2010) so an understanding of both rivers and groundwater in this system is critical for managing the flow to the city's customers; this lab investigated how to map tributaries, measure annual precipitation, and identify surface permeability of fine sand and gravel to predict how much water can be expected in the system at any time of year and by what path it will arrive in the reservoirs. 

The flow rates are important because all water flows carry sediment which can have a negative long-term affect on the reservoirs. The annual sediment rate for the Bull Run Watershed is 20 tons per sq. km. per year.

<div style="width: 400px; margin: 0 auto;"> <img src="https://jenner.smugmug.com/Geology-Labs/i-g8pCPxp/0/O/bullrun.png"><br />
<small>Fig. 1. Aerial view of Bull Run Watershed. Dense forest surround the lakes. Activities like recreational use and logging are restricted as part of the management plan. Picture taken by Jenner Hanni, September 2010.</small>
</div>

<strong>Methods</strong>

Tributaries can be separated into sections called reaches. Each reach will be assigned a number order, starting with a '1' for reaches with no tributaries. When two first-order streams meet, the next reach will be a second-order because the orders are summed downstream; if that second-order reach is joined by another second-order reach, the subsequent reach will be fourth-order. (Shreve, 1966) 

Drainage frequency is the ratio of first-order reaches to total ordered reaches in the drainage basin as a percentage. Stream density, \(D\), is the number of streams per kilometer and can be calculated by dividing the sum total length in km. of all reaches by the drainage area in sq. km. The overall discharge, \(Q\), of a watershed can be found utilizing 

$$Q = \frac{I_p A}{t}$$

where \(I_p\) is the input from precipitation, \(A\) is the total watershed area, and \(t\) is time. The significant variation of daily rainfall and the staggered effects from the different paths taken by precipitation are mitigated by utilizing the mean precipitation rate for the month when predicting discharge. This mean rate was calculated utilizing the 2003 data for the South Bull Run Fork site (Snotel, 2003) and plotting the standard curve for cumulative and daily rainfall. 

Groundwater, when precipitation penetrates the surface and travels downslope, is a significant resource for reservoir recharge. Permeability describes how easily water can move between grains in porous material. It is possible to determine the permeability constant, \(k\), for any given material by utilizing Darcy's equation 

$$k = \frac{q}{Ai}$$

where \(q\) is the discharge in volume/second and \(A\) is the cross-sectional area of the sample; the hydraulic gradient, \(i\), is dimensionless and can be calculated utilizing

$$i = \frac{\Delta h}{\Delta L}$$

where \(\Delta h\) is the total height of the water column and \(\Delta L\) is only the height of the material.

Permeability increases with increasing grain size because small grains are more likely to fill in all open spaces; for example, gravel will have a higher permeability coefficient than fine sand because there is more room between gravel grains for the water to flow. The experiment conducted used a Ward's Constant Head Permeability meter. 

A vertical cylinder with the lower end wrapped in cheesecloth was filled with the material to test. A length of rubber tubing was used to run water into the top of the cylinder at a constant rate. Three trials were conducted where the water that permeated the material was collected and measured over a pre-determined period of time to find the water's velocity. 

<strong>Results</strong>

The drainage relief from the highest point (1448 MSL) to the lowest point (300 MSL, at the Headworks) was found to be 3.86 degrees, which is relatively flat and likely contributed to the dendritic flow pattern seen in Figure 1; the thirty-three first-order reaches highlighted in red represent 55% of the sixty-one total reaches in the watershed. The watershed is 25km at its longest and 15km at its widest, yielding a total length/width ratio of 1.67 and a total stream density of 0.5 streams per km. 

<div style="width:510px; margin: 0 auto;"> <img src="https://jenner.smugmug.com/Geology-Labs/i-ZTgQD57/0/O/firstorderstreams.png"><br /><small>Fig. 2. Steam ordering of the Bull Run drainage basin utilizing the Shreve method (Shreve, 1967) with first-order streams in red; the order of other reaches are noted by number. Flow direction is from east to west and the highest order in the basin is reached by the Bull Run mainstem in the west half of Reservoir #2. Red are modifications on top of base image from lab packet.</small> </div>

<br /><br />

Figure 3 presents the cumulative total precipitation for all days in 2003 and Figure 4 presents the actual daily centimeters of rain. The two graphs are complimentary; the steepest slopes on the total precipitation curve represent periods when daily rainfall added rapidly to the total; the shallower slope in summer correlates to the many days on which no precipitation was recorded. 

<div style="width:472px; margin: 0 auto;"> <img src="https://jenner.smugmug.com/Geology-Labs/i-vV4B9ws/0/O/dailyprecip.png"><br /><small>Fig. 3. Cumulative precipitation shown over 365 days from 2003 data for South Bull Run Fork. Steepness of slope indicates periods of time with near-daily rainfall, thereby increasing total precipitation year-to-date. The flat section in the center of the graph describes the dry summer months of June, July, and August. Short dry periods in the first part of February and October are seasonally consistent with the region. Data obtained from Snotel.</small>
</div>

<br /><br />

<div style="width:566px; margin: 0 auto;"> <img src="https://jenner.smugmug.com/Geology-Labs/i-dzqcBP3/0/O/totalprecip.png"><br /><small>Fig. 4. Daily precipitation. The highest values occur in January and February and the lowest occur in the summer months of June, July, and August. The magnitude of these values are proportional to slope magnitude in Figure 2. Data obtained from Snotel.</small>
</div>

<br /><br />

As noted, the summer months of June, July, and August experienced the least total rainfall; precipitation was measured only on six days in the month of June for a monthly total of 5.2 cm. This value was averaged over thirty days for a mean daily precipitation rate, IP, of 0.17 cm. An average June day would see the 277 sq. km. of the Bull Run Watershed discharge 4.7 million cubic meters of water, according to the following sample calculation utilizing Equation 1.

$$I_p = 0.17 cm = 1.7x10-2 m$$
$$A = 277 x106 m^2$$
$$t = 1 day$$

$$Q = \frac{I_p A}{t} = \frac{(1.7x10^-2)(277x10^6 m^2)}{1 day} = 4.71x10^6 m^3/day$$

More water is likely to enter the groundwater when the materials over which it flows are more permeable. The discharge rates and hydraulic gradients were found for fine sand and gravel. The discharge through gravel was about nine times higher, or almost one order of magnitude, as seen in Table 1. The permeability coefficients displayed this same order of magnitude difference when calculated utilizing Equation 2.

$$Q = 0.56 cm^3/s$$
$$i = \frac{\Delta h}{\Delta L} = \frac{24 cm}{12.5 cm} = 1.92$$
$$A = \pi r^2 = \pi (1.75 cm^2) = 9.62 cm^2$$

$$k = \frac{Q}{iA} = \frac{0.56 cm^3/s}{(1.92)(9.62 cm^2)} = 0.03$$

<strong>Discussion</strong>

More than half the reaches are first-order and thus more shallow, narrow, turbulent, and easily affected by forestry activities which lead to denuded slopes and erosion. For example, logging could result in increased sediment turbidity in the reservoirs, affecting delivery of water to the city's customers. For this reason, logging in the watershed is carefully managed. 

Additionally, there is always lag between rainfall and its affect in the system. Some of the water runs down slope directly into the streams but, depending on the permeability of the surface material, much of that precipitation may seep into groundwater and take longer to reach the reservoirs. The daily precipitation values in Figure 4 could be compared to a standard curve showing daily discharge rates to determine the amount of lag and where it occurs. 

<strong>Conclusion</strong>

The watershed needs to be carefully managed because it supports a sizable population and there are significant dry periods in the summer of up to ten days at a time when the system is not recharged by precipitation. Gravel is clearly the superior material for allowing the flow of groundwater because its permeability coefficient was nearly an order of magnitude higher than that of fine sand, so water moves more quickly and in greater total amounts. Groundwater recharge of the reservoirs is a vital part of the watershed system.
