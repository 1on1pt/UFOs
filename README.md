# UFOs
Building dynamic webpages by using JavaScript, CSS, Bootstrap, basic HTML, and Chrome developer tools.

## Overview of Project
The purpose of this project is to:

1. Build a table using data stored in a JavaScript array.
2. Create filters to make this table fully dynamic.
3. Place the table into an HTML file for easy viewing.

The benefit of a table that is *fully dynamic* is that it will react to user input.  The webpage was customized using Bootstrap, CSS, and HTML.

Dana, who is a data journalist, developed a webpage with a dynamic table that provides information to explore the question: UFO Sightings: Fact or Fancy?  Her table is working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, she added table filters for:

  * City
  * State
  * Country
  * Shape

### Resources
**Code:**

* app.js
* index.html

**Data:**

* data.js

**Software:**

* JavaScript
* CSS
* Bootstrap
* HTML
* Chrome Developer Tools
* Visual Studio Code 1.65.1


## Results
The new and improved **UFO Sightings: The Truth is Out There** webpage is now live and ready to be used by all ufologists!  As you recall, the original version of the webpage only could be filtered by *date*.  But this update includes these additional filtering capabilities:
 * City
 * State
 * Country
 * Shape

As you travel through *cyberspace*, you will ultimately *land* on this *unfiltered* webpage:

![UFO_webpage_challenge](https://user-images.githubusercontent.com/94148420/157881647-799974b5-84b9-4c18-a0ac-9729c2e48c78.PNG)


The unfiltered webpage allows you to scroll and browse through the database of UFO sightings.  Use of the **Filter Search** allows the user to narrow a search based on date, city, state, country, or shape.

![filter_search](https://user-images.githubusercontent.com/94148420/157994808-6a965ac9-3603-462c-830f-3a3ecafd1733.PNG)

A visitor to the webpage may choose one or more filters by entering the in the appropriate format.  For example, date is entered in the 1/10/2010 format and city, state, country, and shape entries are entered with a small case first letter.  Typing "1/12/2010" into the date filter and hitting ENTER will give the following eight results:

![date_1-2-2010_results](https://user-images.githubusercontent.com/94148420/157995357-fac15a86-7f0f-4958-8385-4c907f862a87.PNG)


But this particular search could be further refined if there is only an interest in UFO sightings in the State of Oregon on 1/12/2010.  In addition to typing in the date of 1/12/2020, **"or"** is entered in the Enter State filter followed by hitting the ENTER key or clicking the mouse outside of a filter box for the following two results:

![date_1-2-2010_or_results](https://user-images.githubusercontent.com/94148420/157995841-a7aa032c-2925-4bd9-abc2-840f7316c313.PNG)


To clear the entry for your next search, click on **UFO Sightings** in the upper left corner of the webpage:

![UFO_sightings](https://user-images.githubusercontent.com/94148420/157996397-c027d02c-55ad-4846-94dd-4f1ab61d0aad.PNG)


## Summary

### Drawbacks:
1. The entry of a filter must be precise in order for it to be recognized.  The user does not know what ranges for date, city, state, country, or shape would be available.  This could cause user frustration and therefore lead to unfavorable reviews of the webpage.
2. The database is "static" and therefore goes out of data quickly.

### Recommendations:
1. Provide date ranges and/or the ability to search by month/year.
2. Indicate that a "city is not included in the database" rather than having a blank table OR use dropdown lists.
3. Indicate that a "state is not included in the database" rather than having a blank table OR use dropdown lists.
4. Indicate that a "country is not included in the database" rather than having a blank table OR use dropdown lists.
5. Indicate that a "shape is not included in the database" rather than having a blank table OR use dropdown lists.
6. Use a live source for the database rather than a static source.
