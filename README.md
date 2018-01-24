# Inequality in the primary healthcare from Andalucía
Fact-check: Are there differences in the health service among provinces? LINK
By Carmen Aguilar

![Ratio: population per centres](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/ratioCentres.png)

![Ratio: sanitary workers by type](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/ratio%202016.png)

![General frequency by province](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/Frequency.png)

![Change in the sanitary staff between 2009 and 2016](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/changeStaff.png)

![Example: Filter by category to see your area performance](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/FilterAreas.png)

![Map: density and older population distribution](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/mapPopulation.png)

![Map: find your health area](https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/HealthAreas.png)

In January 2018 I published a fact-check story that proved the differences in resources in the primary healthcare service within Andalucía. This was a project carried out for the MA Data Journalism at Birmingham City University. 

The graphics above are some of the charts published in "Fact-check: Are there differences in the health service among provinces?", as a result of the analysis. 

The parameters considered in this work agree with those taken into account by the Spanish Health Ministry to assess the area. I analysed professionals, centres, and frequency among the eight provinces from Andalucía and among the health areas (smaller sanitary divisions). 

## Get the data

The data was downloaded from the <a href="https://www.msssi.gob.es/estadEstudios/estadisticas/sisInfSanSNS/home.htm">Spanish Health Ministry database</a>.

<ul>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/20171208_Centros_de_Atencion_Primaria.csv">CSV: Primary Healthcare Centres</a></li>
<li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/poblacionasignada.csv">CSV: Population allocated in Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/dispositivosurgextrahospital.csv">CSV: A&E in non-hospital units in Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/ratioprofesional%20provincia.csv">CSV: Ratios per professional in health areas from Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/ratioprofesionalProvinciaSolo.csv">CSV: Ratios per professional in provinces from Andalucía/a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/profesionalesAT.csv">CSV: Number of professionals per type by health area and province in Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/frecuentacionAPtotalAND.csv">CSV: General frequency by province from Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/freqUregenteProvinciasSolo.csv">CSV: Emergency frequency by province from Andalucía</a></li>
   <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/frecuentacionAP.csv">CSV: General frequency by health area from Andalucía</a></li>
   <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/frecuentacionUrgenciaZonas.csv">CSV: Emergency frequency by health area from Andalucía</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/poblacionmayor.xlsx">XLSX: Population by age in Andalucía by town.</a></li>
  <li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/densidad%20poblacio%CC%81nFinal.xlsx">XLSX: Population density in Andalucía by town.</a></li>
  </ul>

## See the analysis
<ul>
<li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/Primary%20Health%20AND.Rmd">R Notebook about the analysis regarding centres: </a>rate of people by centre, number of centres, number of centres by type, and ratio of population by A&E in non-hospital units. Ratios in provinces and health areas.</li>
  
<li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/Doctors%20and%20nurses.Rmd">R Notebook about the analysis regarding professional: </a>ratio of GP, paediatric, nurse and assistant administrative by population allocated. Number of professionals by type in 2009 and 2016 and change between those two years. Figures are calculated by provinces and health areas.</li>

<li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/Frequency.Rmd">R Notebook about the analysis regarding frequency: </a>general and emergency frequency by provinces and health areas.</li>

<li><a href="https://github.com/Carmen-Aguilar/Andalucia-healthcare/blob/master/population.Rmd">R Notebook about population: </a>evolution of the allocated population and proportion of older group.</li>
</ul>

## Visualisation

<strong>Column charts</strong> were made using <a href="https://flourish.studio/">Flourish.studio</a>. This type is used to show comparison about:
<ul>
  <li>Ratio of people by centres and number of centres in each province.</li>
  <li>Ratio of people by type of professional and evolution between 2009 and 2016.</li>
  <li>Number of professionals by type and percentage of change between 2009 and 2016.</li>
  <li>Frequencies rates.</li>
</ul>
<strong>Maps</strong> were built in Carto, using the shape file from the <a href="https://www.juntadeandalucia.es/institutodeestadisticaycartografia/DERA/g17.htm">nstituto de Estadística y Cartografía de Andalucía.</a>
<ul>
  <li>Map that show the distribution of population according to parameters of density of population and age.</li>
  <li>Map that show the borders of each health area and their names.</li>
  </ul> 
  
<stron>Bar charts built in JS</strong> using <a href="https://canvasjs.com/javascript-charts/">CanvasJS</a> that allow the user filter by category and get the local information. 
