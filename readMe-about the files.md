In this repo you will find the files used to perform Data Asssimilation on the COVID-19 datasets of the following four countries:

1. USA πΊπΈ

2. Guyana π¬πΎ

3. Ethiopia πͺπΉ

4. Trinidad πΉπΉ

Here is a brief breakdown of what each file does:

- Excel sheets:   Saved in '.csv' format, these contain the time series data for each country
- Read_data.  :   Here is where the model loads the time series files for each country
- Initialize_SEIR:This is the place to edit parameters such as vaccination and death rates
- Free_Run:       In these files you can run the SEIR model without data assimilation to check its performance
- Configure_DA:   These files contain the baseline configurations for DA used for each country, including observational variances, filters, ensemble sizes and errors
- Observer:       Here you will find the configuration for the different state variables to be plotted and observed (Active, Recovered, Death, Vaccinated)
- DA_exps:        Here you will find more in depth configurations for the initialization of the model, including time periods, free_run and DA configurations 
- Compare_runs:   Here you can provide unique configurations for differing data sets and perform sensitivity runs
- SEIR_eqns:      Find the equations used in the operation of the SEIR_model

The time-series covid data used in this project were primarily taken from the following sites:

- Our World in Data: https://ourworldindata.org/covid-cases
- The Human Data Exchange: https://data.humdata.org/event/covid-19

