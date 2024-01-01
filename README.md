This project is a Task Board Management System developed using Node.js, Express.js, React, and PostgreSQL.
It allows users to manage tasks by organizing them into multiple lists, enabling drag-and-drop functionality for easy task management.
Features:
* User Authentication:
    Users can register and log in securely using their credentials stored in the PostgreSQL database.
* List Management:
    Users have the ability to create multiple lists, and these lists are stored and managed in the database using Sequelize ORM.
* Task Management:
    Tasks can be created, edited, and moved between different lists using drag-and-drop functionality.
    The database is updated in real-time when tasks are moved to different lists, ensuring data integrity.
*Horizontal Scrolling:
     Multiple lists are displayed horizontally, allowing users to navigate through their lists conveniently.

 <-- Technologies Used: -->
Back-End:
  Node.js and Express.js for server-side development.
  PostgreSQL database managed with Sequelize ORM for data storage.
Front-End:
  React for building the user interface.
  HTML5 Drag-and-Drop API or libraries like react-dnd for drag-and-drop functionality.


 <-- HOW TO GET STARTED WITH THE PROJECT -->
To run this project locally:

Clone this repository.
Install dependencies using npm install.
Set up PostgreSQL and configure the database settings in the backend.
Run the backend server using npm start in the /backend directory.
Run the frontend using npm start in the /frontend directory.
Feel free to explore and contribute to this project by following the guidelines in the CONTRIBUTING.md file.
