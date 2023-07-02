## 启动

```shell
conda activate textgen
```


- 启动
```shell
python3 server.py --chat \
--model-dir models/ --lora-dir loras/ \
--verbose --n-gpu-layers 200000 \
--auto-launch
```