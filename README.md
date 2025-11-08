# QuizBuilder Application

A full-stack quiz application built with React and Spring Boot.

## Features

- User authentication
- Quiz creation and management
- Real-time quiz taking
- Score tracking
- Responsive design

## Tech Stack

- **Frontend**: React, Vite, TailwindCSS
- **Backend**: Spring Boot, Java 17
- **Database**: MySQL 8.0
- **Containerization**: Docker, Docker Compose

## Getting Started

### Prerequisites

- Docker and Docker Compose
- Java 17+
- Node.js 18+
- MySQL 8.0+

### Local Development

1. Clone the repository
2. Set up environment variables (copy `.env.example` to `.env`)
3. Start the application:
   ```bash
   docker-compose up --build
   ```

### API Documentation

API documentation is available at `http://localhost:9096/swagger-ui.html` when the backend is running.

## Deployment

### Production Build

```bash
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up --build -d
```

### Environment Variables

See `.env.example` for required environment variables.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
