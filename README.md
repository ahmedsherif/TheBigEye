# The Big Eye

ServerSentEvents (also known as SSE or Eventsource) firehose of [GitHub public timeline](https://developer.github.com/v3/activity/events/#list-public-events)

## Setup

Clone the repository

git clone https://github.com/ahmedsherif/TheBigEye.git

Generate a new GitHub personal access token here: https://github.com/settings/tokens/new

## Start the server:

    ACCESS_TOKEN=your_personal_access_token node app.js

Receive events here: http://localhost:5001/events
