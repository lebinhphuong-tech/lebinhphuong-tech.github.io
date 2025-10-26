# Personal Webpage 

My personal Webpage/Resume/CV in [Bootstrap](http://getbootstrap.com/) using the [iPortfolio template](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) created by [Bootstrap Made](https://bootstrapmade.com//). 

## Hosted with love on GitHub
[Here](https://fabriziomiano.github.io/)

## Running Locally with Docker

### Prerequisites
- Docker and Docker Compose installed on your machine

### Quick Start

1. Start the portfolio website:
   ```bash
   docker-compose up -d
   ```

2. Open your browser and navigate to:
   - Main portfolio: `http://localhost:8080`
   - Documents page: `http://localhost:8080/docs`

3. To stop the container:
   ```bash
   docker-compose down
   ```

### Commands

- **Start in background**: `docker-compose up -d`
- **View logs**: `docker-compose logs -f portfolio`
- **Stop container**: `docker-compose down`
- **Restart container**: `docker-compose restart`

### Customization

The container serves all files from the root directory. Any changes you make to HTML, CSS, or JS files will be reflected automatically (you may need to hard refresh your browser: Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows/Linux).
