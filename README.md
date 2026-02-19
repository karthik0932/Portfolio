# Portfolio Website - DevOps Practice Project

A simple portfolio website built for practicing DevOps, CI/CD, and Git workflows.

## Project Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Styling
├── Dockerfile          # Docker configuration
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions CI/CD pipeline
└── README.md           # This file
```

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
- Runs tests (if any)
- Deploys to your hosting platform

## Customization

1. Update content in `index.html` with your actual information
2. Modify colors and styles in `styles.css`
3. Add your projects and experience
4. Update contact links

## DevOps Learning Checklist

- [ ] Initialize Git repository
- [ ] Create GitHub repository
- [ ] Set up Docker containerization
- [ ] Configure GitHub Actions CI/CD
- [ ] Deploy to cloud platform (AWS, Azure, etc.)
- [ ] Set up monitoring and logging
- [ ] Implement infrastructure as code (Terraform)
- [ ] Add automated testing
- [ ] Configure domain and SSL

## Technologies Used

- HTML5
- CSS3
- Docker
- GitHub Actions
- Nginx (for Docker deployment)

## License

MIT License - Feel free to use this for your own learning!
