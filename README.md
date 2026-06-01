# holbertonschool-softy-pinko-docker

## Run task6 (full stack)

From the repository root, build and start the Task 6 stack (front-end, back-end, proxy):

```bash
cd task6
docker compose up --build -d
# or with the legacy CLI:
docker-compose up --build -d
```

- The proxy publishes port 80 on the host. Open `http://localhost/` to view the front-end.
- The API is available at `http://localhost/api/hello` (proxied to the back-end).

To stop and remove containers:

```bash
docker compose down
```
