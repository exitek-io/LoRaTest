Repo for testing LORA models and different parts of generation pipeline \

Make sure you have installed dependencies from requirements and upgraded your libgcc \

Config params: \

REPO_PTH - Path baseline SD model \
VAE_PTH - Path to VAE to use \
LORA_PTH - Path to lora to use \
EDITOR_IMAGE_CACHE_ROOT_DIR - Path to image cache dir \
VARIANT - fp16 or fp32 \
USE_LORA - True # False to use SD without lora \
LORA_SCALE - Lora scale param (higher gives more weight to Lora while inference) \
ADAPTER_NAME  -  Don't change \
TEST_IMG_PTH - test image \

Prompt example: \
edit_prompt = "Glam, a woman with glam makeup, glam look, 4k, the best quality, masterpiece, glam thick eyebrows, glam thick eyelashes, soft eyelashes, glam blush" \


The most important params for generation \
skip \
edit_guidance_scale (CFG) \
detail_restoration_amount \
