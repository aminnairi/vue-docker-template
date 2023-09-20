# vue-docker-template

Template for running Vue inside of a container.

## Requirements

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Environment Configuration

```bash
cp .env.example .env
```

Please, take some time reviewing the configuration of the project by editing the `.env` file before going any further.

## Docker Compose Services Startup

```bash
docker-compose up --detach
```

## Production Build

```bash
docker-compose exec node npm run build
```

## Docker Compose Services Shutdown

```bash
docker-compose down --remove-orphans --volumes --timeout 0
```

## Documentation

- [Vite.js](https://vitejs.dev/guide/)
- [Vue.js](https://vuejs.org/guide/introduction.html)
- [Docker](https://docs.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/compose-file/)
