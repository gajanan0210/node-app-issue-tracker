# node-app-issue-tracker
The Issue Tracker App is a Node.js and EJS-based application.

# Issue Tracker App
This is a Node.js and EJS application for tracking issues/bugs for a project. It allows users to create projects, add issues to projects, and perform various actions like filtering, searching, and creating issues.

## Features
    Neat and intuitive user interface
    Home Page:
        Displays a list of projects
        Provides a button to create a new project (newly created projects appear in the list)
    Create Project Page:
     Accepts the following fields to create a project:
        Name
        Description
        Author
    Project Detail Page:
        Redirects the user from the home page when clicking on a project
        Displays bugs related to the selected project
        User can perform the following actions on this page:
            Filter by multiple labels
            Filter by author
            Search by title and description
            Create a new issue
    Create Issue Page:
        User can create an issue for a project
        Accepts the following fields:
            Title
            Description
            Author
## Installation
-Clone the repository:

git clone <repository-url>

-Navigate to the project directory:

cd issue-tracker-app

-Install the dependencies:

npm install

-Start the application:

npm start

Open your web browser and visit http://localhost:8000 to access the application.

### Dependencies
The app uses the following dependencies:

Express: Fast, unopinionated, minimalist web framework for Node.js
EJS: Embedded JavaScript templates
Other dependencies can be found in the package.json file
Contributing
Contributions are welcome! If you find any issues or want to enhance the application, feel free to open a pull request.


