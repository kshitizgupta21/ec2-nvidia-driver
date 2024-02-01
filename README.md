### Instructions for installing CUDA 12.0 nvidia driver on ubuntu AMI on EC2 instance
1. Launch GPU ec2 instance with Ubuntu 20.04 AMI
2. In the instance install gcc
```
sudo apt update
sudo apt install build-essential
```
3. Follow the instructions at https://developer.nvidia.com/cuda-12-0-0-download-archive?target_os=Linux&target_arch=x86_64&Distribution=Ubuntu&target_version=20.04&target_type=runfile_local and select installer as runfile (local)

 
