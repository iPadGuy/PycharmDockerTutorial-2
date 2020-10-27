**README**

# PyCharm - Configure an interpreter using Docker

### References
- https://www.jetbrains.com/help/pycharm/using-docker-as-a-remote-interpreter.html

**Note:** The `slim` versions of Docker images are preferred, and 
are the offical images for Python.

##### Tuesday, October 27, 2020
- This tutorial uses the `python:latest` Docker Image, which is a 
  shared tag with `3.9.0-buster`, not `3.9-slim-buster`. According 
  to what I have read, the `slim` versions are the officical 
  versions, and they are smaller than the full Debian builds, like 
  `buster`.
- This was pretty easy--I just wish it was more intuitive, or 