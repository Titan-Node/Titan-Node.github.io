# Free Hosted Livepeer Inference Endpoints For Eliza

Use any of the following endpoints to run inference on Eliza for free.

By Titan Node

```
https://gateway.livepeer-eliza.com
```

By Livepeer AI SPE

```
https://dream-gateway.livepeer.cloud
```

## Quick Start

1) For image generation, make sure `IMAGE_GEN=TRUE` is set in your .env file.
```
# Feature Flags
IMAGE_GEN=TRUE
```
   
2) Make sure to add `ModelProvider": "livepeer"` and `"imageModelProvider": "livepeer"` to your character file.

```
    "name": "",
    "clients": [],
    "modelProvider": "livepeer",
    "imageModelProvider": "livepeer",
    "settings": {},
    "plugins": [],
```


## Available Models For Free

**LLM (text)**

`meta-llama/Meta-Llama-3.1-8B-Instruct` (default)

**Image**

`ByteDance/SDXL-Lightning` (default)

## Want to host your own decentralized inference endpoint? Follow these guides

[Livepeer Docs - Start Gateway](https://docs.livepeer.org/ai/gateways/start-gateway)

[Livepeer Docs - Fund Gateway](https://docs.livepeer.org/gateways/guides/fund-gateway)

