FROM node:10
COPY . .
RUN CI=true
# Installs all node packages
RUN npm install
# Finally runs the application
CMD [ "node", "index.js" ]
