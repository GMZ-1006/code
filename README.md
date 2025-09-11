# 创建环境并安装依赖
conda env create -f environment.yml
# 激活环境并下载数据集和模型
conda activate myenv  
git clone https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1
# 运行
./run.sh
