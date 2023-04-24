# stablediffusion

***Instalação***

```
lsmod | grep nvidia
```

```
nvidia-smi
```

```
sudo apt update
```

```
sudo apt install build-essential
```

```
gcc --version

g++ --version
```

```
sudo apt install nvidia-cuda-toolkit
```

```
nvcc --version
```


```
sudo apt install linux-headers-$(uname -r) -y
```

```
sudo wget -O /etc/apt/preferences.d/cuda-repository-pin-600 https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-ubuntu2004.pin
```

```
sudo apt-key adv --fetch-keys https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/7fa2af80.pub
```

```
sudo add-apt-repository "deb https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/ /"
```

```
sudo apt update
```


```
sudo apt full-upgrade
```

```
sudo apt install cuda
```
***Abra***
```
sudo nano /etc/profile.d/cuda.sh
```
***Coloque e Salve***

```
export CUDA_HOME="/usr/local/cuda"

export PATH="$PATH:$CUDA_HOME/bin"
```


```
sudo reboot
```


```
nvcc --version
```

```
sudo visudo -f /etc/sudoers
```
 ***secure_path, append :/usr/local/cuda/bin***

 

