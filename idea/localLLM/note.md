# Slack claude is dead, need an Enterprise Grid workspace and not available for HK

```sh
pip3 install --upgrade huggingface_hub
pip3 install transformers

# require token, gen a read token here: https://huggingface.co/settings/tokens
huggingface-cli login

# Using `low_cpu_mem_usage=True` or a `device_map` requires Accelerate
pip3 install accelerate
```
