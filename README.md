# Hello Docker Project

This project contains a simple Dockerfile that, when built and run, outputs “Hello, Captain!” to the console.

## Project URL

This is a local Docker project from the roadmap.sh, You can find the project details [here](https://roadmap.sh/projects/basic-dockerfile).

## Getting Started

These instructions will guide you through building and running the Docker image.

### Prerequisites

Ensure you have Docker installed on your machine. You can download and install Docker from [here](https://www.docker.com/products/docker-desktop).

### Instructions

1. **Clone the repository** (if applicable):

    ```bash
    git clone https://github.com/TalalNuman/hello-docker.git
    cd hello-docker
    ```

2. **Build the Docker image**:

    Run the following command to build the Docker image using the Dockerfile in the root directory:

    ```bash
    docker build -t hello-captain .
    ```

3. **Run the Docker container**:

    After building the image, you can run the container using:

    ```bash
    docker run hello-captain
    ```

4. **Output**:

    After running the container, you should see the following output in your terminal:

    ```bash
    Hello, Captain!
    ```
