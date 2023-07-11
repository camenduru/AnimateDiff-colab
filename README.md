🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU <br />
🥳 Please join my patreon community https://patreon.com/camenduru <br />

## 🦒 Colab

# 🚦 WIP 🚦

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/AnimateDiff-colab/blob/main/AnimateDiff_colab.ipynb) | AnimateDiff_colab (256x256 🦒 Colab Free)

## Tutorial
For prompts please edit `/content/animatediff/configs/prompts/1-ToonYou.yaml` file 

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
![e653f235-12fc-4b80-9d9e-c53d7955427a](https://github.com/camenduru/AnimateDiff-colab/assets/54370274/409077db-6ee0-41ac-aee2-a341e13f68dd) ![1-masterpiece,-best-quality,-1girl,-solo,-cherry-blossoms,-hanami,-pink-flower,](https://github.com/camenduru/AnimateDiff-colab/assets/54370274/a8909ab6-b657-4fc8-8930-ccdf31bd73ec)
