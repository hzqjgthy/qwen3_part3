
conda create --name vllm python==3.12 -c https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main

conda activate vllm

pip install -U --no-cache-dir "bitsandbytes>=0.46.3"


pip install --upgrade vllm







































# 安装剩余依赖
pip install datasets==3.0.0 pandas==2.2.2 transformers==4.44.0 peft==0.12.0 tensorboard==2.18.0

pip install accelerate bitsandbytes




pip install deepspeed==0.14.5


还是出现了问题：
    安装了一下 CUDA 开发工具包：
    # Ubuntu/Debian 系统
    sudo apt update
    sudo apt install nvidia-cuda-toolkit


