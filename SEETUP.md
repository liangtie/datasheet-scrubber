# Setup

## Install AnaConda

wget https://repo.anaconda.com/archive/Anaconda3-2023.07-Linux-x86_64.sh

bash Anaconda3-2023.07-Linux-x86_64.sh

source ~/.bashrc

## Setup Virtual Env

conda create -n datasheet-scrubber python=3.11
conda activate datasheet-scrubber

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --set show_channel_urls yes

conda install -c anaconda tensorflow


pip config set global.index-url http://mirrors.aliyun.com/pypi/simple
pip install -r ./requirements.txt


## Model Download links

1. Models.zip

https://drive.google.com/u/0/uc?id=17lDuMDquBpam5EwPMyqU1omMatLXGGgq&export=download

2. Full_Dataset.zip

https://drive.google.com/u/0/uc?id=164l6FN-UDHalxcGys4AsUVg1YlvfmCfF&export=download

3. Table_extract_robust.zip (Invalid link)

https://drive.google.com/u/0/uc?id=1ub5Z4lMTTX1S428TZG4NttkzYaGuR7ZK&export=download

4. Yolo

 - yolo.h5: https://drive.google.com/u/0/uc?id=15imxnopP_4ILtg0V2Ni11IGtPxA-dthb&export=download

 - yolov3.weights : https://drive.google.com/u/0/uc?id=12-sLCv6m4z---qXWSHVZSSA6WzfmzNNM&export=download

 - yolo.py (Invalid link) : https://drive.google.com/u/0/uc?id=1-_tOr99SVXAR7OH2y3KrjRA4ZJA4IdVf&export=download

 - trained_weights_1915_final.h5 : https://drive.google.com/u/0/uc?id=1uDQZVsOqLws3EUPjkNY6md4LSzAQfOFD&export=download




