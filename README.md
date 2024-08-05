# Koboldcpp-Android-Termux
I made an easier to follow install guide for koboldcpp. Please give credit to the creators of the apps I'm not the creator of these apps I'm just making easier to follow installation guides thx




1>


pkg updated && pkg upgrade -y && termux-setup-storage && pkg install wget -y && pkg install git -y && pkg install proot -y && cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh

2>

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && pip install ffmpeg && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && apt install wget

3>

apt install openssl

4>

git clone https://github.com/LostRuins/koboldcpp.git

5>

cd koboldcpp
 
 6>
 
make

7>

wget https://huggingface.co/concedo/KobbleTinyV2-1.1B-GGUF/resolve/main/KobbleTiny-Q4_K.gguf


koboldcpp.py --model KobbleTiny-Q4_K.gguf



Connect to http://localhost:5001 on your mobile browser


Launch Command Example: Change the sdmodel to any model u want sdxl works but if u have limited ram use --sdquant command, erase sdquant for sd 1.5 models


cd koboldcpp

python koboldcpp.py --sdmodel opendalle_v11.safetensors --model KobbleTiny-Q4_K.gguf --sdquant

