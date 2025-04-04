# Xei

<p align="center">
    <img src="./xei.jpg" />
</p>

__Xei__ (Persian: شیء or زِی) is a "family" of AI models trained on day to day tasks with the goal of being multilingual and multi purpose. These models are available from 0.1 billion parameters (approximately 135 million parameters) up to 671 billion parameters. 

The models are trained on different bases with different structures and one of the goals of making these models was to make users able to run most of these locally. 

## Download Models

In order to download models, you can go ahead and download them from our [Ollama](https://ollama.com/haghiri/xei) repository. Also if you want to run 100B or 671B models, we've provided a script to run it on modal which can be accessible [here](https://github.com/aqua-regia-ai/modal). 

## The Platform 

The platform is available at [chat.aquaregiai.com](https://chat.aquaregiai.com) and after signing up, you'll be able to access 671B model. Remember that the models are mostly made to be able to run on consumer GPU. 

## Models

| Model | Architecture | Multilignual |
| :----:| :------------:|:-----------:|
| `0.1b` | LLaMA         | 🔴          |
| `0.5b` | Qwen          | 🟠          |
| `2b`   | Gemma2        | 🟢          |
| `8b`   | Command-R     | 🟢          |
| `32b`  | Command-R     | 🟢          |
| `100b` | Command-R     | 🟢          |
| `671b` | DeepSeek V2   | 🟢          |

## License

Most of the usage is licensed under _Apache 2.0_ but if you're in a direct affiliation of OpenAI or Google, you may be using these models only if you deposit one million dollars worth of bitcoin to the following wallet:

```
bc1qrnpk2sq4gu0zevauv8sg6zc9sqsypsjrdhkpvx
``` 