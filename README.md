# Entity-Frame-Work-Live-Project

# Introduction
The last live project of my studies at The Tech Academy was conducted in a two week sprint, working with other software developers using Agile/Scrum methodology. The project was to build software designed for a theater company to manage its website content without needing any technical knowledge. It will have multiple areas to manage admin needs, subscriber needs, and general public needs. The site will include information on the current season, past productions, the current cast members. It will allow the acting company to easily upload content. It will allow subscribers to easily manage their subscriptions.

<br>
# Text Helper Character Limit Helper Method
<br>
My frist story had me create a method that could be used to limit the number of characters displayed using ellipses. I created a static method in a new C# class folder that took in a string and integer.


<br>
# Create Model & CRUD Pages
<br>
I created the modle for a rental request and had a schema to follow for what it should include.  The end goal was to have the ability to add, edit, view details, and delete entries and then updated the database to create a table in the database. I used SQL Server Object Exploer to check that the table had been created correctly. I then scaffolded it to create a controller with views for CRUD functionality.

# Rental Request Index Page
<br>
My next story entailed building a accordion to display all the rental request to reveal a panel with additional details. I was giving a color theme and style of what the accordion should look like. I used bootstrap collapse to build the accordion. The user could input a start date/time and a end date/time for there rental. I implemented a time remaining on the rental on the far right of the header card of the accordion and if they rental had no started yet it would display the time until the rental started. Then the rental request on the index page was sorted by start date in ascending order. The rental request with later start dates and/or times were towards the bottom of the page. 
