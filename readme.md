# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Verify first docker is running with the following commands: ``docker-v`` and ``docker-compose -v``.

2. Then, run ``docker-compose up`` (you can use flag ``-d`` to put docker running in the background).

3. When it ends, try to access the local db pointing to <http://localhost:3000/api/ping>.

4. If everything is correct, you can jump to the frontend and try to go to <http://localhost:3001/register>. Once there, register with a cool name ;).

And that's all for the initial setup!
