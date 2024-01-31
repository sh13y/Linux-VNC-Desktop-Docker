# Launch Linux VNC Desktop Docker on Google Cloud Platform

If you're looking for a quick and easy way to set up a Linux VNC desktop using Docker on Google Cloud Platform (GCP), you're in the right place. Follow these simple steps to get started.

## Prerequisites

- GCP Account with root access
- Free 16GB RAM and 4vCPU

## Instructions

1. Go to [Google Cloud Console](https://console.cloud.google.com/).

2. Activate the Cloud Shell by clicking on the terminal icon in the top right corner.

3. Paste the following command in the Cloud Shell terminal:

    ```bash
    docker run -p 8080:80 dorowu/ubuntu-desktop-lxde-vnc
    ```

4. Press Enter to run the command. This will launch a Linux VNC desktop Docker container.

5. After the code has executed, click on "Web Preview" in the Cloud Shell toolbar.

6. Select "Preview on port 8080" from the dropdown.

7. You're done! Access your Linux VNC desktop by navigating to the provided URL in your web browser.

## Note

- Ensure that your GCP instance has the required resources (16GB RAM, 4vCPU) for optimal performance.

Feel free to customize and explore the Docker image for additional configurations.

Happy coding!
