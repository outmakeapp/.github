<img src="https://outmake.app/press/logos/app-icon-1024.png" width="96" alt="Outmake app icon">

# Outmake

**Run local AI models on your Mac.** Outmake is a free, privacy-focused macOS app for running open AI models on Apple silicon Macs. It downloads models from Hugging Face and Civitai with one click, checks each one against the Mac's memory before anything downloads, and runs it on the Mac itself once it is downloaded. There is no Outmake account, no advertising and nothing that identifies you.

**[Download at outmake.app](https://outmake.app)** · Apple silicon (M1 or later), macOS 26 or later, 8 GB of memory or more

```sh
brew install --cask outmakeapp/tap/outmake
```

## What it runs

| Kind | Models and engines |
|---|---|
| **Chat** | Open models in GGUF format on llama.cpp with Metal, including the Qwen, Gemma, DeepSeek, Kimi and MiniMax families. The Models catalog lists 4,200+ models and every published size of each, marked Runs great, Runs well or Too big for that Mac. |
| **Pictures** | stable-diffusion.cpp runs Stable Diffusion 1.5, SDXL, Pony, Illustrious, FLUX.1, FLUX.1 Krea, FLUX.2, FLUX.2 klein, Chroma, Z-Image, Qwen-Image, Anima and Krea 2, plus thousands of community styles (LoRAs) from Civitai. FLUX.2 and FLUX.2 klein also edit pictures. |
| **Video** | Wan 2.1, Wan 2.2 (text to video and picture to video) and LTX-Video. |
| **Voices** | Qwen3-TTS speaks in Chinese, English, Japanese, Korean, German and French. Kokoro, Kitten, Piper, Supertonic and Pocket TTS run on sherpa-onnx and MLX, and ElevenLabs works with your own key. One set of cues (a laugh, a whisper, a pause) works across every voice. |
| **Dictation** | Hold the right Option key and speak; the words are typed where the cursor is, in any app. You can talk to it in 100+ languages. |

## Which models run on your Mac

Every model on [outmake.app/models](https://outmake.app/models) says whether it fits your Mac, the size to get and how fast it runs. There is a page for each Mac: [M1 with 8 GB](https://outmake.app/macs/m1-8gb), [M2 with 16 GB](https://outmake.app/macs/m2-16gb), [M4 with 16 GB](https://outmake.app/macs/m4-16gb), [M4 Pro with 24 GB](https://outmake.app/macs/m4-pro-24gb), [M3 Max with 64 GB](https://outmake.app/macs/m3-max-64gb) and [every other Mac](https://outmake.app/macs).

## Measured on a MacBook Pro with M1 Pro and 16 GB

- Speculative decoding took a code edit from 30.5 to 69.1 words a second.
- Wan 2.2 14B made a two-second clip in 12 minutes.
- Background removal with Apple's Vision takes 0.33 s.

## Also in the app

- **Studio tools:** upscaling with MetalFX, a detail upscaler, storyboards with a narration voice, and full control of steps, guidance, sampler, scheduler, size and seed, saved as presets.
- **Outmake Bench** ranks local models for each Mac by quality and speed.
- **Bring your own plan:** chat with Claude, ChatGPT, Gemini and OpenCode through the plan or key you already pay for, at no extra charge.
- A browser in each chat, one memory shared by every agent, Passwords sealed with Touch ID, and ⌘K search across everything.
- **Native:** 166,000 lines of Swift, no Electron, 134 MB installed, and it lives in the Mac's notch.
- **Private by design:** a model on the Mac can't open files, run commands or go online. The chat engine listens only on 127.0.0.1 with a key made at each launch, API keys stay in the macOS Keychain, and Outmake asks before anything goes to a cloud company.

Free public beta (0.6, 22 Oct 2026). Watch the [launch film](https://outmake.app/media/film.mp4).

[Release notes](https://outmake.app/releases) · [Help](https://outmake.app/help) · [Press kit](https://outmake.app/press) · [Privacy](https://outmake.app/privacy)

[X](https://x.com/outmakeapp) · [Threads](https://www.threads.net/@outmakeapp) · [Instagram](https://www.instagram.com/outmakeapp) · [Bluesky](https://bsky.app/profile/outmake.bsky.social) · [YouTube](https://www.youtube.com/@outmake) · [LinkedIn](https://www.linkedin.com/company/outmake) · [Hugging Face](https://huggingface.co/outmake)

Made by [Ambedo Labs](https://ambedo.dev) in Utah, USA. Questions: hello@outmake.app
