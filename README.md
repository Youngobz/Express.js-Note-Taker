# Note Taker Application

The Note Taker application provides a simple and intuitive interface for users to create, save, and manage notes. Here's a more detailed explanation of its functionality:


https://github.com/Youngobz/Express.js-Note-Taker/assets/133522178/f41e059e-11fc-4d20-b7e9-4913b98344b1




## Home Page:

When you first open the application by navigating to http://localhost:<PORT>, you are greeted with a home page. This page introduces you to the Note Taker application and encourages you to get started.

## Note Taker Interface (/notes):

Clicking the "Get Started" button on the home page or directly accessing /notes takes you to the main note-taking interface. Here's what you can do on this page:

<li> View Saved Notes: On the left side of the interface, you'll find a list of saved notes. Clicking on a note title in this list will display the contents of the selected note on the right side of the interface.

<li>Create New Notes: To create a new note, you can click the "+" icon at the top-right corner of the interface. This will clear the current note content (if any) and allow you to enter a new note title and text in the respective input fields.

<li>Edit Notes: When you click on a saved note's title in the list, the note's title and text will be displayed in the input fields. You can edit the title and text as needed.

<li>Save Notes: To save a new note or update an existing note, click the floppy disk ("Save") icon. This will save the note to the list on the left.

<li>Delete Notes: Each saved note has a trash can icon next to its title. Clicking this icon will delete the corresponding note from the list.

## API Routes:

Behind the scenes, the application utilizes API routes to handle data storage and retrieval. Here's how the API routes work:

<li>GET /api/notes: Retrieves a list of all saved notes from the database.
<li>POST /api/notes: Receives data from the client to create a new note and save it to the database.
<li>DELETE /api/notes/:id: Deletes a note with the specified unique ID from the database.

## Data Storage (db.json):

Notes are stored in a JSON file named db.json. This file acts as a simple database, keeping track of each note's title, text, and a unique ID.

The Note Taker application is a convenient tool for users who want to jot down and organize their thoughts, ideas, and reminders. Whether you're a student, professional, or anyone who needs a digital notepad, this application provides a user-friendly interface for managing your notes efficiently.

## Installation

Clone the repository to your local machine:

<li>git clone <repository-url>

### Navigate to the project directory:

<li>cd <project-directory>

### Install the required dependencies:

<li>npm install

### Usage

Start the application:

<li>npm start
<li>Open your web browser and navigate to http://localhost:<PORT>, where <PORT> is the port number specified in your .env file.

_Click the "Get Started" button to access the Note Taker interface. Feel free to explore, use, and contribute to this Note Taker application. Happy note-taking! 📝_
