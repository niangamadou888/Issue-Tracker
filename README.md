
# Issue Tracker

The MongoDB-Based Issue Tracking API is a backend service that facilitates the management of issues related to specific projects. This API is designed to handle CRUD (Create, Read, Update, Delete) operations for issues in a MongoDB database. It allows users to interact with the system by making HTTP requests to various endpoints. The primary purpose of the project is to provide a flexible and efficient means of tracking and managing issues for different projects.
## Features
- Retrieve Issues: Users can query the API to retrieve a list of issues associated with a particular project. Customized queries can be made using query parameters to filter issues based on criteria like open status, creation date, and other attributes.

- Add New Issues: Users can submit new issues to the system, specifying details such as the issue title, issue text, and the creator's name. Optional fields include assignment, status information, and the option to set the issue as open or closed.

- Update Existing Issues: Existing issues can be modified by providing the unique '_id' of the issue. The API validates the '_id' and updates the relevant fields, including the 'open' status and other optional attributes. The 'updated_on' field is automatically updated to reflect the modification time.

- Delete Issues: Users can remove issues from the system by specifying the issue's '_id'. The API verifies the validity of the '_id' before performing the deletion, responding with success or failure.
## Technologies Used

- Javascript

- Node.js

- MongoDB
## App Demo

https://boilerplate-project-issuetracker.niangamadou888.repl.co/
