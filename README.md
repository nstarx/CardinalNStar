# Cardinal North Star

````
    N
    |
W --+-- E
    |
    S
````

> Kubeflow\
> http://nstarx.eastus.cloudapp.azure.com/ \
*user: user@example.com, Password1#*

> Sid's Portal\
http://nstarx-portal.eastus.cloudapp.azure.com/

> Kara's Backend\
http://nstarx-backend.eastus.cloudapp.azure.com/


# Dev

GitHub\
https://github.com/nstarx

#


# Azure Vanila Setup for FastChat

Machine Type 

https://learn.microsoft.com/en-us/azure/virtual-machines/nct4-v3-series


Install GPU Drivers

https://github.com/lm-sys/FastChat https://learn.microsoft.com/en-us/azure/virtual-machines/linux/n-series-driver-setup

Install PyEnv and Screen

Here is a dump of history, no special order
```
    1  sudo lshw -C display
    8  curl https://pyenv.run | bash
   12  pyenv install 3.10.5
    2  nvidia-smi
    3  sudo apt install virtualenv
    6  pip3 install "fschat[model_worker,webui]"
    8  curl https://pyenv.run | bash
    9  nano .bashrc 
   15  sudo  apt-get install build-essential
   18  sudo apt install zlib
   19  sudo apt install zlibsudo apt install zlib1g
   20  sudo apt install zlib1g
   21  sudo apt install zlib1g-dev
   22  pyenv install 3.10
   23  lspci | grep -i NVIDIA
   25  pyenv install --list
   26  pyenv 3.10
   29  pyenv activate systen
   33  pyenv install --list
   40  sudo apt-get install bzip2 libreadline6 libreadline6-dev openssl
   41  sudo apt-get install bzip2 libreadline6  openssl
   42  sudo apt-get install bzip2  openssl
   43  sudo apt-get install python-openssl
   45  sudo apt-get install libbz2-dev
   47  sudo apt install libssl-dev
   48  pyenv install 3.10.13
   49  /home/azureuser/.pyenv/versions/3.10.13/bin/python3.10
   50  pyenv virtualenv 3.10  project1
   51  pyenv versions
   55  wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-keyring_1.0-1_all.deb 
   56  sudo dpkg -i cuda-keyring_1.0-1_all.deb
   57  sudo apt-get update
   58  sudo apt-get -y install cuda-drivers
   59  nvidia-smi
       sudo apt-get install -y nvidia-container-toolkit
       docker run -it --gpus=all <image_name>
   60  pip3 install "fschat[model_worker,webui]"
   61  screen -S fastchat.serve.controller
   62  screen -S model_worker_vicuna
   63  screen -S gradio
   64  screen list
   65  screen -ls
   69  history
```

...
DS2 Machine URL after firewall open ports

FastChat UI at

```
http://40.76.227.135:7860/   ui

http://40.76.227.135:21001/docs   controller api

http://40.76.227.135:21002/docs     worker api

```
