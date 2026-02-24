Scalable Auth & Task Management APIA production-ready Backend Intern assignment featuring a secure RESTful API with JWT Authentication, Role-Based Access Control (RBAC), and a responsive React frontend. FeaturesJWT Authentication: Secure login and registration with password hashing (Bcrypt).RBAC (Role-Based Access Control): Tiered access for admin and user roles.RESTful CRUD: Complete Task Management entity with validation.Security: Middleware for token verification, error handling, and CORS.Scalability: Modular directory structure and API versioning (/api/v1). Tech StackBackend: Node.js, Express.jsAuth: JSON Web Tokens (JWT), Bcrypt.jsFrontend: React.js, Tailwind CSS, Lucide IconsDocumentation: Postman Collection included in repo. Project Structure├── src/
│   ├── middleware/        # Auth and Validation middleware
│   ├── routes/            # API Route definitions
│   ├── controllers/       # Business logic
│   └── models/            # Database schemas
├── public/                # Frontend assets
├── .env                   # Environment variables
└── server.js              # Entry point
 Getting Started1. Backend Setup# Clone the repository


# Install dependencies
npm install

# Start the server
node server.js
2. Frontend SetupThe frontend is built with React. Ensure you have a dev server running or open the App.jsx in your preferred environment. API EndpointsMethodEndpointDescriptionAccessPOST/api/v1/auth/registerRegister new userPublicPOST/api/v1/auth/loginLogin & get TokenPublicGET/api/v1/tasksGet all tasksAuth (RBAC)POST/api/v1/tasksCreate a taskAuthDELETE/api/v1/tasks/:idRemove a taskOwner/AdminCreated for the Backend Developer Intern Assignment.