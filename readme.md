- [process](#process)
- [Flux](#flux)
- [Hidden Faces](#hidden-faces)
  - [Prompt](#prompt)
- [LORA](#lora)
  - [Lora for Flux](#lora-for-flux)
  - [Alien for flux 1.D](#alien-for-flux-1d)
  - [Post to make on discord](#post-to-make-on-discord)
- [Dancing Noodles](#dancing-noodles)
  - [Dance Video](#dance-video)
- [ComfyUI](#comfyui)
  - [Workflow](#workflow)
  - [ComfyUI-AnimateAnyone-Evolved](#comfyui-animateanyone-evolved)
  - [ComfyUI tutorial](#comfyui-tutorial)
    - [How to save a workflow in the folder workflow](#how-to-save-a-workflow-in-the-folder-workflow)
    - [Ultimate SD Upscale missing](#ultimate-sd-upscale-missing)
    - [controlnet](#controlnet)
    - [Instant ID](#instant-id)
  - [Using Searge](#using-searge)
  - [keyboard shotcut](#keyboard-shotcut)
    - [check](#check)
- [Youtube download](#youtube-download)
  - [VLC not working](#vlc-not-working)
  - [use firefox extension](#use-firefox-extension)


Create Table of Contents / update Table of contents

# process

[Learn ThinkDiffusion](https://www.thinkdiffusion.com/learn)

[Link to Roop](https://github.com/s0md3v/sd-webui-roop)

[Mastering Image Prompts in Stable Diffusion AI with IP-Adapter](https://learn.thinkdiffusion.com/mastering-image-prompts-in-stable-diffusion-ai/)

[Make anyone say anything with Wav2Lip's Lip Sync and any existing video](https://learn.thinkdiffusion.com/wav2lip-lip-sync-any-existing-video/)

# Flux

[Link to Flux Model](https://huggingface.co/lllyasviel/flux1-dev-bnb-nf4/tree/main)

Link to copy in Forge/Models/Stable Diffusion :

https://huggingface.co/lllyasviel/flux1-dev-bnb-nf4/resolve/main/flux1-dev-bnb-nf4.safetensors

https://huggingface.co/lllyasviel/flux1-dev-bnb-nf4/resolve/main/flux1-dev-bnb-nf4-v2.safetensors

Run Forge 

# Hidden Faces 

[Link to tuto HiddenFaces](https://learn.thinkdiffusion.com/hidden-faces-and-text-with-control-net-qr-code-monster/)


## Prompt

mountains, red sunset, 4k, ultra detailed, masterpiece
An autumn landscape in a mountainous forest, 4k, ultra detailed, masterpiece
In a tropical and rocky forest during autumn, 4k, ultra detailed, masterpiece

# LORA

[Lora models and how to use them with Stable Diffusion](https://learn.thinkdiffusion.com/how-to-use-loras/)

## Lora for Flux

[Emmanuel MACRON FLUX DEV LORA](https://civitai.com/models/652678/emmanuel-macron-flux-dev-lora)

https://civitai.com/api/download/models/742325?type=Model&format=SafeTensor

<lora:emmanuel macron:1>
<lora:Macron_Lora_Civitai_r1:1>

realistic photo of a Emmanuel Macron  with hair rollers on it's head,<lora:Macron_Lora_Civitai_r1:1>

Link to Flux on Civitai 
https://civitai.com/models/618692?modelVersionId=691639 

## Alien for flux 1.D

https://civitai.com/models/213836/xenomorph-alien-flux1d-and-sdxl?modelVersionId=736892

Base model: Flux.1 D (D for dev model. S for Schnell model. I only use D for the best quality!)

## Post to make on discord

Install Flux from civitail

![alt text](image-1.png)

![alt text](image.png)

AssertionError: You do not have CLIP state dict!
Time taken: 24.3 sec.

A: 11.12 GB, R: 11.41 GB, Sys: 12.0/44.3223 GB (27.0%)*

[Link to discord discussion](
https://discord.com/channels/1102237470457864282/1102259141839441960/1286089274889863199)

# Dancing Noodles

## Tuto 1
[link to the tutorial](https://learn.thinkdiffusion.com/transform-videos-with-ai-dancing-noodles-step-by-step-tutorial/)




## Tuto 2
[tuto 2](https://www.youtube.com/watch?v=d3vpKqTiTvc)

[Link to dance-transfer Discord](https://discord.com/channels/808550927774515250/1268437080585932800/1268538941334618173)

## Dance Video

[Link 1 for credits](https://www.youtube.com/watch?v=rY9PDSfEjUk)

Last log lines :

    Requested to load ControlNet
    Requested to load ControlNet
    Requested to load AnimateDiffModel
    Requested to load BaseModel
    Loading 4 new models

Missing input for model

![alt text](image-6.png)


# ComfyUI

## Workflow

[Link comfyworkflows](https://comfyworkflows.com/)

## ComfyUI-AnimateAnyone-Evolved

[Link to github](https://github.com/ankur8613/ComfyUI-AnimateAnyone-Evolved)

## ComfyUI tutorial

[ComfyUI Workflow Creation Essentials For Beginners](https://www.youtube.com/watch?v=VM9snsuoqBc)

[Master AI image generation - ComfyUI full tutorial 2024](https://www.youtube.com/watch?v=g74Cq9Ip2ik ) 
start again at [44'](https://youtu.be/g74Cq9Ip2ik?si=Ig7ef4y0-AP27nfq&t=2644)

### How to save a workflow in the folder workflow

[Link to discord](https://discord.com/channels/1102237470457864282/1102259141839441960/1286992144460156970)

### Ultimate SD Upscale missing 

### controlnet 

Install Models / controlnet Union not found

|ID| Type|Base|Name|Filename|Description|
|----------|----------|----------|----------|----------|--------|
| 313 | controlnet|SDXL|xinsir/ControlNet++: All-in-one ControlNet|diffusion_pytorch_model.safetensors|All-in-one ControlNet for image generations and editing!|

Install Nodes

comfyUI-art-venture (preprocessor )

### Instant ID

https://github.com/cubiq/ComfyUI_InstantID

install nodes from : 
100	cubiq	 ComfyUI InstantID (Native Support)

install InsightFace Model

https://huggingface.co/InstantX/InstantID/resolve/main/ip-adapter.bin?download=true

in 

    comfyUI/models/instantid


Also install instantid model 



https://github.com/cubiq/ComfyUI_IPAdapter_plus/issues/263
same i had the double /models/antelopev2/antelopev2/ THANK YOU!

## Using Searge 

https://learn.thinkdiffusion.com/introduction-to-flux-ai-quick-guide/#download-workflow-for-the-webinar

Install nodes
https://github.com/SeargeDP/SeargeSDXL
https://github.com/SeargeDP/ComfyUI_Searge_LLM

Install Mistral
https://huggingface.co/MaziyarPanahi/Mistral-7B-Instruct-v0.3-GGUF/resolve/main/Mistral-7B-Instruct-v0.3.Q4_K_M.gguf

Create a new folder called llm_gguf in the ComfyUI/models directory.

![alt text](image-4.png)


## keyboard shotcut

| key | action | 
|-|-|
| ctrl + left mouse| select node | 
| shift + ctrl | move selected node |
 ctrl + A| select all |
|Ctrl M| Mute a Node |
 Ctrl + B | Bypass |
 double click| search|
 |ctrl+shift+V|paste with link|


convert widget to input -> search -> primitive (Reroute Primitive )

### check

Install custom nodes : Image chooser

Model : 4x-UltraSharp

# Youtube download 

## VLC not working
Media / Convert media / Network / URL Youtube

Patch VLV : Go to [code videolan](https://code.videolan.org/videolan/vlc/-/tree/master/share/lua/playlist)

and download this file [youtube.lua](https://code.videolan.org/videolan/vlc/-/blob/c49166f43588bd9dccb85620316ae4f5c28ae797/share/lua/playlist/youtube.lua)

In this directory : C:\Program Files\VideoLAN\VLC\lua\playlist
replace the youtube.luac file

## use firefox extension

use [this](https://videodroid.org/pro_upgrade.html)

moz-extension://66ac18bd-3ddd-409e-b964-8e09bf093566/options/options.html


