# 2025 아주소중한딥러닝챌린지

## 개발 및 추론 환경

`vast.ai`에서 제공하는 [PyTorch (Vast) 이미지](https://hub.docker.com/r/vastai/pytorch/) 기반 Docker 환경  
1x RTX 6000Ada (48GB)  
Jupyter Notebook에서 코드 작성 및 추론 진행  
<br/>

## Required Packages

```
pip install -r requirements.txt
```

<details> <summary> requirements.txt 내용 </summary>

```
accelerate==1.10.1
asttokens==3.0.0
attrs==25.3.0
backcall==0.2.0
beautifulsoup4==4.13.5
bitsandbytes==0.47.0
bleach==6.2.0
certifi==2025.6.15
cfscrape==2.1.1
charset-normalizer==3.4.2
comm==0.2.2
debugpy==1.8.14
decorator==5.2.1
decord==0.6.0
defusedxml==0.7.1
docopt==0.6.2
einops==0.8.1
executing==2.2.0
fastjsonschema==2.21.2
filelock==3.18.0
flash_attn==2.8.3
fsspec==2025.5.1
hf-xet==1.1.5
huggingface-hub==0.34.4
idna==3.10
inquirerpy==0.3.4
ipykernel==6.29.5
ipython==8.12.3
ipython_pygments_lexers==1.1.1
ipywidgets==8.1.7
jedi==0.19.2
Jinja2==3.1.4
jsonschema==4.25.1
jsonschema-specifications==2025.4.1
jupyter_client==8.6.3
jupyter_core==5.8.1
jupyterlab_pygments==0.3.0
jupyterlab_widgets==3.0.15
MarkupSafe==2.1.5
matplotlib-inline==0.1.7
mistune==3.1.4
mpmath==1.3.0
nbclient==0.10.2
nbconvert==7.16.6
nbformat==5.10.4
nest-asyncio==1.6.0
networkx==3.3
numpy==2.1.2
nvidia-cublas-cu12==12.8.3.14
nvidia-cuda-cupti-cu12==12.8.57
nvidia-cuda-nvrtc-cu12==12.8.61
nvidia-cuda-runtime-cu12==12.8.57
nvidia-cudnn-cu12==9.7.1.26
nvidia-cufft-cu12==11.3.3.41
nvidia-cufile-cu12==1.13.0.11
nvidia-curand-cu12==10.3.9.55
nvidia-cusolver-cu12==11.7.2.55
nvidia-cusparse-cu12==12.5.7.53
nvidia-cusparselt-cu12==0.6.3
nvidia-nccl-cu12==2.26.2
nvidia-nvjitlink-cu12==12.8.61
nvidia-nvtx-cu12==12.8.55
packaging==25.0
pandas==2.3.2
pandocfilters==1.5.1
parso==0.8.4
pexpect==4.9.0
pfzy==0.3.4
pickleshare==0.7.5
pillow==11.0.0
pipreqs==0.5.0
platformdirs==4.3.8
prompt_toolkit==3.0.51
psutil==7.0.0
ptyprocess==0.7.0
pure_eval==0.2.3
pyarrow==21.0.0
Pygments==2.19.2
python-dateutil==2.9.0.post0
pytz==2025.2
PyYAML==6.0.2
pyzmq==27.0.0
referencing==0.36.2
regex==2025.8.29
requests==2.32.4
rpds-py==0.27.1
safetensors==0.6.2
setuptools==80.9.0
six==1.17.0
soupsieve==2.8
stack-data==0.6.3
sympy==1.13.3
timm==1.0.19
tinycss2==1.4.0
tokenizers==0.22.0
torch==2.7.1+cu128
torchaudio==2.7.1+cu128
torchvision==0.22.1+cu128
tornado==6.5.1
tqdm==4.67.1
traitlets==5.14.3
transformers==4.56.0
triton==3.3.1
typing_extensions==4.14.0
tzdata==2025.2
urllib3==1.26.20
wcwidth==0.2.13
webencodings==0.5.1
wheel==0.45.1
widgetsnbextension==4.0.14
yarg==0.1.9
```

</details>

<br/>

## 사용 모델

InternVL 3.5 8B : [🤗 HuggingFace](https://huggingface.co/OpenGVLab/InternVL3_5-8B) | [📃 arvix](https://arxiv.org/abs/2508.18265)

<br/>

## 실행 시간

- 이미지 데이터 전처리 : 약 7시간
- 테스트 데이터에 대한 Output 생성 : 약 3시간