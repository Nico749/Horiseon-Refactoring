# Horiseon-Refactoring
The goal of the refactoring is to make the Horiseon website more accessible, boosting its ranking on search engines. We also want to fix link bugs and missing code parts and consolidate the CSS efficiency 

USER STORY 
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

ACCEPTANCE CRITERIA 
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

ISSUES FIXED:
-CSS file was not efficient, with multiple code lines doing exactly the same thing
-Missing alt attributes on all the images, making the website not accessible
-Heading attributes were not in the proper order
-Title was too generic and non descriptive
