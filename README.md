🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU <br />
🥳 Please join my patreon community https://patreon.com/camenduru <br />

## 🦒 Colab

# 🚦 WIP 🚦

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/AnimateDiff-colab/blob/main/AnimateDiff_colab.ipynb) | AnimateDiff_colab (--L 24 --W 512 --H 512 🦒 Colab Free Limit)

## Tutorial
Please edit `/content/animatediff/configs/prompts/1-ToonYou.yaml` file for different prompts. We can use it with any LoRA 🥳 <br />
output files here `/content/animatediff/samples/`

```
ToonYou:
  base: ""
  path: "models/DreamBooth_LoRA/toonyou_beta3.safetensors"
  motion_module:
    - "models/Motion_Module/mm_sd_v14.ckpt"
    - "models/Motion_Module/mm_sd_v15.ckpt"

  seed:           [10788741199826055526, 6520604954829636163, 6519455744612555650, 16372571278361863751]
  steps:          25
  guidance_scale: 7.5

  prompt:
    - "best quality, masterpiece, 1girl, looking at viewer, blurry background, upper body, contemporary, dress"
    - "masterpiece, best quality, 1girl, solo, cherry blossoms, hanami, pink flower, white flower, spring season, wisteria, petals, flower, plum blossoms, outdoors, falling petals, white hair, black eyes,"
    - "best quality, masterpiece, 1boy, formal, abstract, looking at viewer, masculine, marble pattern"
    - "best quality, masterpiece, 1girl, cloudy sky, dandelion, contrapposto, alternate hairstyle,"

  n_prompt:
    - ""
    - "badhandv4,easynegative,ng_deepnegative_v1_75t,verybadimagenegative_v1.3, bad-artist, bad_prompt_version2-neg, teeth"
    - ""
    - ""
```

## Main Repo
https://github.com/guoyww/animatediff/

## Page
https://animatediff.github.io/

## Paper
https://arxiv.org/abs/2307.04725

## Output
![0-best-quality,-masterpiece,-1girl,-looking-at-viewer,-blurry-background,-upper (5)](https://github.com/camenduru/AnimateDiff-colab/assets/54370274/34f3ec0a-277b-4cec-a5c8-468b666b739b)
![1-masterpiece,-best-quality,-1girl,-solo,-cherry-blossoms,-hanami,-pink-flower, (3)](https://github.com/camenduru/AnimateDiff-colab/assets/54370274/7fa841d4-31b8-469d-ad32-f56a986a2c3d)
![2-best-quality,-masterpiece,-1boy,-formal,-abstract,-looking-at-viewer,-masculine, (2)](https://github.com/camenduru/AnimateDiff-colab/assets/54370274/b4976fb1-758e-4d9b-9c65-40cea7c60fff)

