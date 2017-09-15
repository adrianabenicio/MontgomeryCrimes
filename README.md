# MontgomeryCrimes

This project aims to conduct analyzes of crimes in Montgomery Count, Maryland, in the year 2013.

The data used is in the "MontgomeryCountyCrime2013.csv" file of this repository, but can also be accessed on the Montgomery County open data website: dataMontgomery (https://data.montgomerycountymd.gov/). Each row in the data is a crime reported by a law enforcement officer and contains the following information:

* **Incident ID**: Police Incident Number
* **CR Number**: Police Report Number
* **Dispatch Date / Time**: The actual date and time a Officer was dispatched
* **Class**: Four digit code identifying the crime type of the incident
* **Class Description**: Common name description of the incident class type
* **Police District Name**: Name of District (Rockville, Wheaton etc.)
* **Block Address**: Address in 100 block level
* **City**: City
* **State**: State
* **Zip Code**: Zip code
* **Agency**: Assigned Police Department
* **Place**: Place description
* **Police Sector**: Police Sector Name
* **Beat**: Police patrol area subset within District
* **PRA**: Police patrol are subset within Beat
* **Start Date / Time**: Occurred from date/time
* **End Date / Time**: Occurred to date/time
* **Latitude**: Latitude
* **Longitude**: Longitude
* **Police District Number**: Major Police Boundary
* **Location**: Location

For the manipulation of the data, the Python 3 language, the NumPy and the Pandas libraries were used. For data visualization, we used the seaborn and matplotlib libraries.

# Objectives

* Explore the data and perform a preprocessing to fit them for analysis;
* Apply the tools that the Python language offers to fit the data and perform statistical analysis;
* Answer the proposed questions appropriately and provide a good data visualization through charts;
* Elaborate relevant questions whose answer produces important information.

# Insights

From the crime data, the main insights were:

* Determine the longest and shortest police response time. The purpose of this evaluation was to verify the quality of the police service through the response time and to determine if this time varies according to the district.
* Another insight was to find the most common crime by the district. From this information is possible to analyse if there are common crimes in neighboring districts and to think about a possible spreading of that crime.
* Furthermore, a relevant information could be to know in which places there are more occurrences of crimes and in which shift these crimes are most common.
* Finally, other relevant information comes from determining the percentage of crimes against children, animals, and how many crimes involve drugs, sexual offenses, and unauthorized taking of someone’s personal property.

# Conclusions

* For dispatch time analysis, three factors were used: hour, day of the week and month. According to the hours chart, most crimes occur during the morning (7am to 12pm). The beginning of the week was also the period most frequently (Monday, Tuesday and Wednesday). The analysis of the months was a little bit inconclusive, since the results were homogeneous where we have a maximum of 180 crimes of variation with the monthly average.
* The analysis of the location of the crimes indicated the Silver Spring district as the most violent, with the highest number of crimes per capita and covering the highest number of violent crimes.
* It was also observed that the most violent crimes occur in the morning and in places of residential life, like single family residence, apartments / condominiums, streets, parking lots, etc.
* Analyzing the types of crime, we realize that the most common crime is "Driving under the influence" and there are 31 least common crimes (like parking offenses, robbery using a knife as weapon and others) with just one occurrence each.
* 20.7% of the crimes are violent and the most common violent crime is "Driving under the influence" too. The most common nonviolent crime is "CDS-poss marijuana/hashish".
* 45.18% of the crimes involve the unauthorized taking of someone’s personal property by another person and 20.02% are drug-related crimes. 
* Crimes against children compose 0.58% of the crimes, while sex crimes are 1.04% of the total.

# Contributors

* Adriana Benício Galvão
* Gisliany Lillian Alves de Oliveira
* Jéssica Cabral de Araújo
