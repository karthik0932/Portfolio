# Portfolio Website

A modern, interactive portfolio website built with Vue.js for showcasing professional experience and projects.

## Project Structure

```
.
├── index.html          # Main HTML file with Vue.js
├── app.js              # Vue.js application logic
├── styles.css          # Styling with animations
├── Dockerfile          # Docker configuration
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions CI/CD pipeline
└── README.md           # This file
```

## Features

- Interactive Vue.js single-page application
- Expandable project cards with detailed information
- Animated gradient background
- Fully responsive design
- Modern glassmorphism UI effects
- Smooth scrolling navigation

## Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

Then visit `http://localhost:8000`

## Docker Deployment

Build and run with Docker:

```bash
# Build the image
docker build -t portfolio-website .

# Run the container
docker run -d -p 8080:80 portfolio-website
```

Visit `http://localhost:8080`

## CI/CD Pipeline

This project includes a GitHub Actions workflow that:
- Builds the Docker image
- Runs tests
- Deploys to your hosting platform

## Technologies Used

- Vue.js 3
- HTML5
- CSS3 (with animations and gradients)
- Font Awesome icons
- Docker
- GitHub Actions
- Nginx (for Docker deployment)

## Customization

1. Update content in `app.js` to modify:
   - Skills
   - Work experience
   - Projects
   - Contact information

2. Modify colors and styles in `styles.css`

## License

MIT License - Feel free to use this for your own portfolio!
