# install-rocm-linux-mint
install rocm on linux mint
sudo nano /etc/apt/sources.list.d/additional-repositories.list
add deb http://security.ubuntu.com/ubuntu jammy main universe
sudo apt update && export LC_ALL=C && sudo amdgpu-install --usecase=hiplibsdk,rocm
