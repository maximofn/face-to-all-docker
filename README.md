# Face to all docker

Dockerization of the [Hugging Face Face to all Space](https://huggingface.co/spaces/multimodalart/face-to-all)

 * Space: [https://huggingface.co/spaces/multimodalart/face-to-all](https://huggingface.co/spaces/multimodalart/face-to-all)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/face_to_all:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```