# Methods for extract and validate nº deaths per state in Brazil

<h2>Introduction</h2>
<p> In Brazil we have three databases that account for all deaths in the country, all these sources are derived from a single and rigorous epidemiological document in Brazil.</p>

<p><b>The Death Declaration</b>, a 3 way form document exclusively completed by physicians, is mandatory for all burials and for issuing the Civil Certificate of Death, being the source of all mortality data since 1977.<br> Even though it is considered the most reliable Brazilian health index, we still observe a not negligible degree of under reporting, especially in rural areas at states from North and North-East regions.
</p>
<h2> IBGE - Civil Registry offices</h2>
The IBGE (Brazilian Institute of Geography and Statistics) since  1974 by law force was the official organ responsible to collect and interpreters  all mortality data.IBGE use civil registry offices from source and makes public available its data before analyze and verifies. However since today 30-Oct-2021 only mortality data until 2019 is available.

<h2> SIM - MS/ DataSUS - Ministry of health database of unified health system </h2>

In 2011, due to the already known under reporting of deaths indexes in the more distant and rural states and regions of the country, a more robust and less bureaucratic death accounting was developed, since the data from civil registry offices legally was a longer period permission for notification.
The SIM-MS/SUS (Mortality Information System) has more accurate data and specified infos like cause of deaths with ICD 10 classification and more demografic and populational classified infos.
<h2>Portal transparencia ARPEN Civil Registry</h2> 
Available for access since 2018, and maintained by the National Association of Registrars of Natural Persons (ARPEN), this portal is a free-access site, which was developed with the purpose of providing, in parallel, some information on births, marriages and deaths. It is not an official source of vital statistics and all information from this source comes from the Civil Registry Information Center (CRC). However, it is the only source of information on deaths for 2021, being updated daily and providing the total number of deaths monthly by place of occurrence. Several authors emphasize that the data reported are related to deaths from non-traumatic or natural causes.

<h2>METHODS </h2>

Using these premises and knowledge of the advantages and disadvantages of each data source, we developed a systematic and easily reproducible method to obtain data on deaths in Brazil by state, as close as possible to reality.

1. We extracted all monthly mortality data from natural and undetermined causes from IBGE from Jan/14 to Dec/19.

2. We extracted all the total monthly mortality data and subtracted the traumatic causes from the SIM-MS/DataSUS from Jan/14 to Dec/19, and also the preliminary data from Jan/20 to Dec/20.

3. We extracted all the total monthly mortality data from the ARPEN Civil Registry portal from Jan/18 to Aug/21.

We make all these preliminary data available in the dataset of this project at the link: https://dataverse.harvard.edu/dataverse/covidbr

Analazing 