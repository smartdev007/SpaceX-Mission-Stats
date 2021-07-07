# SpaceX Mission Launch Stats

> React, GraphQL, Apollo app that uses the SpaceX API to display mission details like launches and rocket details

## Installation and Running Instructions

```
# Install dependencies (server & client)
npm install
cd client && npm install

# Run server & client (:3000 & :5000)
npm run dev

# Server only (:5000)
npm run server

# Client only (:3000)
npm run client

# Build for production (Builds into server ./public)
cd client && npm run build

# Graphiql - http://localhost:5000/graphql
```

## App Info

### Functionalities

- Get all mission names
- Find out if the mission was successful or not
- Check mission launch date
- Find out rocket name and type that was used for a particular mission

### Live website

https://spacex-launch-stat.herokuapp.com/