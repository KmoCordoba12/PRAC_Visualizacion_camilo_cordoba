# PRAC_Visualizacion_camilo_cordoba
Datos y preparacion de los mismos para la creacion del dashboard publicado en Tableau Public: https://public.tableau.com/views/Climatechangeandenergy/Analysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---
Data and its preparation for the creation of the dashboard published on Tableau Public: https://public.tableau.com/views/Climatechangeandenergy/Analysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Archivos

Se comparte el notebook y los datos utilizados para la creacion del dashboard:

* **PRAC_Visualizacion_camilocordoba.ipynb** Notebook con el código relacionado a la preparacion de los datos cargados en Tableau.
* **carpeta data_original** incluye los 19 data sets originalmente descargados de la pagina web https://ourworldindata.org
* **carpeta data_cleaned** incluye la data resultante del proceso de preparacion y que se carga en Tableau.
*  **data_cleaned/ merged_data.csv** archivo con la data unificada de las 19 fuentes y cargada en Tableau

---

The notebook and data used to create the dashboard are shared:

* **PRAC_Visualizacion_camilocordoba.ipynb** Notebook with the code related to the preparation of the data loaded into Tableau.
* **data_original folder** includes the 19 data sets originally downloaded from the website https://ourworldindata.org
* **data_cleaned folder** includes the data resulting from the preparation process and loaded into Tableau.
*  **data_cleaned/ merged_data.csv** file with the unified data from the 19 sources and loaded into Tableau

## Diccionario de datos / Data diccionary
Here is the updated list using your requested Variable | Type | Description format, based on the metadata from your documents.

Entity | String – Key | Nombre del país o region

Code | String – Key | Codigo del país o región

Year | Number – Date | Año

Annual area burnt by wildfires | Integer | Area annual Quemada por incendios forestales

Annual CO2 emissions | Integer | Cantidad de CO2 emitido por país en medido en toneladas

Annual CO2 emissions per capita | Decimal | Cantidad de CO2 emitido por persona medido en toneladas

Consumption of controlled substance (zero-filled) - Chemical: All (Ozone-depleting) | Double | Consumo de diversas sustancias controladas (BCM, CTC, CFC, HBFC, HCFC, HFC, MB, TCA y otros CFC totalmente halogenados).

Forest Area | Integer | Superficie de más de 0,5 hectáreas con árboles de más de 5 metros de altura y una cobertura de copas superior al 10 %, medido en Km2.

Gas consumption - TWh | Decimal | Consumo de gas natural por terawatt-hours

Coal consumption - TWh | Decimal | Consumo de carbon por terawatt-hours

Oil consumption - TWh | Decimal | Consumo de gasolina por terawatt-hours

Fossil fuels (TWh) | Decimal | Consumo de combustibles fósiles en terawatt-hours

Fossil fuels per capita (kWh) | Decimal | Consumo de combustibles fósiles por persona en Kilowatt-horas

population not using safely managed drinking water services | Integer | Fuente de agua potable mejorada disponible en las instalaciones, libre de contaminación fecal y química.

Access to electricity (number of people without access) | Integer | Cantidad de personas que no tienen acceso a electricidad en sus hogares.

Concentrations of fine particulate matter (PM2.5) - Residence area type: Total | Decimal | Concentración de PM2.5

Ozone - Minimum daily concentration | Integer | Concentración de ozono medida en Dobson Units (DU)

Ozone - Mean daily concentration | Integer | Concentración de ozono medida en Dobson Units (DU)

Global average temperature anomaly relative to 1861-1890 | Double | Diferencia en la temperatura media de la superficie terrestre y marina en grados Celsius.

Land use: Built-up area | Double | Superficie total construida en Km2

Land use: Grazingland | Double | Superficie total de pradera en Km2

Land use: Cropland | Double | Superficie total área de cultivo en Km2

Mismanaged plastic waste (metric tons year-1) | Integer | Plásticos desechados incorrectamente medidos en toneladas.

---

Entity | String – Key | Name of country or region

Code | String – Key | Country or region code

Year | Number – Date | Year

Annual area burnt by wildfires | Integer | Annual area burnt by wildfires

Annual CO2 emissions | Integer | Amount of CO2 emitted per country measured in tonnes

Annual CO2 emissions per capita | Decimal | Amount of CO2 emitted per person measured in tonnes

Consumption of controlled substance (zero-filled) - Chemical: All (Ozone-depleting) | Double | Consumption of various controlled substances (BCM, CTC, CFC, HBFC, HCFC, HFC, MB, TCA and other fully halogenated CFCs).

Forest Area | Integer | Area of more than 0.5 hectares with trees taller than 5 metres and a canopy cover of more than 10%, measured in km2.

Gas consumption - TWh | Decimal | Natural gas consumption per terawatt-hours

Coal consumption - TWh | Decimal | Coal consumption per terawatt-hours

Oil consumption - TWh | Decimal | Oil consumption in terawatt-hours

Fossil fuels (TWh) | Decimal | Fossil fuel consumption in terawatt-hours

Fossil fuels per capita (kWh) | Decimal | Fossil fuel consumption per person in kilowatt-hours

Population not using safely managed drinking water services | Integer | Improved drinking water source available on premises, free from faecal and chemical contamination.

Access to electricity (number of people without access) | Integer | Number of people without access to electricity in their homes.

Concentrations of fine particulate matter (PM2.5) - Residence area type: Total | Decimal | Concentration of PM2.5

Ozone - Minimum daily concentration | Integer | Ozone concentration measured in Dobson Units (DU)

Ozone - Mean daily concentration | Integer | Ozone concentration measured in Dobson Units (DU)

Global average temperature anomaly relative to 1861-1890 | Double | Difference in average land and sea surface temperature in degrees Celsius.

Land use: Built-up area | Double | Total built-up area in km2

Land use: Grazingland | Double | Total grassland area in km2

Land use: Cropland | Double | Total cropland area in km2

Mismanaged plastic waste (metric tons year-1) | Integer | Incorrectly disposed of plastics measured in tonnes.
