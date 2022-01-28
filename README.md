# PyPSA-eur-adjustments-to-WITCH
Adjustments of PyPSA-eur code that have been made in order to make the scenarios comparable to the WITCH model

This folder contains the changed code of PyPSA-eur, that I modified during my Masterthesis in order to create more comparability between PyPSA-eur scenarios and the scenarios of the Integrated Assessment Model WITCH. The values applied to the PyPSA-eur scenarios are results of three scenarios in WITCH in the year 2030.

The modifications are:
* introduction of limits to conventional installed capacities in the script build_powerplants.py
* introduction of min. limits to variable renewable installed capacities in the scripts solve_network.py
* simulation of CCS technologies due to introduction of new technologies in the cost.csv file
