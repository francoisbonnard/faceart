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

[link to the tutorial](https://learn.thinkdiffusion.com/transform-videos-with-ai-dancing-noodles-step-by-step-tutorial/)

File : dance-transfer-v80.json
Recommend : Turbo 24gb machine


## Dance Video

[Link 1 for credits](https://www.youtube.com/watch?v=rY9PDSfEjUk)




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


