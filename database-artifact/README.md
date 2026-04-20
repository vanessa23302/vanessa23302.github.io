# Database Artifact

## Overview

This artifact comes from the Travlr Getaways web application originally developed in CS 465: Full Stack Development. The application is a travel booking system built using Node.js, Express, and MongoDB. It allows users to view information about travel destinations and trip packages through an API that retrieves data from a MongoDB database.

The artifact demonstrates how backend services interact with a database to retrieve structured data that can be consumed by client applications.

---

## Original Code

The original version of the code retrieved trip data from the MongoDB database using the Mongoose model. While this implementation successfully returned trip records, it was limited because it always returned the full list of trips without allowing users to filter or sort the results.

The original code is included in the **original-code** folder.

---

## Enhanced Code

The enhanced version improves the API functionality by adding additional logic to the trips controller. The improvements include:

- Filtering trips by minimum and maximum price
- Sorting trip results by price
- Improving the structure and readability of the controller code

These changes make the API more flexible and realistic for a production environment because it allows users to retrieve specific subsets of data rather than always returning the entire database collection.

The enhanced implementation can be found in the **enhanced-code** folder.

---

## Skills Demonstrated

This artifact demonstrates several important computer science and software development skills, including:

- Backend development using Node.js and Express
- Database interaction using MongoDB and Mongoose
- API design and implementation
- Data filtering and sorting
- Writing maintainable and readable backend code

These improvements demonstrate how backend services can efficiently manage and deliver structured data in a modern web application.

---

## Narrative

The narrative document explains the purpose of the artifact, the enhancements that were made, and the skills demonstrated during the development process.

[View the Database Artifact Narrative](narrative/database-artifact-narrative.docx)
