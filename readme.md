# NextJS Express Typescript Boilerplate

## Development
To run in development run the following command(s)

```
npm install 
npm run dev 
```

the server will start running on port 3000. you can access it by going to http://localhost:3000


## Production

This boilerplate has Docker setup. So make sure docker is installed. If installed, ou can just follow the below command(s) to get build and run the image

```
docker build . -t  <username>/<image-name>
docker run -p 3000:3000 -d <username>/<image-name>
```

The image will expose port 3000. you can access it by going to http://localhost:3000


## Tech Stacks

* NextJS
* ExpressJS
* Docker