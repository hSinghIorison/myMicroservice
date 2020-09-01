# Create Docker image

```
docker build -t mymicroservice .
```

## Run Docker image

```
docker run -it --rm -p 3000:80 --name mymicroservicecontainer mymicroservice
```

You can browse to the following URL to access your application running in a container: http://localhost:3000/WeatherForecast
