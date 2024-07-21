<h1 align="center" margin="0">
  <a href="https://unsloth.ai"><picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://i.ibb.co/phm1qVZ/studio-beta-large-text.png">
    <source media="(prefers-color-scheme: light)" srcset="https://i.ibb.co/phm1qVZ/studio-beta-large-text.png">
    <img alt="unsloth logo" src="https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20logo%20black%20text.png" height="60" style="max-width: 100%;">
  </picture></a>
</h1>

<h3 align="center" style="margin: 0;">
User friendly WebUI to create & run custom LLMs.
</h3>
<h3 align="center">Unsloth Studio creates finetuned models which you can chat with and save locally. Zero code and beginner friendly.
</h3>
<br/>
<p align="center">
  <a href="https://docs.unsloth.ai/">
    <img src="https://i.ibb.co/rGM1b0X/start-button.png" height="45" alt="Start for free" />
  </a>
</p>
<br>

https://github.com/nomic-ai/gpt4all/assets/70534565/513a0f15-4964-4109-89e4-4f9a9011f311

<div align="center">

### [Inference only](https://unsloth.ai/) &nbsp;•&nbsp; [Documentation](https://docs.unsloth.ai/) &nbsp;•&nbsp; [Join our Discord](https://discord.com/invite/unsloth)

</div>

## ✨ Features
- Unsloth makes fine-tuning **[2-5x faster](https://github.com/unslothai/unsloth/tree/main#-performance-benchmarking)** with **80% less memory**
- [Inference](https://colab.research.google.com/drive/1aqlNQi7MMJbynFDyOQteD2t0yVfjb9Zh?usp=sharing) and loading is 2x faster with Unsloth.
- Maximum context lengths can be increased by 3-8x with Unsloth.
- Models can be exported to GGUF, Ollama, vLLM or uploaded to Hugging Face.
- Runs locally on **Linux** and **Windows** via WSL.
- Supports 4bit and 16bit QLoRA / LoRA finetuning via [bitsandbytes](https://github.com/TimDettmers/bitsandbytes).

## 🦥 Unsloth.ai News
- 📣 NEW! [Mistral Nemo-12b](https://colab.research.google.com/drive/17d3U-CAIwzmbDRqbZ9NnpHxCkmXB6LZ0?usp=sharing) both Base and Instruct now supported
- 📣 NEW! [Gemma-2-9b](https://colab.research.google.com/drive/1vIrqH5uYDQwsJ4-OO3DErvuv4pBgVwk4?usp=sharing) and Gemma-2-27b now supported
- 📣 UPDATE! [Phi-3 mini](https://colab.research.google.com/drive/1hhdhBa1j_hsymiW9m-WzxQtgqTH_NHqi?usp=sharing) model updated. [Phi-3 Medium](https://colab.research.google.com/drive/1hhdhBa1j_hsymiW9m-WzxQtgqTH_NHqi?usp=sharing) 2x faster finetuning.
- 📣 NEW! Continued Pretraining [notebook](https://colab.research.google.com/drive/1tEd1FrOXWMnCU9UIvdYhs61tkxdMuKZu?usp=sharing) for other languages like Korean!

## 💎 Model Support
Unsloth reduces memory usage by 80% and speeds up fine-tuning by 2-5x with no loss in accuracy.

Table below shows Unsloth's performance compared to Hugging Face + Flash Attention 2:

| Unsloth supports | Parameters | Performance | Memory use |
|-----------|---------|--------|----------|
| **Llama 3**      | [8B](https://huggingface.co/unsloth/llama-3-8b-Instruct-bnb-4bit)&nbsp;•&nbsp;[70B](https://huggingface.co/unsloth/llama-3-70b-Instruct-bnb-4bit)               | 2x faster | 60% less |
| **Mistral NeMo** | [12B](https://huggingface.co/unsloth/Mistral-Nemo-Instruct-2407-bnb-4bit)             | 2x faster | 60% less |
| **Gemma 2**      | [9B](https://huggingface.co/unsloth/gemma-2-9b-it-bnb-4bit)&nbsp;•&nbsp;[27B](https://huggingface.co/unsloth/gemma-2-27b-it-bnb-4bit)               | 2x faster | 63% less |
| **Phi-3** | [mini](https://huggingface.co/unsloth/Phi-3-mini-4k-instruct-bnb-4bit)&nbsp;•&nbsp;[medium](https://huggingface.co/unsloth/Phi-3-medium-4k-instruct-bnb-4bit)               | 2x faster | 50% less |
| **Mistral v0.3**    | [7B](https://huggingface.co/unsloth/mistral-7b-instruct-v0.3-bnb-4bit)               | 2.2x faster | 73% less |
| **Qwen2**    | [1.5B](https://huggingface.co/unsloth/Qwen2-1.5B-Instruct-bnb-4bit)&nbsp;•&nbsp;[7B](https://huggingface.co/unsloth/Qwen2-7B-Instruct-bnb-4bit)&nbsp;•&nbsp;[72B](https://huggingface.co/unsloth/Qwen2-72B-Instruct-bnb-4bit)               | 2x faster | 60% less |
| **TinyLlama**  | [1.1B](https://huggingface.co/unsloth/tinyllama-chat-bnb-4bit)               | 3.9x faster | 74% less |

## 📚 Info
- Unsloth Studio is powered by [Unsloth's](https://github.com/unslothai/unsloth) training and inference engines.
- Reward Modelling like DPO Zephyr and ORPO are supported.
- Check out [our documentation](https://docs.unsloth.ai/) for guides and a advanced features.
- See our full list of [supported models](https://docs.unsloth.ai/get-started/all-our-models).
- Follow us on [Twitter (aka X)](https://twitter.com/unslothai)
- No change of hardware. Supports NVIDIA GPUs since 2018+.

### 🙏 Special Thanks
- Special thanks to [Sebastien](https://github.com/sebdg) and the Unsloth community for helping out with this project!
