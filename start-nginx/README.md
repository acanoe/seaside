# Start - nginx

## Intro

Simple docker project to run nginx server hosting an HTML file.

## How to run

1. build the image
   ```bash
   docker build -t start-nginx .
   ```
2. run it!
   ```bash
   docker run --name start-nginx-1 -p 8080:80 -d start-nginx
   ```
3. click [this link](http://localhost:8080) or go to http://localhost:8080 to see the page
