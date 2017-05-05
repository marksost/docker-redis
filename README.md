# docker-redis

A utility that helps manage a Docker container running a Redis server. This is useful to avoid having to have Redis installed on your local machine if you need it for various storage projects.

---

## Installation

To install the utility, run the following command:

```
curl -sL https://raw.githubusercontent.com/marksost/docker-redis/master/install.sh | bash
```

NOTE: If you first `cd` into a directory within your path, you will be able to run this utility from any command line afterwards. Normally it's best to put this in `/usr/local/bin`.

## Usage

```
docker-redis status      Prints the status of the Redis container
docker-redis start       Starts the Redis container
docker-redis stop        Stops the Redis container
docker-redis restart     Restarts the Redis container
docker-redis update      Pulls the latest image for the Redis container
docker-redis help        Shows this message
docker-redis version     Prints the version number
```
