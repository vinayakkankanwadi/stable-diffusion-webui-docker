# stable-diffusion-webui-docker
Stable Diffusion WebUI Docker Simple

```
Simple version of stable diffusion in docker

Source Repository: 
- https://github.com/vinayakkankanwadi/stable-diffusion-webui-docker

Based on:
- AUTOMATIC1111/stable-diffusion-webui

Offers:
- Docker GPU support for AUTOMATIC1111/stable-diffusion-webui 
- Does not make changes to AUTOMATIC1111/stable-diffusion-webui
- use SD_WEBUI_VERSION:-v1.9.4 to build version of AUTOMATIC1111/stable-diffusion-webui
- Docker compose using Command Line Arguments
- Based on pytorch/pytorch:2.1.2-cuda12.1-cudnn8-runtime
- Available Image aauno/stable-diffusion-webui-docker:latest
- Use "entrypoint" and "command" in docker-compose to customize as required
- Volume is mapped using "--data-dir"

Future Plans:
- CI/CD for automated image update on AUTOMATIC1111/stable-diffusion-webui release

Reference:
- AUTOMATIC1111/stable-diffusion-webui

```
