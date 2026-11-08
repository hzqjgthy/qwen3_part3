
conda create  --name unsloth python==3.12 -c https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main

conda activate unsloth

conda install jupyterlab

conda install ipykernel

pip install modelscope


pip install unsloth==2025.10.12
pip install unsloth_zoo==2025.10.13 
pip install transformers==4.57.1

pip install openai













pip install -r requirements.txt

pip install openai

pip install vllm -i https://pypi.tuna.tsinghua.edu.cn/simple

# 走 PyTorch 官方 CUDA 源
pip install --upgrade pip

pip install torch==2.4.0+cu121 torchvision==0.19.0+cu121 torchaudio==2.4.0+cu121 \
  --index-url https://download.pytorch.org/whl/cu121


pip install modelscope
pip install datasets==3.0.0





















# 安装剩余依赖
pip install datasets==3.0.0 pandas==2.2.2 transformers==4.44.0 peft==0.12.0 tensorboard==2.18.0

pip install accelerate bitsandbytes




pip install deepspeed==0.14.5


还是出现了问题：
    安装了一下 CUDA 开发工具包：
    # Ubuntu/Debian 系统
    sudo apt update
    sudo apt install nvidia-cuda-toolkit


