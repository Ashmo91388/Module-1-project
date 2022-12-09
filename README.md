## Description
As a developer, I want to optimize the Horiseon website for more readable, and accesible utilization.
By doing so, I have refactored both the HTML.index as well as CSS. Updates are as follows: 

added "Horiseon" to <title> on line 7

added alt attributes to lines, 
30, 37, and 44 with attribute "keyboard coffee and notepad"

changed line 13 in html.index to <nav> which then changed line 35 in css to header nav ul li to target all nav items in container, and then removed line 39 as it would then be redundant.

removed line 29 class "search-enging-optimization was redundant, added 'id' class to line 30 so that link from line 16 in <nav> section can move user to search optimization section in browser.

added float: right property to line 45 CSS to move nav list items to the end. 

removed line 44 'a' element and line 49 'p' element in css as it already applies to universal selector. 

removed line 91 in css and changed line 93 to just .benefits semantic element so all benefits elements are targeted

added line 97 to css with 10px padding so that there is space in between h3 headers, and all are targeted.

##Acceptance Criteria##
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

