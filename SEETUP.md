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


