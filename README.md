# dockercompose_helloworld

## What

This repository is for testing git integrations in Portainer or CI/CD tools.
This repository hosts a simple docker-compose.yml file, which defines a simple helloworld http container.

Simply put in the URL to this repository in your tool of choice and declare docker-compose.yml as the file to load for deployment.
That should work - and if not, keep configuring your tool/host/network/whatever until it works.

## Why

This is meant for testing git integrations in tools like Portainer, which can monitor a git repo and automatically pull the newest changes and automatically deploy them.
Setting up that integration can be hard depending on the network and security settings one has to deal with.

I wanted an easy way to test such integrations, therefore I created a simple docker-compose.yml for a simple HTTP webserver, which answers with hello world.

Disclaimer: I **did not** write the webserver, I just found it and deemed it useful for tests.
