# ChemE 375: HW1

The assignment is due midnight **before** the beginning of the next class period.

Note: Use Excel for all problems.  Remember that on all Excel assignments, **some points will be given for following the recommended practice of naming variables and for presentation (formatting)**.  For each problem please use a separate worksheet and highlight your answers!

## Problem 1 (20 points)

In the first worksheet in the workbook complete the following.  The rate of heat transfer (q) from a heated flat plate with a cool fluid stream flowing across it can be found by:

<img src="https://latex.codecogs.com/gif.latex?q&space;=&space;h&space;\Delta&space;T" title="q = h \Delta T" class="center" />

where h is the heat transfer coefficient and $\Delta T$ is the change in temperature between the cool fluid and the plate.  The heat transfer coefficient is related to Nu, the dimensionless Nusselt number, through

<img src="https://latex.codecogs.com/gif.latex?Nu&space;=&space;\frac{hL}{k}&space;=&space;0.332&space;\sqrt[3]{Pr}\sqrt{Re}" title="Nu = \frac{hL}{k} = 0.332 \sqrt[3]{Pr}\sqrt{Re}" class="center" />

where L is the plate length, k is the fluid’s thermal conductivity, Pr is the dimensionless Prandtl number and Re the dimensionless Reynolds number.

The last two quantities are calculated according to

<img src="https://latex.codecogs.com/gif.latex?Re&space;=&space;\frac{\rho&space;L}{\mu}" title="Re = \frac{\rho L}{\mu}" />

and

<img src="https://latex.codecogs.com/gif.latex?Pr&space;=&space;\frac{\mu&space;c_P}{k}" title="Pr = \frac{\mu c_P}{k}" />

where μ is the fluid viscosity, cp is the fluid heat capacity, v is the fluid velocity and ρ is the density of the fluid.

*What is the heat transfer rate, in W/m2*, from a flat plate 2 meter long and temperature 343 K, if a stream of water passes over it at a velocity of 1.45 meters per second? The temperature of the water is 294 K, the. Water properties are: μ = 9.79x10-4 Pas, ρ = 998 kg/m3, k = 0.601 Wm-1K-1, and cp = 4.18x103 Jkg-1K-1.

*Hint: Begin by giving all the known quantities names, then calculate Nu.  h can be obtained once Nu is known.*

**After you have solved the problem, answer the following in the spreadsheet (for points).**
* Very Briefly list which skills, learned in class, were used to solve the problem.
* Are these skills useful to only the particular type of problem given here or are they broadly applicable? Very Briefly defend your position. This isn’t meant to take more than 5 min.


## Problem 2 (20 points)

In the second worksheet in the workbook complete the following.  Your team is tasked with designing the operational protocol for a batch reactor (basically a tank) for a particular reaction that must be carried out in the absence of oxygen to reduce the formation of byproducts.  You have an idea to first fill the tank with nitrogen and then add the liquid mixture.  As the liquid mixture is added, part of the nitrogen gas will be removed to prevent pressure buildup.

To flush the oxygen out, the tank will initially be filled so that the nitrogen is at 298.15 K and 1.25 atm.  To keep oxygen out, you want to make sure that the pressure inside the tank remains greater than 1.0 atm after the liquid is added; however, the pressure should not become greater than 2.5 atm in order to keep the cost of the tank to a minimum.  The tank has a capacity of 4000 L, and depending upon the amount of product needed, the volume of liquid in the tank can range from 3000 to 3500 L.  **In all cases, twenty-five percent of the nitrogen initially placed in the container remains after the tank is filled with the liquid.**  Given these constraints determine for your boss the range of possible operating conditions (temperatures, volumes, and pressures) so that appropriate heat transfer and control equipment can be designed.

Hints:
* You may assume nitrogen and the liquid mixture are at the same temperature & pressure.
* You may assume that nitrogen is an ideal gas described by the equation PV=nRT.
* One of the first things you need to do is calculate the amount of nitrogen that is placed into the empty tank.  I would also suggest setting up the spreadsheet with a column of possible temperatures and a row of possible volumes.
* You may assume that changes in the volume of liquid due to changes in temperature and pressure is negligible and the volatility of the liquid is low such that nitrogen is essentially the only component of the gas phase.
* Remember that the number of moles, temperature, pressure, and volume of the gas are related.  You can only set three of the four independently.
* The hardest part of this problem is figuring out what is needed.  Remember, you are the engineer trying to present some data to your boss that can be used for future design.  The Excel portion of this problem is fairly easy (especially if you make careful use of dollar signs ($) in your equations).

**After you have solved the problem, answer the following in the spreadsheet (for points).**
* Very Briefly list which skills, learned in class, were used to solve the problem.

## Problem 3 (20 points)

Visit [finance.yahoo.com](finance.yahoo.com) and select a stock by searching for a company name (e.g. Google). Place that data in an Excel Worksheet. Repeat this process for a different company stock so that there are two Worksheets, each with the appropriate stock ticker symbol.

Generate a plot that includes the two stock “Close” data and daily “High” and “Low” values. Normalize the data by the maximum “Close” price over the past month so that all values are divided by the maximum value for that particular stock. Calculate the MAX, MIN, STDEV, AVERAGE, and the MEDIAN for each stock “Close” data. Format the plots with appropriate font size for readability, eliminate shadow effects, make the plot readable in black and white, and remove the outside border. Describe how you would export the figure for a presentation or document. The final plot should be both readable and aesthetically pleasing.


## Problem 4 (20 points)

[Download the data](https://github.com/uw-cheme375/uw-cheme375.github.io/raw/master/homeworks/tclab.txt) from an Arduino temperature control device and import the data into an Excel workbook.

Generate a plot that shows the measured temperature values on one plot and the heater values on another plot. Add appropriate labels to the plots such as x-label, y-label, title, and legend. Make sure that the plot is readable even when printed in black and white or for someone who may be color-blind. Horizontally align the time of two plots so that the heater effect on the temperature is observable.

## Problem 5 (20 points)

For each of the following problems, on a worksheet entitled *Functions*, allow input of the independent variable, x, in one column. In a second column, show the function in text. In a third, show the value of the function.

| Input value (x) | Output function f(x)                       |
| --------------- | ------------------------------------------ |
| 0.5 rad         | cos(x)                                     |
| 30 degrees      | sin(x)                                     |
| 2               | tan(π/x) π/x in rad                        |
| 5               | max of 2/√x, x^2/2, x^3/3, (x^2+x^3)/5     |
| 25              | x!                                         |
| 0.5             | x^2 when x<1; sin(πx/2) when x≥1           |
| 4.999           | largest integer less than or equal to x    |
