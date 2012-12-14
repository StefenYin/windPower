Wind Power:
==========

**Here are three modules written in Ipython-Notebook**:

costreturn
----------
Calulate the Cost of Energy, Initial Capital Cost, Return on Investment, and 
Payback period, etc, when we know the Annual Energy Production of a wind farm.
Inside, there are two examples. One is for different specified turbine types
laid out in different wind farms. The other is for different hub heights of
three types of turbine.

windfarmlayout_overall
----------------------
Includes the inital functions for windfarmlayout, such as built coordinates
according to prevailing wind direction, relative position of every turbine in
the farm, and finally the wake lossed calculation.

    windfarmlayout_onetwofarm
    -------------------------
    With functions in windfarmlayout_overall, tried to layout two farms.They are
    not evenly laid out between each row in the limited farm square.
    The inital wind velocity data are imported from matlab file, and then calculated
    for real wind speed of back rows after wake losses.

    windfarmlayout_thirdfarm
    ------------------------
    With functioins inw windfarmlayout_overall, laid out third farm which is
    evenly laid out between each row and between each turbine in a row.


turbine_design
--------------
With rotor performance (power coefficient, pitch angle, and tip speed ratio),
and inital rotor speed and max tip speed ratio, there are three types of turbine
designed here: fixed-pitch and constant rotor speed, variable-pitch and constant
rotor speed, and commercial turbine from Mitsubishi one-MW. 
The designed components consist of rotor diameter, pitch angle or angle setting, 
power curve, thrust coefficient and power coefficient, and final hub height.
