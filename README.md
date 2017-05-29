# Udacity---Make-effective-data-visualisation

**Summary**-in no more than 4 sentences, briefly introduce your data visualization and add any context that can help readers understand it  
This data visualization intends to :  
* highlight the growing number of forcibly displaced people by country of origin over the years since 1951  
* correlate the main sources with armed conflict or wars location
  

**Design** - explain any design choices you made including changes to the visualization after collecting feedback  
I choose to represent the number of forcibly displaced people by circles appearing on the related country on a world map. The size of the circle is proportional to the number of displaced people. I choose to identify location of armed conflicts by coloring countries in red (2 possible instensities : light red for small armed conflict and red for wars). I also choose to design a bar charts showing the evolution of forcibly displaced people worldwide other the year. The y-axis scale of change depending the worlwide or countries view to better see the forcibly displaced people evolution for a country. I made this update after a feedback highliting that as the number of displaced people for one country is so small regarding the worlwide value that one unique scale does not allow an optimal visualization.
The legend is composed of three elements. The first one is a dynamic element identifying the value of displaced people the location and the year considered. The second one identify the armed conflict intensity color scale. The third one are circles explaining the link between the size ans the number of displaces people. I had last one after feedbacks explainign that it was not clear what the blue circles represent. Finally I had animations to my visualization. It starts with a dynamic evolution form 1951 to 2014. Afterwards it is allowed to update the visualization by clicking on any countries on the map or a bar charts for a given year. Clicking on the background reset to the worlwide visualization.


**Feedback** - include all feedback you received from others on your visualization from the first sketch to the final visualization  

**Resources** - list any sources you consulted to create your visualization  
* Displaced people data : http://popstats.unhcr.org/en/persons_of_concern
* Armed conflict data : http://ucdp.uu.se/downloads/
* https://bl.ocks.org/mbostock
