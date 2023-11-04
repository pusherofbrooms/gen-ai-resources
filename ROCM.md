# oobabooga/text-generation-webui on AMD 7xxx GPU ubuntu
## install amd drivers with amdgpu-install (seems to also install rocm drivers).
## setup a virtualenv
```
cd text-generation-webui
python -m venv venv
source venv/bin/activate
```
## install rocm specific torch and tensorflow
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm5.6
pip install tensorflow-rocm
pip install -r requirements_amd.txt
```
### will complain about typing-extensions version but ui still seems to work.
## run the webui
```
python server.py
```
### complains that bitsandbytes has no gpu support, but I haven't seen a problem from this.
## Caveats
- exllama2 and autoawq don't work with ROCM yet.
- The openai extension requires more python packages as of 2023-11-04. There is an openai branch which will probably incorporate these soon.
```
pip install tiktoken
pip install sentence_transformers
pip install SpeechRecognition
```

# automatic1111/stable-diffusion-webui on amd 7xxx gpu ubuntu
## install amd drivers with amdgpu-install (seems to also install rocm drivers).
## setup a virtualenv
```
cd stable-diffusion-webui
python -m venv venv
source venv/bin/activate
```
## run `webui.sh` as normal to install all dependencies and start the webui.
## If you get a core dump on start, check that your torch and torchvision are at least v2.1.0+rocm5.6. If they're not, run the following:
```
pip3 install torch torchvision --index-url https://download.pytorch.org/whl/rocm5.6 -U
```
## Now running webui.sh should bring up the website.

