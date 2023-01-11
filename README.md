# Github Actions workflow evaluation

This repository aims to provide examples or testcases for the capabilities of official Github action runner instances.
For example we will test the Docker availability for different versions on different operating systems.

## Results
### Docker availability
Windows and Ubuntu runner have docker provided. MacOS runner do not, because MacOS is not supported by Docker and Docker is not licensed to be used in a service like that in MacOS (see [here](https://github.com/orgs/community/discussions/25777))