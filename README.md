# cs465-fullstack
CS-465 Full Stack Development with Mean
Here's the updated description with MongoDB and RESTful API included:

### Tech Stack:
- **Frontend**: 
  - **Angular** (CLI v6.2.9): The project uses Angular for the front-end development. Angular provides a structured and scalable framework for creating Single Page Applications (SPAs). 
  - **Development tools**: Features include a development server (`ng serve`) for local development, the ability to scaffold new components, services, and other Angular artifacts, and tools for running unit tests (via Karma) and end-to-end tests (via Protractor).
  
- **Backend**:
  - **Node.js/Express**: The backend is built using Express, a minimal and flexible Node.js web application framework. It handles HTTP requests and sets up the server (port 3000 by default). The backend routes are handled by different controllers, which are logically grouped in directories such as `controllers`, `routes`, and `views`.
  - **HTTP Server**: The backend utilizes `http` from Node.js to create the server and handle server-level errors and events (such as 'listening' and 'error').
  - **MongoDB**: The project uses MongoDB as the database to store and manage travel-related data.

- **Database**:
  - **MongoDB**: The app uses MongoDB, a NoSQL database, for storing travel package details like resort names, prices, and descriptions.

### Features:
- **Single Page Application (SPA)**: The project is built as an SPA with Angular, allowing the application to load a single HTML page and dynamically update content without refreshing the page. This enhances performance and user experience.
  
- **Authentication and Security**: The project has implemented security features, likely involving login functionality and user authentication. Based on the folder structure and commit messages, the app has a functional login page.
  
- **RESTful API**: The project utilizes RESTful APIs for handling data exchanges between the front-end and back-end. The APIs are used to manage and retrieve travel-related data.
  
- **Travel-related Information Management**: Based on the folder content, the project handles travel-related data (for instance, details about various travel packages like "Gale's Reef" and "Dawson's Reef") with fields such as trip codes, resort names, duration, prices,
