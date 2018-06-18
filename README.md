# Spark in Docker with python3.5.3

# docker build
> docker build -t spark:python3.5.3 .
# docker run
> docker run -it -p 4040:4040 -p 8080:8080 -p 8081:8081 -h spark --name=spark spark:python3.5.3
