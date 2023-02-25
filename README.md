
# Event Management System

An event management system is a software application or platform that helps individuals or organizations plan, organize, and execute events more efficiently. The goal of an event management system is to streamline the event planning process and ensure that events run smoothly and successfully.

## Working
- When the website is opened, it will ask for all the event related details that has to be filled by the event coordinator. 
- Agree to the terms and conditions and hit save.
- This will upload the event details to the database and one can see the event and register for it through the search section in the navbar.
- other operations like generating reportm edit or deleting a particular event can be done through the respective sections in the navbar.
## Technologies used

1. html - to design the body of the website.
Read more -> https://developer.mozilla.org/en-US/docs/Web/HTML

2. CSS - For the appearance, design of the website.
Read more -> https://developer.mozilla.org/en-US/docs/Web/CSS

3. JavaScript - to make the website responsive for the client side.
Read more -> https://developer.mozilla.org/en-US/docs/Web/JavaScript

4. PHP - to make the website responsive for the server side.
Read more -> https://www.w3schools.com/php/

5. Bootstrap - Framework used for development of website.
Read more -> https://getbootstrap.com/docs/5.3/getting-started/introduction/

6. SQL - Database used to store the informaion
Read more -> https://www.w3schools.com/sql/
## HTML

- HTML (Hypertext Markup Language) is a markup language used to create and structure web pages. It consists of a series of elements and tags that define the content and layout of a web page.

- HTML tags are used to define the different types of content on a web page, such as headings, paragraphs, images, links, forms, and more.

- The HTML code is interpreted by web browsers to display the content and structure of a web page to users. 

- HTML is often used in conjunction with other technologies, such as CSS (Cascading Style Sheets) and JavaScript, to create visually appealing and interactive web pages.


## CSS
- CSS (Cascading Style Sheets) is a styling language used to describe the presentation and layout of HTML and XML documents, including web pages.

- It enables web developers to separate the visual appearance of a website from its content, making it easier to maintain and update.

- CSS consists of a series of rules or declarations that define the style properties of HTML elements, such as font size, color, spacing, layout, and more.

- These rules can be applied to specific HTML elements or to a group of elements, and they can be defined inline in the HTML document, in an external CSS file, or within the HTML head section.

- CSS can be used to create visually appealing and responsive web pages that adapt to different screen sizes and devices.
## JavaScript
- JavaScript is a high-level, dynamic, and interpreted programming language used to create interactive and dynamic web pages.

- It allows web developers to add functionality and interactivity to HTML and CSS documents by manipulating the Document Object Model (DOM), which represents the structure of a web page.

- JavaScript is a client-side scripting language, which means it is executed by the user's web browser on their computer or mobile device.

-  JavaScript can be used to create animations, validate user input, manipulate web page content, handle events, and much more.

- It is also used in conjunction with server-side languages such as PHP and Node.js to create full-stack web applications.
## PHP

- PHP (Hypertext Preprocessor) is a server-side scripting language used to create dynamic web pages and web applications. 

- It is an open-source and widely-used language, which runs on a web server and generates HTML content that is sent to the client's web browser. 

- PHP is designed to work with databases and can be used to create complex and dynamic web applications.

- It is often used in conjunction with other technologies such as HTML, CSS, and JavaScript to create full-stack web applications. 

- PHP has many built-in functions and libraries that make it easy to perform common tasks such as file handling, database interaction, and user authentication.

- Additionally, it has a large and active community that contributes to its development and supports its users.
## SQL Database
- A SQL database is a type of relational database that uses SQL (Structured Query Language) to manage and manipulate data. 

- It is a collection of data organized into tables, with each table containing rows and columns that define the structure and attributes of the data.

- SQL databases are used to store, retrieve, and manage large volumes of structured data efficiently.

- SQL databases provide a structured and organized way to store and retrieve data, making it easy to access and analyze large amounts of data.

- SQL databases are widely used in businesses, organizations, and government agencies to manage various types of data, such as financial data, customer data, inventory data, and more
## Deployment

To run this project you must have installed a virtual server i.e XAMPP on your PC.

```bash
1st Step: Copy the main project folder
2nd Step: Paste in xampp/htdocs/
```
Connecting Database

```bash
3rd Step: Open a browser and go to URL “http://localhost/phpmyadmin/”
4th Step: Then, click on the databases tab
5th Step: Create a database naming “xyz” and then click on the import tab
6th Step: Click on browse file and select “project.sql” file which is inside the “project” folder
7th Step: Click on go
```
After Creating Database

```bash
8th Step: Open a browser and go to URL “http://localhost/Events-Management-System-master/”
```

