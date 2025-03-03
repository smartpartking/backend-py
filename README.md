### Development

This starter project uses the `FastAPI` web framework and `uv` as a package manager. 

- You can add packages with `uv add <package>`
- Run the dev server with `uv run fastapi dev`

### Parking System API

As a continuation from the design round, we'll be building a simple stateless API for the Parking System. The API needs to be used by a UI so ensure that responses & possible errors are descriptive. You do not need to integrate with a database and can use hardcoded data. We should try to support the following requirements:

- should be able to get a list of spaces available, by size & type (EV/normal parking spot)
- should be able to add a car and carry out validation to see if it can be parked (check size, check type)
- add appropriate HTTP responses with errors where applicable:
    - valid request is processed successfully
    - invalid request (user/server, both)

#### Stretch goals

- Write a unit test (can use libraries)
- Integrate debug logging (can use libraries)
