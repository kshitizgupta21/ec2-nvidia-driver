### Instructions for installing CUDA 12.0 nvidia driver on ubuntu AMI on EC2 instance
1. Launch GPU ec2 instance with Ubuntu 20.04 AMI
2. In the instance install gcc
```
sudo apt update
sudo apt install build-essential
```
3. Follow the instructions, make sure to select the right version of OS to match that of AMI https://developer.nvidia.com/cuda-12-0-0-download-archive?target_os=Linux&target_arch=x86_64&Distribution=Ubuntu&target_version=20.04&target_type=runfile_local and select installer as runfile (local)

 
### Install docker
1. https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository
2. https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user
