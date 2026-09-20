# Microservices Docker Containerization

This project containerizes four Node.js microservices using Docker and Docker Compose.

## Services

| Service         | Port |
| --------------- | ---: |
| User Service    | 3000 |
| Product Service | 3001 |
| Order Service   | 3002 |
| Gateway Service | 3003 |

## Run

```bash
docker compose build
docker compose up -d
```

## Test

```text
http://localhost:3000/health
http://localhost:3001/health
http://localhost:3002/health
http://localhost:3003/health
```

## Snapshot

### Docker Containers

![Docker Containers](./snapshot/Screenshot%202026-09-20%20193743.png)
![Docker Containers](./snapshot/Screenshot%202026-09-20%20193805.png)
![Docker Containers](./snapshot/Screenshot%202026-09-20%20194147.png)

![Docker Containers](./snapshot/Screenshot%202026-09-20%20194318.png)
