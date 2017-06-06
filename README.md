# Udacity---Make-effective-data-visualisation

**Summary**  
This data visualization intends to :  
* highlight the growing number of forcibly displaced people by country of origin over the years since 1951  
* correlate the main sources with armed conflict or wars location
  

**Design**   
I choose to represent the number of forcibly displaced people by circles appearing on the related origin country on a world map. The size of the circle is proportional to the number of displaced people. I choose to identify location of armed conflicts by coloring countries in yellow (2 possible instensities : light red for small armed conflict and red for wars).  
I also choose to design a bar charts showing the evolution of forcibly displaced people worldwide other the year. The y-axis scale change depending the worlwide or countries view to better see the forcibly displaced people evolution for a country. I made this update after a feedback highliting that as the number of displaced people for one country is so small regarding the worlwide value that one unique scale does not allow an optimal visualization.  
The legend is composed of three elements. The first one is a dynamic element identifying the value of displaced people the location and the year considered. The second one identify the armed conflict intensity color scale. The third one are circles explaining the link between the size ans the number of displaces people. I had last one after feedbacks explainign that it was not clear what the blue circles represent. Finally I had animations to my visualization. It starts with a dynamic evolution form 1951 to 2014. Afterwards it is allowed to update the visualization by clicking on any countries on the map or a bar charts for a given year. Clicking on the background reset to the worlwide visualization. I also add a tooltip when passing on bubbles in order to identify the country associated.


**Feedback**  

*Feedback n°1  - Status of the project : Initial sketch*
When I start the project I just wanted to show the growing number of forcibly displaced people other the world. When I share my first visualization with my friends their feedback was : "Ok great but what is your message? What is the main reason for forced migration? " I decided to add to my visualization armed conflict location and make the correlation stands out.  

*Feedback n°2 - First visualization released*   
The feedback was to add a legend explaining the meaning of the circles and sizes. I decide to add this legend

*Feedback n°3 : First visualization released*  
In my first released, on click on a country, the bar chart was updated for the country but the scale was the same as the worlwide view. As a consequence, the bar charts for a giving country show almost nothing. I also took into account this feedback addign a updating scale to the bar charts

*Feedback n°4 : Second vizualisation relaesed with above feedbacks integrated*  
Several feedbacks mentionned I should add a title to the bar chats y-axis to be clear on what I show. I add it

*Feedback n°5 : Final visualization*  
The feedback were very positive. I get particulary good feedbacks on the animation capabilities  

*Feedback n°6 : First review*  
It was recommended to add a sentence making my visualization explanatory. I add them beneath the title. It was also recommended to add a tooltip when passing on circles. I add it too. At last it was recommended to change the armed conflict location colors from red to something less striking. I choose light yellows shades.

**Resources** 
* Displaced people data : http://popstats.unhcr.org/en/persons_of_concern
* Armed conflict data : http://ucdp.uu.se/downloads/
* https://bl.ocks.org/mbostock
