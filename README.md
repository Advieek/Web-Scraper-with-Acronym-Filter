This code is a basic setup of a webscraper tool with some added tools for my specific application.

Firstly this code consists of the Web Scraper. It starts out by using the BeautifulSoup library to convert text into a more usable format. 
This is done through the utilization of HTML tags to find the specific body of text to take information from.

After this it goes through a filtration process to extract possible acronyms from the text it just got. 
It finds consecutive capital letters which means its unlikley to find acronyms such like eABC, A.B.C, or even AbCD.
I do plan to add an updated version that is able to find these aswell but for now this is sufficient since in my use case its unlikley for acronyms as such to be present.
It also does check for duplicate terms to make sure the same acronym doesnt pop up twice 

Finally the last steps is to just organize everything into a numbered list making it easy to know the total number of acronyms found as well as organize the data further.
At the end it exports all the data as a file as whatever type you need. 
