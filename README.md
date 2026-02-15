Steps to Containerize a Static Website with Apache

Create a project directory for the website files.

Add your static website files (HTML, CSS, etc.) to the project directory.

Create a Dockerfile using Ubuntu 22.04 as the base image.

Install Apache and Apache utilities inside the Docker image.

Copy the website files into the container’s web directory.

Expose port 80 to allow HTTP access.

Set Apache to run in the foreground as the container’s main process.

Build the Docker image.

Run the container and map the host port to the container port.

Test the website by accessing it through a browser.

Stop and remove the container when done.

Optionally, clean up and optimize layers to reduce image size.
