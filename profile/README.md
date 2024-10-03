## Hi there 👋
This is a Developer Akademie Group Work 
For the Videoflix App Portfolio Example 🍿🍿🍿

<h1>🎬 Videoflix 🍿</h1>

<p>Welcome to <strong>Videoflix</strong>, a Netflix-inspired video streaming platform! This project is developed by <strong>Lukas, Alex, and Benjamin</strong> as part of our intensive full-stack developer training. We're using <strong>Angular 18</strong> for the frontend and <strong>Django & Django Rest Framework</strong> for the backend, with a <strong>PostgreSQL database</strong>. The platform enables users to register, explore a video library, and stream videos with various quality options.</p>

<hr>

<h2>🚀 Project Overview</h2>

<p>Videoflix aims to recreate the core features of popular streaming services with a focus on clean code, responsive design, and scalable architecture. Our goal is to deliver an intuitive and efficient user experience for managing and watching video content.</p>

<h2>🔧 Tech Stack</h2>
<ul>
    <li><strong>Frontend:</strong> Angular 18</li>
    <li><strong>Backend:</strong> Django & Django Rest Framework</li>
    <li><strong>Database:</strong> PostgreSQL</li>
    <li><strong>Caching Layer:</strong> Redis</li>
    <li><strong>Background Task Runner:</strong> Django RQ or Celery</li>
</ul>

<h2>📋 Checklist - Definition of Done (DoD)</h2>
<ul>
    <li>Ensure Clean Code principles are followed</li>
    <li>Functions are no longer than 14 lines</li>
    <li>Each function performs one clear task</li>
    <li>All function and variable names follow the snake_case convention</li>
    <li>No unused variables or functions</li>
    <li>All commented-out code has been removed</li>
</ul>

<h3>📑 Documentation</h3>
<ul>
    <li>Documentation is present</li>
    <li>A clear and concise README.md file exists</li>
</ul>

<h3>🛠️ Django-Specific Requirements</h3>
<ul>
    <li>Views that return HTTP responses are in <code>views.py</code></li>
    <li>Helper functions are located in <code>functions.py</code> or <code>utils.py</code></li>
    <li>Unit tests are written, and there is at least 70% test coverage (use <strong>Django Nose</strong>)</li>
    <li>Code is PEP-8 compliant</li>
</ul>

<h3>🖥️ Technical Requirements</h3>
<ul>
    <li>Backend and frontend are separated, communicating via a REST API</li>
    <li>PostgreSQL is used as the database</li>
    <li>Redis is set up as the caching layer</li>
    <li>Host the backend on a V-Server</li>
    <li>Ensure at least 80% test coverage for the backend</li>
    <li>The user interface is responsive across all screen sizes</li>
</ul>

<h2>📜 Functional Requirements</h2>

<h3>1. User Registration</h3>
<ul>
    <li>Users can register with an email and password</li>
    <li>A confirmation email is sent after registration</li>
    <li>Accounts must be activated before login</li>
    <li>General error messages are displayed for invalid input</li>
</ul>

<h3>2. User Login & Logout</h3>
<ul>
    <li>Registered users can log in with their email and password</li>
    <li>Error messages are kept general to maintain security</li>
    <li>Users can reset their password via a "Forgot Password" option</li>
    <li>Users can log out securely</li>
</ul>

<h3>3. Video Dashboard</h3>
<ul>
    <li>A dashboard displays a hero section with a featured video teaser</li>
    <li>Videos are grouped by genre</li>
    <li>Each video is displayed with a thumbnail and title</li>
</ul>

<h3>4. Video Playback</h3>
<ul>
    <li>Video quality is automatically adjusted based on device and connection</li>
    <li>Users can manually choose resolutions (120p, 360p, 720p, 1080p)</li>
    <li>Basic controls: play, pause, forward, rewind, and full-screen</li>
</ul>

<h3>5. Progress Tracking</h3>
<ul>
    <li>Playback progress is automatically saved</li>
    <li>Users are prompted to continue where they left off for partially watched videos</li>
</ul>

<h3>6. Legal Information</h3>
<ul>
    <li>There are easily accessible links to the privacy policy and imprint in the footer</li>
</ul>

<h2>⚡ Other Features</h2>
<ul>
    <li>Background tasks are handled with <strong>Django RQ</strong> or <strong>Celery</strong></li>
    <li>We use Redis as a caching layer for faster performance</li>
</ul>

<h2>💻 Developer Instructions</h2>
<p>Follow the steps below to set up the project:</p>

<ol>
    <li>Clone the repository: <code>git clone https://github.com/videoflix/videoflix-app.git</code></li>
    <li>Navigate to the backend directory: <code>cd backend</code></li>
    <li>Create a virtual environment and install dependencies: <code>pip install -r requirements.txt</code></li>
    <li>Run database migrations: <code>python manage.py migrate</code></li>
    <li>Start the backend server: <code>python manage.py runserver</code></li>
    <li>Navigate to the frontend directory: <code>cd ../frontend</code></li>
    <li>Install frontend dependencies: <code>npm install</code></li>
    <li>Start the Angular frontend: <code>ng serve</code></li>
</ol>

<h2>🧪 Testing</h2>
<ul>
    <li>We have implemented unit tests for the backend, with at least 70% coverage.</li>
    <li>To run tests, execute: <code>python manage.py test</code></li>
</ul>


<h2>🎉 Fun Facts</h2>
<p>The VideoFlix crew loves 🍕 pizza and 🍔 burgers! We always brainstorm the best ideas over a good meal!</p>

🧙 VideoFlix-Crew Developed by Lukas, Alex and Benjamin ;)

