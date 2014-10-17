readme.txt

This is the readme for lab6 by Woody Butler
10/16/2014 Comp20
The lab's objectives were to:
Practice writing JavaScript.
Practice using a third-party API.
Practice parsing JSON data.
Understand the limitations of client-side JavaScript.

We practiced using javascript sucessfully in conjunction with the Google maps API.
The limitations of client-side Javascript disallowed the project from accessing the MBTA API in realtime as it was not Cross-origin resource sharing enabled. The best we could have done would be to open up the API and copy the text into the html file, which would give the data for a snapshot of the red line. This was not attempted when I realized that live updates would not be an option. Client-side Javascript has many quirks and a few glaring limitations, namely the CORS issue. This varies by API however. 