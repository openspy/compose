# OpenSpy Docker compose

This docker compose script can be used to run the basics of openspy.

Run it with `docker-compose -f docker-compose.yml up`


## Running a local dev environment

Clone this repo by running the command `git clone --recursive https://github.com/openspy/compose`
To run a local dev environment, ensure that you have downloaded the geoip database and placed it in the geoip folder, then run the command `docker compose -f docker-compose-dev.yml up`
This will automatically create and build a full OpenSpy server for local development.

## Redirecting to DEV OpenSpy
There are two methods to do this:
* add each domain you require to your hosts file.
* create a DNS server with a wildcard `A` record to point to your docker host.
