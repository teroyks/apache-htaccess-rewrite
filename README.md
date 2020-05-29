# htaccess Redirection Test

## Running the server

### Build the image

```shell script
docker build -t apache-rewrite .
```

### Start the Server

```shell script
docker run --rm -d -p 80:80 --name htaccess -v "$PWD":/var/www/html apache-rewrite
```

