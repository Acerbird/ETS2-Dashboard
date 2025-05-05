# ETS2-Dashboard
The goal is a dashboard that shows a map of Europe with numbers in each country. 
Maybe even paint each country depending on the number.
The numbers shall represent the additional costs calculated from the inputs of the user due to the new CO2 price on heating from the ETS2.

The user shall be able to input their own heating parameters. 
Parameters to add:
- Heating Fuel
- own consumption (standard in kWh/a) but an additional choosing option where one can choose the unit of the consumption input (kg,l,GJ,ton,...)
- country

- a slider that determines the CO2 price of ETS2 for which the additional costs shall be computed

To implement this dashboard I want to use the python package shiny. 
