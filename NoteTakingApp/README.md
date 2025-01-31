
Movie Ratings & Reviews App
This is a Note Taking App built with HTML, CSS, and Node.js.

File Structure
NoteTakingApp/
│
├── config/
│   └── db.js
├── controllers/
│   └── notesController.js
├── docs/
│   ├── API_Documentation.md
│   └── README.md
├── errorTesting/
│   ├── index.ejs
│   ├── movie-detail.ejs
│   └── submit-review.ejs
├── models/
│   └── Note.js
├── public/
│   ├── css/
│   │   ├── header.css
│   │   ├── new-note.css
│   │   ├── note-editor.css
│   │   ├── notes.css
│   │   ├── profile.css
│   │   └── styles.css  
│   ├── img/
│   │   └── owl-note-taking.png
│   └── js/
│   │   ├── dark-mode.js
│   │   ├── new-note.js
│   │   └── note-editor.js
│   └── scrollApp.png
├── routes/
│   └── routes.js
├── views/
│   ├── partials/
│   │   ├── header.ejs
│   │   └── footer.ejs 
│   ├── index.ejs
│   ├── new-note.ejs
│   ├── note-editor.ejs
│   ├── notes.ejs
│   └── profile.ejs 
├── .env
├── app.js
├── package.json
└── package-lock.json

How to Run the App

1.Clone the repository:
git clone https;//github.com/FabioKallina/NoteTakingApp.git
cd project-root

2.Install the dependencies:
npm install

3.Run the application:
nodemon app.js

4.Open your web browser and go to:
http://localhost:3000
