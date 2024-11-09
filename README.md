### NOTE: This has been built on ARM and probably only will work with ARM CPUs.
## Description
This is a ROS Noetic docker image with [TagSLAM](https://github.com/berndpfrommer/tagslam) installed for rapid deployment.

## Getting started
Pull the docker image
```bash
docker pull ghcr.io/raameshb/tagslam
```
Run the docker image
```bash
docker run -it --network host ghcr.io/raameshb/tagslam
```
After running the image, the correct files will be sourced and the catkin workspace will be built, allowing you to use tagslam directly

## Usage
This should work just like any other TagSLAM install, refer to the [documentation from the official repo](https://berndpfrommer.github.io/tagslam_web/).
