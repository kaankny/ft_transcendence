<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ft_transcendence README</title>
</head>
<body>

<h1>ft_transcendence</h1>

<p><strong>ft_transcendence</strong> is a real-time multiplayer Pong game with advanced features such as secure user management, live chat, and customization options. Built with modern web technologies, this project is part of the Ecole 42 curriculum and offers a flexible, engaging gaming experience.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#tech-stack">Tech Stack</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#modules-implemented">Modules Implemented</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="overview">Overview</h2>
<p>This project allows users to compete in a multiplayer Pong game, either locally or remotely. The game supports user authentication, live chat, and customizable gameplay options. The project was developed using a framework-based backend and frontend technologies, including multiple security and accessibility features.</p>

<h2 id="features">Features</h2>
<ul>
    <li>Real-time multiplayer Pong game with <strong>remote players</strong> support</li>
    <li>Secure <strong>user management</strong> with authentication and OAuth 2.0</li>
    <li><strong>Two-factor authentication (2FA)</strong> using JWT</li>
    <li><strong>Live chat</strong> with direct messaging, blocking, and game invitations</li>
    <li><strong>Game customization options</strong> for enhanced user experience</li>
    <li><strong>User dashboards</strong> displaying game statistics</li>
    <li>Multiple language support</li>
    <li>Advanced 3D graphics using ThreeJS</li>
</ul>

<h2 id="tech-stack">Tech Stack</h2>
<ul>
    <li><strong>Backend:</strong> Django</li>
    <li><strong>Frontend:</strong> React, Bootstrap</li>
    <li><strong>Database:</strong> PostgreSQL</li>
    <li><strong>Authentication:</strong> OAuth 2.0, JWT, 2FA</li>
    <li><strong>3D Graphics:</strong> ThreeJS</li>
    <li><strong>Containerization:</strong> Docker</li>
</ul>

<h2 id="installation">Installation</h2>
<p>To install and run the project locally, follow these steps:</p>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/kaankny/ft_transcendence.git
cd ft_transcendence</code></pre>
    </li>
    <li>Set up the backend:
        <pre><code>cd backend
pip install -r requirements.txt
python manage.py migrate</code></pre>
    </li>
    <li>Set up the frontend:
        <pre><code>cd frontend
npm install
npm start</code></pre>
    </li>
    <li>Run with Docker:
        <pre><code>docker-compose up --build</code></pre>
    </li>
    <li>Visit <code>http://localhost:3000</code> to access the game.</li>
</ol>

<h2 id="usage">Usage</h2>
<p>After installation, users can register, log in, and start playing Pong with others in real-time. The platform supports remote multiplayer matches, live chat, and game customization options. Players can also track their statistics through user dashboards.</p>

<h2 id="modules-implemented">Modules Implemented</h2>

<h3>Major Modules</h3>

<ul>
    <li><strong>Framework as Backend</strong>: The backend is powered by Django, providing a robust and scalable structure.</li>
    <li><strong>Standard User Management</strong>: Includes secure user registration, login, profile updates, and the ability to manage user information, friends, and game history.</li>
    <li><strong>Remote Authentication</strong>: Integrated OAuth 2.0 for secure, remote user authentication, including authentication via 42 API.</li>
    <li><strong>Remote Players</strong>: Allows two users in different locations to play against each other in real-time.</li>
    <li><strong>Live Chat</strong>: Provides real-time communication between users, along with the ability to block users and send game invitations through chat.</li>
    <li><strong>Two-Factor Authentication (2FA) and JWT</strong>: For enhanced security, 2FA has been implemented along with JSON Web Tokens for session management and authorization.</li>
    <li><strong>Advanced 3D Graphics</strong>: Leveraging ThreeJS to create immersive 3D graphics for the Pong game, enhancing visual gameplay quality.</li>
</ul>

<h3>Minor Modules</h3>

<ul>
    <li><strong>Frontend Framework</strong>: Bootstrap is used for developing a responsive, single-page application frontend.</li>
    <li><strong>Database Integration</strong>: PostgreSQL is used for managing game and user data, ensuring consistent and secure storage.</li>
    <li><strong>Game Customization Options</strong>: Allows players to customize their game experience with different settings, such as power-ups and maps.</li>
    <li><strong>User and Game Stats Dashboards</strong>: Displays user performance and game statistics using easy-to-navigate dashboards.</li>
    <li><strong>Multiple Language Support</strong>: Supports multiple languages to provide an inclusive user experience.</li>
</ul>

</body>
</html>
