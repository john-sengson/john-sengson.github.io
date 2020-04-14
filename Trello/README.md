# Lightning Talks

Yay! Lightning talks!

This is your chance to learn a new topic and share it with others. This is great practice for your future talks at meetups and local conferences. This is also a good chance to practice giving and receiving actionable, specific, and kind feedback.

Based on the week you're in, select the appropriate file in this repo and follow the instructions.

This a demo. Line Completed by John 

# React components get data from Web API

## Concepts

* Making network calls from JavaScript (superagent)
* When to get data (`componentDidMount`)
* Updating state with new data

## Code demo

* Walk-through of existing code base
* Add an item listing
* Add ability to remove an item
* Add ability to add an item

# Testing REST Web APIs routes

## Agenda

* Testing the requests and responses of the routes
* Use `supertest` because it understands Express.js
* Mock the database


## Demo

    npm install
    npx knex migrate:latest
    npx knex seed:run
    npm test

- Test the `POST /users` route


The lines above are copied from the code in class lecture.