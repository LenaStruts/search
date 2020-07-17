# search
In this project I built a copy of Google website using HTML, CSS and SASS. It consists of 3 pages: Google Search, Google Images and Google Advanced Search. To navigate between the pages there is a navigation in the top right corner. On the Google Advanced page to navigate back to Google Search it’s enough to press the Google logo at the top left corner. 

The copy of Google Search page contains a logo, search bar and navigation. The are also two buttons under a search bar, one is for simple google search and the other for the first search result – I’m feeling lucky. Since Google policy does not allow access to the first search result through query parameters, I also added a different version of Google Search page with a JavaScript function, which redirects to DuckDuckGo’s first search result. 

The copy of Google Images page is almost the same as the one for google search, but instead it gets the result of Google Image Search. There is also a small span tag that makes the logo look like the one from Google Image page.

The copy of Google Advanced Search page has 4 input fields with labels and comments to help organizing your search. To look for all, exact, any or none words or fraise I used as_q, as_epq, as_oq or as-eq parameters respectively. In order to style the labels I used CSS grid. 

Another thing, I can’t but mention is the 7-1 system I used to organize SASS. Pieces of reusable code were organized in partials and imported on the particular pages’ stylesheets. 
