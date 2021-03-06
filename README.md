# Entity-Frame-Work-Live-Project

# Introduction
The last live project of my studies at The Tech Academy was conducted in a two week sprint, working with other software developers using Agile/Scrum methodology. The project was to build software designed for a theater company to manage its website content without needing any technical knowledge. It will have multiple areas to manage admin needs, subscriber needs, and general public needs. The site will include information on the current season, past productions, the current cast members. It will allow the acting company to easily upload content. It will allow subscribers to easily manage their subscriptions.


# Text Helper Character Limit Helper Method

My frist story had me create a method that could be used to limit the number of characters displayed using ellipses. I created a static method in a new C# class folder that took in a string and integer.
<br>

<a href ="https://github.com/codhharris713/Entity-Frame-Work-Live-Project/blob/main/texthelper.png"> Text Helper </a>



# Create Model & CRUD Pages
I created the modle for a rental request and had a schema to follow for what it should include.  The end goal was to have the ability to add, edit, view details, and delete entries and then updated the database to create a table in the database. I used SQL Server Object Exploer to check that the table had been created correctly. I then scaffolded it to create a controller with views for CRUD functionality.
<br>

<a href ="https://github.com/codhharris713/Entity-Frame-Work-Live-Project/blob/main/rental_request_model.png"> Model </a>

# Rental Request Index Page
My next story entailed building a accordion to display all the rental request to reveal a panel with additional details. I was giving a color theme and style of what the accordion should look like. I used bootstrap collapse to build the accordion. The user could input a start date/time and a end date/time for there rental. I implemented a time remaining on the rental on the far right of the header card of the accordion and if they rental had no started yet it would display the time until the rental started. Then the rental request on the index page was sorted by start date in ascending order. The rental request with later start dates and/or times were towards the bottom of the page. 
<br>

![rental_request](https://user-images.githubusercontent.com/83795096/149723380-37733c87-1a00-4946-ac7a-9f825c22b0c1.gif)
<br>

<a href ="https://github.com/codhharris713/Entity-Frame-Work-Live-Project/blob/main/rental_request_start_end_time.png"> Accordion with start and end date/time logic </a>
<br>

<a href ="https://github.com/codhharris713/Entity-Frame-Work-Live-Project/blob/main/accordion.png"> Accordion Content </a>
<br>

I used Font Awesome Icons to change the action links to their respective edit, details, and delete symbols.
<br>
![icons](https://user-images.githubusercontent.com/83795096/149725504-68386d69-8f17-4554-9a8f-dd9fc6a718ac.png)

<a href ="https://github.com/codhharris713/Entity-Frame-Work-Live-Project/blob/main/action_links.png"> Action Links </a>


