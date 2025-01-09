Need help? Reach us on [Discord](https://discord.gg/cTGZSwfzwt) - Tag `titannode`, `de_fi_ne` or `chasemedia`

<img src="https://raw.githubusercontent.com/Titan-Node/Titan-Node.github.io/refs/heads/main/Livepeer-Eliza-Mascot-Docs.png" alt="GitHub Logo" width="100%"/>

# Free Hosted Livepeer Inference Endpoints For Eliza

Use any of the following endpoints to run inference on Eliza for free.

By Livepeer Cloud SPE (Recommended)

```
https://dream-gateway.livepeer.cloud
```

By Titan Node (Alternative)

```
https://gateway.livepeer-eliza.com
```

## Quick Start

Edit your character file with the following:

1) Use Livepeer for all inference (automatically does text and image generation)

```
    "name": "",
    "clients": [],
    "modelProvider": "livepeer",
    "settings": {},
    "plugins": [],
```

2) Add `"imageModelProvider": "livepeer"` to your character file for using other text Generation providers.

```
    "name": "",
    "clients": [],
    "modelProvider": "openai",
    "imageModelProvider": "livepeer",
    "settings": {},
    "plugins": [],
```


## Available Models For Free

**LLM (text)**

`meta-llama/Meta-Llama-3.1-8B-Instruct` (default)

**Image**

`ByteDance/SDXL-Lightning` (default)

`SG161222/RealVisXL_V4.0`

`SG161222/RealVisXL_V4.0_Lightning`

`black-forest-labs/FLUX.1-dev`

`black-forest-labs/FLUX.1-schnell`

`stabilityai/stable-diffusion-3.5-large`

`stabilityai/stable-diffusion-3-medium-diffusers`

`stabilityai/stable-diffusion-3.5-medium`

## Want to host your own decentralized inference endpoint? Follow these guides

[Livepeer Docs - Start Gateway](https://docs.livepeer.org/ai/gateways/start-gateway)

[Livepeer Docs - Fund Gateway](https://docs.livepeer.org/gateways/guides/fund-gateway)

