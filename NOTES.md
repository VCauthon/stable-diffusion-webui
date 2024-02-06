
### Running stable diffusion

1. Install linux dependencies
    - `sudo apt-get update`
    - `sudo apt install wget git python3 python3-venv libgl1 libglib2.0-0`
2. Create a conda environment and activate it
    - `conda create -n stable-diffusion-webui python==3.10`
    - `conda activate stable-diffusion-webui`
3. Run the webui.sh
    ```bash
        bash webui.sh --skip-torch-cuda-test
    ```
---

### Changing the current model

Stable diffusion webui allows changing the current model for another one.

Pages where models can be retrieved:
- https://civitai.com

Setting a concrete model:
1. Download: https://civitai.com/models/260267/animagine-xl-v3
2. Load all models into: [/models/Stable-diffusion/](/models/Stable-diffusion/)

---

### Setting a concrete checkpoint

A checkpoint is a file that saves the state of a machine learning model at a specific point during training, allowing for later resumption of the process or making predictions. In Stable Diffusion projects, checkpoints are crucial for modifying and customizing the model, enabling image generation based on previous learnings.

All checkpoints are retrieved from the following source:
- https://civitai.com/
