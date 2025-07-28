<h1>🏋️‍♂️ FitLife – Microservices-Based Fitness App</h1>
<p>A modular full-stack fitness tracker built using Spring Boot microservices, secured with Keycloak, and enhanced with Gemini AI for smart workout recommendations.</p>
<h2>🚀 Tech Stack</h2>
<ul>
  <li><strong>Backend:</strong> Java, Spring Boot, REST APIs</li>
  <li><strong>Authentication:</strong> Keycloak (JWT, RBAC)</li>
  <li><strong>AI:</strong> Google Gemini API (for generating workouts)</li>
  <li><strong>Database:</strong> MySQL</li>
  <li><strong>Containerization:</strong> Docker, Docker Compose</li>
  <li><strong>Dev Tools:</strong> Postman, GitHub, Swagger UI</li>
</ul>
<h2>🧩 Microservices Overview</h2>
<ul>
  <li><strong>user-service</strong> – Handles user registration, authentication, and profiles</li>
  <li><strong>workout-service</strong> – Manages workout plans, categories, and logs</li>
  <li><strong>diet-service</strong> – Manages nutrition and meal plans</li>
  <li><strong>gateway-service</strong> – API gateway for routing requests and load balancing</li>
  <li><strong>discovery-service</strong> – Eureka service registry</li>
  <li><strong>config-service</strong> – Centralized Spring Cloud Config server</li>
  <li><strong>ai-service</strong> – Uses Gemini API to auto-generate workouts</li>
</ul>

<h2>🛠️ Getting Started</h2>
<ol>
  <li>Clone the repository:<br>
    <code>git clone https://dakshsahu1803/fitlife-microservices</code></li>
  <li>Start Keycloak:
    <ul>
      <li>Use Docker or standalone Keycloak setup</li>
      <li>Import the <code>realm-export.json</code> file into Keycloak</li>
    </ul>
  </li>
  <li>Start all services:<br>
    <code>docker-compose up --build</code> or run each Spring Boot app individually</li>
</ol>

<h2>🔐 Keycloak Access</h2>
<ul>
  <li><strong>Admin URL:</strong> <a href="http://localhost:8080">http://localhost:8080</a></li>
  <li><strong>Realm:</strong> fitlife-realm</li>
  <li><strong>Client:</strong> fitlife-client</li>
  <li><strong>Demo Login:</strong>
    <ul>
      <li>Username: <code>user1</code> | Password: <code>password</code></li>
    </ul>
  </li>
</ul>

<h2>✨ Features</h2>
<ul>
  <li>User authentication with Keycloak and JWT</li>
  <li>Role-based access control (admin, user)</li>
  <li>Workout plan management & activity tracking</li>
  <li>AI-generated fitness plans using Gemini API</li>
  <li>Nutrition and meal tracking</li>
  <li>Dockerized microservices for easy deployment</li>
</ul>

<h2>📁 Folder Structure</h2>
<pre>
fitlife/
├── user-service/
├── workout-service/
├── diet-service/
├── ai-service/
├── gateway-service/
├── discovery-service/
├── config-service/
├── docker-compose.yml
</pre>

<h2>👤 Author</h2>
<ul>
  <li><strong>Daksh Sahu</strong></li>
  <li><a href="https://github.com/dakshsahu1803">GitHub</a> | <a href="https://linkedin.com/in/daksh-sahu-65828324b">LinkedIn</a></li>
</ul>

<h2>📌 Status</h2>
<ul>
  <li><strong>Project:</strong> 90% Complete</li>
  <li>Frontend and CI/CD integration coming soon 🚧</li>
  <li>Integration with AI coming soon</li>
</ul>
