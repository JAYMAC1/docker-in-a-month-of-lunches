# 4.6 Lab
Lab time! You’re going to put into practice what you’ve learned about multi-stage builds and optimizing Dockerfiles. In the source code for the book, you’ll find a folder at ch04/lab which is your starting point. It’s a simple Go web server application, which already has a Dockerfile, so you can build and run it in Docker. But the Dockerfile is in dire need of optimizing, and that is your job.

There are specific goals for this lab:

Start by building an image using the existing Dockerfile, and then optimize the Dockerfile to produce a new image.
The current image is 800 MB on Linux and 5.2 GB on Windows. Your optimized image should be around 15 MB on Linux or 260 MB on Windows.
If you change the HTML content with the current Dockerfile, the build executes seven steps.
Your optimized Dockerfile should only execute a single step when you change the HTML.