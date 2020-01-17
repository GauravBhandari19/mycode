# Minimum NPM-Express Application on Docker

1. Build the App

```
sudo docker build -t express:0.1 .
```

1. Start the Container

```
sudo docker run -t -i -p 3000:3000 --name express express
```