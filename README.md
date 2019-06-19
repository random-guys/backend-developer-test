# Software Developer Application Test

Create a API that serves the latest scores of fixtures of matches in a “**Mock Premier League**”

## User Types

There should be:

- **Admin accounts** which are used to
  - signup/login
  - manage teams (add, remove, edit, view)
  - create fixtures (add, remove, edit, view)
  - Generate unique links for fixture
- **Users accounts** who can
  - signup/login
  - view teams
  - view completed fixtures
  - view pending fixtures
  - robustly search fixtures/teams
- Only the search API should be availble to the public.

## Authentication and Session Management

1. Ensure the service is stateless.
2. Session management should be handled using Redis.
3. Authenthecation and Authorization for admin and user accounts should be done using `Bearer token` and `JWT`.

## Tools/Stack

NodeJs (JavaScript or TypeScript)

## Tests

Unit tests are a must, submissions without tests will be ignored.

## Submission

1. Your API endpoints shoud be documented in POSTMAN.
2. Seed the db with lots of data before final submission.
3. Code should be hosted on a git repository, Github preferably.
4. The API should be hosted on a live server (e.g. https://heroku.com)

## Bonus

1. Bonus points for `containerization` using `docker`.
2. Bonus point for thorough documentation using POSTMAN.
3. Bonus points for e2e tests and use of `Jest` for tests.
4. Bonus points for `web caching` API endpoints using `Redis`.
5. Bonus points for implementing `rate limiting` for user account API access.

## Time Duration

7 days

## NB:

Please send an email to acknowledge the receipt of this document.
