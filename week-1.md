# Introduction
As part of the Minor Web Development and Design, each week we have a guest lecture.
This was the first guest lecture, it was held by FDND
Date:

## Campspace
Susan Lau works at Campspace. 
Campspace connects outside of the digital world: 'it's for looking for a camping space. It's basically like an Airbnb but for camping'.

### Data
All of this data is in a database. 
She was also talking about using an .exe list within the database.
With data you can make your static HTML more dynamic and we can do that with templating.
What she was showing was how she was looping through the data.

### Backend
All of the sortering and filtering is happening in the backend.

She was showing paths and how the filtering information shows up in the web adress.
The database uses one dimensional CSS.
They're using the framework Symphony.
They use elasticsearch. You can use different URL's for example for images. It helps you structure your data.
There are two types of datasets within elasticsearch: for presentation and for (filtering) backend. For example the height of an image is for backend not relevant information.
They're getting the data in JSON format.
Elasticsearch and filtering
She showed how we can filter with a get request in the browser. For example, we went to look for dutch campsites, then we can put in our code something like match = nl. Then when we check it on the website, when we're looking for dutch campsites, we see in the URL that search=NL was added.

This code below is wrong, but it's to prove a small example of what she had in elasticsearch and how she was filtering them (output was a JSON):

Take-aways from this presentation
Technology wise, don't re-invent it but tweak it. For example: every page has a body, a heading etc. but the content is different.
Name your variables and whatever good enough.
Code alot of things in english, because it's easier to find stuff.
