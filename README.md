# MontgomeryCrimes

Este projeto tem o objetivo de realizar análises a respeito dos crimes ocorridos em Montgomery Count, Maryland, no ano de 2013.

Os dados utilizados estão no arquivo "MontgomeryCountyCrime2013_2.csv" deste repositório, mas também podem ser acessados no website de dados abertos do Condado de Montgomery, dataMontgomery (https://data.montgomerycountymd.gov/). Cada linha de dados corresponde a um crime reportado por um oficial de lei e contém as seguintes informações:

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

Para a manipulação dos dados, foi utilizada a linguagem Python 3 e a biblioteca Pandas.
