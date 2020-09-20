# Drone without limits

This repository contains everything that is need to build a Docker image with [drone](https://drone.io) Enterprise version without limits like build numbers. It is completely identical to official ones, e.g. using Alpine Linux and exports same environment variables by default (except Datatog). Runners that are built by Drone team can e safely used with this image.

The reason this image appeared is that official Drone image is already on Enterprise version but with limits applied, which isn't good for me, as I am individual and able to use Enterprise version for free and without limits.

## THE GREAT WARNING

Not all types of users are allowed to use this image, please consult with [drone documentation](https://docs.drone.io/enterprise/) first!

At the moment of last commit and build only these types of users are allowed to use this image:

1. Individuals who uses Drone without commercialization.
2. Students.
3. Organizations with under $1 million US dollars in annual gross revenue and less than $5 million in debt or equity funding.

Otherwise please use official Drone image from [Docker Hub](https://hub.docker.com/r/drone/drone) or [build open source edition by yourself](https://docs.drone.io/enterprise/#where-do-i-download-the-open-source-edition). Differences between Enterprise and Open Source editions are available [here](https://docs.drone.io/enterprise/#what-is-the-difference-between-open-source-and-enterprise).

## Installation and usage

This image can be used and configured according to [official Drone documentation](https://docs.drone.io/).
