========================================================================
This is the version of DNDC-BC (DNDC-Biochar-Controlled irrigation). It is a modified version of DNDC95, mainly changed the part of biochar and controlled irrigation.
========================================================================

In terms of the two-pool biochar model added, it was added in the module of manure amendment (type 11). You can choose it from the manure type, input soil C/N ratio, 
organic C, N, urea and NH4+, NO3-, biochar pH, absorption ratio, labile biochar rate, MRT of labile biochar pool (years), and MRT of recalcitrant biochar pool (years).

When it comes to the controlled irrigation (CI), one type of water-saving irrigation but different to AWD, it was inserted into the button of "controlled irrigation" in Flooding. 
For rice, there exist three ways for paddy irrigation in default settings, i.e., rainfed, traditional flooding (water levels keeps at 10 cm), and alternation wetting and drying (water 
level fluctuates between -5 cm and 5 cm). However, they cannot simulate CI treatment since they are totally different. According to CI treatment, only retains 5-25 mm of water 
layer in the regreening stage, and 60%-80% of saturated soil moisture content as the irrigation control index in other stages. No standing water layer was established except 
for pesticide and N fertilization under CI. 

We provide a simple example in 2016CC.dnd, which represents the treatment of CC (40 t ha-1 of biochar application) with CI in Kunshan, China. Please note the unit of fluxes.

When use this dnd file to run the model (the weather file is 2016.txt), the model will calculate the CH4, N2O emissions, yield and so on just like the DNDC95.
The results could be found in the File of Results/Record/Site, such as Day_SoilC_1, Day_SoilN_1, and so on.

The DNDC-BC could simulate GHG, C-N dynamics in paddy fields under biochar application and CI, but we admit this is just the first step of developing biocahr model.
We will continue develope and improve it in the future work.