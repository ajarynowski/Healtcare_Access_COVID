# Healtcare_Access_COVID
Access to healthcare as an important moderating variable for estimating geography of immunization level for COVID-19 and its derivatives


We show on the example of Poland that omitting HCA confounding factors could lead to misinterpretation in understanding current epidemic dynamics due to biased estimation of immunity levels. 

# Data description
Data obtained from Polish registries on 16 voivodeships (NUTS-2) and 380 poviats (old NUTS-4):

    • Cumulative No. cases per capita: The cumulative numbers of COVID-19 notifications till the so-called 3rd wave of epidemic (04.03.2020 - 15.06.2021) for poviat or voivodeship [16] divided by its population size. 
    • Healthcare Access – Supply (supply HCA): The number of physicians working in health care per 10,000 inhabitants as an indicator of the supply HCA for poviat or voivodeship [17]. This is a good proxy for capacity and accessibility of healthcare services (public and private).      
    • Healthcare Access – Demand (demand HCA): The number of consultations in primary care provided in 2019 for poviat or voivodeship divided by its population size as an indicator of demand HCA [17]. Pearson correlation on demand HCA in 2019 and 2020 is 0.998 [13], so no significant regional changes have been observed in the demand for HCA due to the pandemic. Demand HCA is a complicated conglomerate of attitudes towards healthcare (i.e. level of trust in the effectiveness of offered treatment by public healthcare), perception of accessibility (i.e. how easily one can reach healthcare facilities), burden of disease (i.e. elderly and inferior health populations seek healthcare more often) and others (i.e. constrains and limits provided by National Health Fund).   
    • Fraction of vaccinated: Percentage of vaccinated with at least one dose for poviat or voivodeship (at the end of 3rd wave as of 15.06.2021) for all age groups [18]. Vaccination coverage gives us a proxy of proportions of population which gain post-vaccination immunity before the so-called 4th wave.   
    • Normalized incidence Sep/Oct’21: 2-week incidence of COVID-19 notifications (21.09–04.10.2021) during the beginning of the so-called 4th epidemic wave for a poviat [16].
    • Normalized deaths Sep/Nov’21: Crude mortality rate – Cumulative number of COVID-19 death cases (15.09–21.11.2021) during the so-called 4th epidemic wave per poviat divided by its population size [19].
    • Normalized Hospitalizations: Number of occupied hospital beds (14.10.2021) at the beginning of the so-called 4th epidemic wave per voivodeship divided by its population size [20].
    • Seroprevalence – Obser-Co: The fraction of seroconverted [21] per voivodeship in a random (by design) sample as a proxy for immunity level collected during 29.03–14.05.2021. As this was the end of the 3rd epidemic wave, as well as the vaccination roll-out was at the beginning, this variable is a good proxy of post-infection acquired immunity.
    
  # Analysis
  
    The dynamics of SARS-CoV-2 spreading vary across the spatial clusters and initial conditions as number of index cases and immunity levels could lead to different phases at the beginning of each wave. Thus, supply/demand HCA are assumed to be moderating variables that affect the relationship between independent (vaccine or post-infection immunity at the end of 3rd wave) and dependent variables (seroprevalence and the 4th wave outbreak dynamics indexes). In a series of diagrams, we depict the explained share of variance for selected dependent variables of interest as calculated by multiple regression.
