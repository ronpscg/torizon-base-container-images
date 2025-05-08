# This repo serves as a place to store and create a container registry with torizon repos

## About
- Each such base image gets its own docker file 
- Trivial build by a github actions workflow file

Note that some Dockerfiles are trivial for the sake of reproducible builds in the presence of moving build targets.
It may be better to simply push the images to the registry, if possible (perhaps it is).
This is by no means a good example - but it is a quick one that serves the purpose of demostrating how to use *Torizon Core Builder* with remote repositories, and *GHCR* is a good option for that (especially if you pay for runners, or host your own)
