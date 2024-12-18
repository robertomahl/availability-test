```bash
docker-compose down -v
```

```bash
docker-compose up -d postgres_primary postgres_replica
```

```bash
mvn clean install -DskipTests
```

```bash
docker-compose down
docker-compose up --build
```
