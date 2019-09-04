# postgres-12beta3-alpine-hashids

A variant of [postgres:12-beta3-alpine](https://hub.docker.com/_/postgres), with the pg_hashids extension included.

This uses [jaredreisinger/postgres-12beta3-alpine-dev](https://hub.docker.com/r/jaredreisinger/postgres-12beta3-alpine-dev) to build the extension, then copies it into a clean [postgres:12-beta3-alpine](https://hub.docker.com/_/postgres) image.

## Usage

Once you have PostgreSQL spun up, use `CREATE EXTENSION pg_hashids;` to get access to the hashids functions.
