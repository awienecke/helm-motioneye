### MotionEye

This helm chart was designed for deployment of MotionEye onto a RaspberryPi 4 with k3s installed, and an external drive mounted to /drive/

This chart assumes sufficient permissions to create the subdirectory tree in /drive/k3s (or wherever you have configured.)

Modifying this chart for an x86 host would simply require modifying the image tag in the yaml named after the product itself.
