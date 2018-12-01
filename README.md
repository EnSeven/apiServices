#APIServices

## Overview
Welcome to the apiServices wiki!
This API is used as the route/method to signup / sign-in to the EnSeven game app. Our apiServer will serve as the gatekeeper for authorization and authentication to our games. Manages database for the overall application. Which includes the data store for our users, including their gaming history. We have started out using a Node Express server with a Mongo backend. We are working on using an Access Control List (ACL) to control access to the various routes, based on roles and role privileges.

##USER
As a user I would like the following:
   * A secure way to signup / signin.
   * An app that' will store my wins / losses
   * I want to be able to view my own stats.
##Developer
As a developer I would like an API that did the following:
   * Secures the signin / signup
   * An API that sends a token that the app will use throughout the users game to securely transfer their information( user name, wins, loses, opponents, other relevant data that we foresee in the future) 
   * An API that sends and receives information to and from Client and Game servers.
   * An API that will support multiple users at the same time and able to store their data. 
   * Have unit tests which assures the developers that everything is working correctly.
   * The ability to manage player stats.

