docker rm -f fabric; docker run --name fabric -p 5432:5432 -e POSTGRES_PASSWORD=fabric -d postgres