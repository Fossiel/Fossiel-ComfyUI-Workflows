# Fossiel ComfyUI Workflows
This repo houses workflows for ComfyUI. They will eventually range in difficulty from very simple to very advanced. Due to my system constraints, these workflows are specifically geared towards low VRAM usage. If your rig has similar specs to mine, these workflows should work fantastically for you as well.

#### My System Specs:
- 12th Generation i7 Laptop
- 32GB System RAM
- Nvidia RTX3050(mobile) with 4GB VRAM



## Workflows:

### SD1.5 Fantasy Character Creator v1.0

While newer image generation models have improved dramatically in both output quality and prompt adherence, Stable Diffusion 1.5 models still generate the most ridiculously pretty women of all open source AI models with minimal effort required by the user. This workflow uses the meinaunreal_v3 model and its prompt adherence may be abysmal but it generates unique, fantastically pretty women.  

Drag the image below into ComfyUI to load the workflow.  

Tip: To introduce variation in facial features of generated characters, add the name of a well known celebrity or fashion supermodel to the positive prompt.  

![SD1-5_Fantasy_Character_Creator_v1-0](images/SD1-5_Fantasy_Character_Creator_v1-0.png)
---
### SD1.5 Semi-Real Character Creator v1.0

This workflow uses an SD1.5 model stack to produce "semi-realistic" characters. Warped limbs are this sport's injuries but the workflow runs very fast and good generations happen frequently. On the plus side, the characters generated have such a high level of consistency that they have to be forced into looking differently. To accomplish this, add pre-SD1.5 (<2022) celebrity names to the prompt in the format `(Celebrity Name:1.0)` and adjust the strength after the colon. Multiple names can be added to make amalgamated changes. Use this ethically by only affecting the output and not actually trying to copy the celebrity's face.  

Drag the image below into ComfyUI to load the workflow.  

![SD1-5_Semi-Realistic_Character_Creator_v1-0](images/SD1-5_Semi-Real_Character_Creator_v1-0.png)



## History
- 2026/03/20 – Added SD1.5 Semi-Realistic Character Creator v1.0 workflow.  
- 2025/10/26 – Added SD1.5 Fantasy Character Creator v1.0 workflow.  

## Coming Soon:
- Z-Image-Turbo Character Creator.
- Low VRAM Qwen Edit Plus Workflow.  
- Practical use of WAN2.2 on potatoes.  

## Credits
- All the developers who make tools available to everyone using local AI  
- Model developers for supplying fantastic open source models, free of charge.  
