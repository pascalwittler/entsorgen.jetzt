# entsorgen.jetzt

A random trash fun project

## Setup

### With Docker

1. Build the container

```bash
docker build -t entsorgen-jetzt:latest .
```

2. Run the container

```bash
docker run -p 3000:80 entsorgen-jetzt                                         # production
docker run -p 3000:80 -v ./public:/usr/local/apache2/htdocs entsorgen-jetzt   # development
```
