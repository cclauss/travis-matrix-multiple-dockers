# Use a Travis matrix to build and run multiple Docker containers in parallel

Let's try to build and test BOTH Python 2.7 and 3.x Dockerfiles in a single .travis.yml file...

https://stackoverflow.com/questions/39422135/travis-build-multiple-docker-images-from-a-single-repo

This matrix approach should do the build and run in parallel instead of serially.
