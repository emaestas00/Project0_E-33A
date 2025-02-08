# Project0_E-33A
Project 0 for Spring 2025 Harvard extension school 
# Background for Project 0
The goal of this project is to introduce how HTML forms interact with web servers using GET Parameters, specifically using Google as our example. We are tasked with expanding on the index.html distribution code and building out own operable version of Google Search, Google Image Search, and Google Advanced Search. 
# Guidelines - Highlight 
    * We should have at least 3 pages: Google Search, Google Image Search, Google Advanced Search
    * On each of the other two pages there should be a link to navigate back to the Google Search
    Functionality
    * Google Search - Users should be able to type into the search bar and taken to the Google results. 
    * On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
    * On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options)
    * When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.
    * “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.

    Design
    * Search bar should be centered
    * Search bar should have rounded corners
    * Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
    * The CSS you write should match Google’s own aesthetics as best as possible.
# index.html 
The index page serves as my homepage and the first of 3 pages we are tasked with building. This is the custom front-end for Google search. It features a navigation bar with links to Google Images and Advanced Search. The page displays the Google logo and includes a search form where users can enter a query. The form submits the search to Google using the q parameter. Additionally, it provides two buttons: "Google Search," which performs a standard search, and "I'm Feeling Lucky," which directly takes the user to the top search result. The page is styled using an external CSS file (styles.css) for improved layout and design.


# googleimage.html
The googleimage.html page provides a custom front-end for Google Images search. It includes a navigation link back to the main Google Search page. The page features the Google Images logo and a search form where users can enter a query to find images. The form submits the search to Google with the tbm=isch parameter, which specifies an image search. When a user enters a search term and clicks the "Google Search" button, they are directed to the corresponding Google Images results. 


# googleadvanced.html
The googleadvance.html page provides a custom front-end for Google's Advanced Search, allowing users to refine their searches with more specific criteria. The page includes a navigation bar linking back to the main search page and displays the Google logo for consistency.The Advanced    Search form contains input fields where users can:
    Search for results containing all specified words (as_q).
    Search for an exact phrase (as_epq).
    Find results containing any of the given words (as_oq).
    Exclude results containing specific words (as_eq).

The as_q, as_epq, as_oq_ and as_eq are Google's GET Parameters 

# Solution for finding the GET Parameters
This week in the hint we were given it was said to explore the URL. If we perform a google search, and in sections this week we explored the 'cats' we saw some letters after the search. It would end up having /search?q=cats at the end of the URL. The q=cats is the GET parameter. I was able to apply this same knowledge to the Google Search and Image Search. For the advanced search it was also the same process where these parameters were at the end of each URL so in searching to things I was able to find them.

# styles.css
The styles.css file provides a clean and responsive design for the Google Search, Google Images Search, and Advanced Search pages. The Google Search and Google Images hold a lot of the same styling where as the Advanced Search did have additional style requirements for the buttons and boxes. 


# resources
Below are resources that helped me complete this weeks assignment
1. Google Branding
    https://partnermarketinghub.withgoogle.com/brands/google-assistant/overview/color-palette-and-typography/
    https://developers.google.com/fonts/faq
    https://www.color-hex.com/color-palette/1872
2. CS50.ai 
    * Helped with answering questions on formating the HTML script
    * Helped me understand the "View Page Source" hint to review Googles underlying HTML. 
3. Visual Studio Auto-Helper
    * Visual Studio was recommended to use during sections. When commenting out my code it provided very quick useful suggestions which I found were more streamlined than my original comments. 
    
    
