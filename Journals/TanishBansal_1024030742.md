# Weekly Work Journal

## Week 1: Project Planning and Documentation

### Work Done
- Finalized the idea for the **Tourism Guide Planner** project.
- Defined the main purpose of the project: helping foreign tourists explore historical places and learn about their history.
- Planned the main features of the website, including historical place information, guide booking, and an AI chatbot.
- Created the project proposal.
- Prepared the project proposal in `.tex` and `.pdf` formats.
- Created the GitHub repository for the project.
- Added a README file containing the project description, features, technology stack, project workflow, and future scalability.

### Outcome
- Developed a clear understanding of the project requirements and workflow.
- Completed the main project documentation.
- Set up and organized the GitHub repository for further development.


## Week 2: Backend Setup and Database Connection

### Work Done
- Started the backend development of the Tourism Guide Planner project.
- Created and initialized the Node.js backend project.
- Added the required dependencies, including Express, Mongoose, dotenv, bcrypt, JWT, CORS, and cookie-parser.
- Created the basic backend folder structure.
- Created the `User` model using MongoDB and Mongoose.
- Added fields for user information such as name, email, password, role, country, and languages.
- Added guide-related information to support tourist and guide roles.
- Set up MongoDB Atlas for the project database.
- Created the database connection configuration.
- Created and configured the main `app.js` file.
- Connected the Express application with MongoDB.

### Outcome
- Successfully set up the backend development environment.
- Created the main User model for tourists and guides.
- Connected the backend application with the MongoDB database.
- Improved understanding of how Express, MongoDB, and Mongoose work together.


## Week 3: Database Models and Backend Structure

### Work Done
- Created the `HistoricalPlace` model.
- Added fields such as place name, description, history, location, images, architecture, cultural importance, important events, and interesting facts.
- Created the `Booking` model to manage guide bookings.
- Connected tourists, guides, and historical places using MongoDB references.
- Added booking details such as date, time, message, and booking status.
- Created the `Review` model.
- Added fields for tourist, guide, booking, rating, and comments.
- Completed the main database models required for the core functionality of the project.
- Started organizing the backend route structure.
- Planned separate routes for authentication, historical places, guides, bookings, and reviews.
- Studied the use of routers and middleware for handling API requests.


## Week 4: API Development and Backend Integration

### Work Done
- Continued the backend development of the Tourism Guide Planner project.
- Created the authentication middleware to protect APIs that require users to be logged in.
- Connected the authentication middleware with protected routes.
- Completed the authentication APIs for signup, login, and logout.
- Created the Historical Places router for adding, viewing, updating, and deleting historical places.
- Created the Guide router for viewing and searching available guides.
- Created the Booking router for booking guides and managing booking requests.
- Added booking status functionality such as pending, accepted, rejected, cancelled, and completed.
- Created the Review router for adding and viewing reviews and ratings for guides.
- Connected the different routers with the main `app.js` file.
- Used MongoDB and Mongoose to store and retrieve project data.
- Started testing the backend APIs and checking the request and response flow.

### Outcome
- Completed the main backend routers of the Tourism Guide Planner project.
- Added authentication and protected important APIs using middleware.
- Created the main API flow for historical places, guides, bookings, and reviews.
- Improved understanding of how routers, middleware, models, and MongoDB work together.
- Prepared the backend for API testing and future frontend integration.

### Outcome
- Completed the main database models for the project.
- Created the basic backend structure for further API development.
- Improved understanding of MongoDB relationships, API routes, and backend application flow.
- Prepared the project for the next stage, which is developing and testing the APIs.
