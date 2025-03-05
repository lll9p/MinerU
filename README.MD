update to version 1.2.2
**after pull, you should download models manually**

use below

```bash
pip3 install --no-cache-dir huggingface_hub && \
    wget https://github.com/opendatalab/MinerU/raw/master/scripts/download_models_hf.py -O download_models.py && \
    python3 download_models.py
```

or


```bash
pip3 install modelscope && \
    wget https://gcore.jsdelivr.net/gh/opendatalab/MinerU@master/scripts/download_models.py -O download_models.py && \
    python3 download_models.py 
```
