```bash
mvn clean install -DskipTests
```

```bash
sudo docker-compose down -v
sudo docker-compose up --build
```

```bash
cd /home/idealogic/apache-jmeter-5.6.3/bin
./jmeter
```

```sql
SELECT count(*) FROM public.users
where first_name like '1 - %'
UNION 
SELECT count(*) FROM public.users
where first_name like '2 - %';
```