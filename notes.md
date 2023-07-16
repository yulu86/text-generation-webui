# Notes

## 启动服务
```bash
conda activate textgen

python3 server.py --chat --character Chiharu_Yamada --loader exllama_hf --disk --model anon8231489123_vicuna-13b-GPTQ-4bit-128g --auto-devices --n-gpu-layers 200000 --auto-launch --listen --listen-port 7861 --api
```