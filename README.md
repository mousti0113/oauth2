# Spring OAuth2 Demo

Demo project showcasing OAuth2 integration with Google and GitHub using Spring Boot.

## Features

- 🔐 OAuth2 login with Google
- 🔐 OAuth2 login with GitHub  
- 🌐 Simple REST endpoint with authentication
- ⚡ Spring Boot 3.5.0
- ☕ Java 21

## Setup

1. Create a `.env` file in the root directory:
```env
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
GITHUB_CLIENT_ID=your-github-client-id
GITHUB_CLIENT_SECRET=your-github-client-secret
```

2. Run the application:
```bash
./mvnw spring-boot:run
```

3. Open http://localhost:8080 and login with Google or GitHub

## Endpoints

- `/` - Protected endpoint that returns a greeting message
- `/login` - OAuth2 login page (auto-redirected)

## Technologies

- Spring Boot 3.5.0
- Spring Security OAuth2 Client
- Maven
- Java 21