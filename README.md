# Greatply Project

## Setup Instructions

### Backend Setup
1. Navigate to the backend directory: `cd backend`
2. Build the project: `./mvnw clean install` 
3. Run the application: `./mvnw spring-boot:run`
4. Backend will be available at http://localhost:8080

### Frontend Setup
1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Frontend will be available at http://localhost:3000

### Environment Configuration
1. Configure OpenAI API key in `backend/src/main/resources/application.properties`

Feel free to modify the ChatGPT Prompt (`Greatply\backend\src\main\java\com\example\backend\service\GPTService.java`) to convey any kind of emotion in the responses.

Although Springboot uses an internal MVC Architecture for the framework's ease of use, the connection to Node.js is considered a straightforward Client/Server application.