# parent layer: base
FROM node:17-alpine
# install nodemon globally
RUN npm install -g nodemon
# the working directory is the root of the project
WORKDIR /app
# copy the app.js file from the build directory to the container
COPY . .
# intall dependencies
RUN npm install
# the port to expose on the host
EXPOSE 4000
# run the app
CMD [ "npm", "run", "dev"]
