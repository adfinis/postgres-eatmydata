# Postgres-Eatmydata

This wraps the upstream postgres images in eatmydata, which significantly
speeds up the database, AT THE EXPENSE OF WELL, EATING YOUR DATA.

Useful for running tests, development, but rather not for production.

Apart from this, nothing differs to the upstream docker images.

## Tags

We currently build images for PostgreSQL 10 and 11. You can use them by
referring to the corresponding tags:

    docker pull adfinissygroup/postgres-eatmydata:10
    docker pull adfinissygroup/postgres-eatmydata:11
    docker pull adfinissygroup/postgres-eatmydata:latest
