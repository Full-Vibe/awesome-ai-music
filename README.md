# Awesome AI Music [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub Stars](https://img.shields.io/github/stars/Full-Vibe/awesome-ai-music?style=flat&logo=github)](https://github.com/Full-Vibe/awesome-ai-music/stargazers) [![GitHub Last Commit](https://img.shields.io/github/last-commit/Full-Vibe/awesome-ai-music?style=flat)](https://github.com/Full-Vibe/awesome-ai-music/commits) [![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Full-Vibe/awesome-ai-music/pulls)

> A curated list of AI music generation tools, SDKs, models, focus music apps, and resources.

We're builders in this space — [workmusic.ai](https://workmusic.ai) is a free browser-based AI focus music app powered by Google Lyria. We built this list because we use these tools every day and wanted one place to track everything happening in AI music. Contributions welcome.

---

## Contents

- [Generation Platforms](#-generation-platforms)
- [Focus & Productivity Music](#-focus--productivity-music)
- [Open Source Models & Libraries](#-open-source-models--libraries)
- [Developer SDKs & Tools](#-developer-sdks--tools)
- [Audio Analysis & MIR](#-audio-analysis--mir)
- [Composition & Arrangement](#-composition--arrangement)
- [Voice & Vocals](#-voice--vocals)
- [Sound Design & SFX](#-sound-design--sfx)
- [Web Audio & Browser](#-web-audio--browser)
- [Research Papers](#-research-papers)
- [Communities](#-communities)
- [Contributing](#contributing)

---

## 🎵 Generation Platforms

Full-featured platforms for creating music with AI.

- **[Suno](https://suno.com)** — Full song generation with vocals, lyrics, and instrumentals from text prompts. The most popular AI music generator. `freemium`
- **[Udio](https://www.udio.com)** — High-quality AI music generation with fine-grained control over style, structure, and arrangement. `freemium`
- **[AIVA](https://www.aiva.ai)** — AI composer specializing in orchestral, cinematic, and classical music. Used in film and game scoring. `freemium`
- **[Soundraw](https://soundraw.io)** — AI music generator focused on customizable background tracks for content creators. Royalty-free. `paid`
- **[Mubert](https://mubert.com)** — Real-time adaptive AI music streams. Good for apps, games, and content that needs dynamic soundtracks. `freemium`
- **[Beatoven.ai](https://www.beatoven.ai)** — AI music tailored for video and podcast creators. Mood-based generation with scene alignment. `freemium`
- **[Soundful](https://soundful.com)** — Template-driven AI music generation for producers and content creators. `freemium`
- **[Boomy](https://boomy.com)** — Create and distribute AI-generated songs to streaming platforms. Anyone can make a song in seconds. `freemium`
- **[Mureka](https://www.mureka.ai)** — AI songwriting assistant with vocal generation, lyric writing, and melody composition. `freemium`
- **[Wondera](https://www.wondera.ai)** — AI music creation platform with style transfer and multi-track editing. `freemium`
- **[Stable Audio](https://www.stableaudio.com)** — Stability AI's music and sound generation platform. High-quality, long-form audio. `freemium`
- **[Google MusicFX](https://aitestkitchen.withgoogle.com/tools/music-fx)** — Google's experimental AI music generator powered by DeepMind's Lyria model. `free`

## 🎧 Focus & Productivity Music

AI-powered music specifically designed to help you concentrate, relax, or sleep.

- **[workmusic.ai](https://workmusic.ai)** — Free browser-based ambient work music generator. No account needed — just open and focus. AI-generated via Google Lyria. `free` `open source`
- **[Brain.fm](https://www.brain.fm)** — Science-backed focus music using patented neural phase locking technology. The gold standard for focus music. `paid` ($7/mo)
- **[Endel](https://endel.io)** — AI-powered soundscapes that adapt to time of day, weather, heart rate (Apple Watch), and location. Beautiful design. `paid`
- **[Focus@Will](https://www.focusatwill.com)** — Neuroscience-based music channels optimized for sustained attention. Research-backed. `paid`
- **[Noisli](https://www.noisli.com)** — Customizable ambient sound mixer. Not AI-generated music per se, but a staple in the focus sound space. `freemium`
- **[myNoise](https://mynoise.net)** — Calibrated noise generators and soundscapes. Incredibly deep customization. Made by a signal processing PhD. `free` (donations)
- **[Calm](https://www.calm.com)** — Meditation and sleep app with curated music and soundscapes. More wellness than productivity. `paid`
- **[LifeAt](https://lifeat.io)** — Virtual study/work spaces with ambient music and productivity tools. `freemium`

## 🔬 Open Source Models & Libraries

Self-hostable models and research code for AI music generation.

- **[AudioCraft](https://github.com/facebookresearch/audiocraft)** — Meta's library for audio generation. Includes MusicGen, AudioGen, and EnCodec. The foundation of most open-source AI music work. ⭐ 17k+ stars
- **[MusicGen](https://huggingface.co/facebook/musicgen-large)** — Meta's controllable music generation model. Text and melody conditioning. Available on HuggingFace in small/medium/large variants.
- **[Magenta](https://github.com/magenta/magenta)** — Google's research project exploring ML for music and art generation. Built on TensorFlow. Includes NSynth, MusicVAE, and more. ⭐ 19k+ stars
- **[Magenta.js](https://github.com/magenta/magenta-js)** — JavaScript/TypeScript port of Magenta for browser-based music generation and interaction.
- **[Riffusion](https://github.com/riffusion/riffusion)** — Generates music by creating spectrograms with Stable Diffusion, then converting to audio. Creative and novel approach.
- **[AudioLDM](https://github.com/haoheliu/AudioLDM)** — Text-to-audio generation using latent diffusion. Can generate music, speech, and sound effects.
- **[AudioLDM 2](https://github.com/haoheliu/AudioLDM2)** — Improved version with better quality and longer generation. Unified model for speech, music, and sound.
- **[Jukebox](https://github.com/openai/jukebox)** — OpenAI's neural net that generates music with vocals in raw audio. Groundbreaking but compute-heavy. ⭐ 8k+ stars
- **[MusicLM](https://google-research.github.io/seanet/musiclm/examples/)** — Google's text-to-music model (research only, not open-sourced, but examples available).
- **[Bark](https://github.com/suno-ai/bark)** — Suno's open-source text-to-audio model. Generates speech, music, and sound effects. ⭐ 37k+ stars
- **[Demucs](https://github.com/adefossez/demucs)** — Meta's music source separation model. Splits songs into vocals, drums, bass, and other stems. Essential for remixing. ⭐ 8k+ stars

## 🔧 Developer SDKs & Tools

- **[Cadence Music](https://music.rynn.me)** — Free AI song generator in the browser: describe a gift or paste lyrics → full song with vocals. 4 free/day, no watermark; Keep $1.99.

Libraries and tools for building music-powered applications.

- **[Tone.js](https://tonejs.github.io/)** — Web Audio framework for creating interactive music in the browser. The standard for browser-based music apps. ⭐ 13k+ stars `open source`
- **[Tonal](https://github.com/tonaljs/tonal)** — Music theory library for JavaScript. Chords, scales, intervals, keys — everything you need for algorithmic composition. `open source`
- **[music21](https://github.com/cuthbertLab/music21)** — Python toolkit for computational musicology. MIDI processing, score analysis, music theory. From MIT. `open source`
- **[Mido](https://github.com/mido/mido)** — Python library for working with MIDI messages and files. Simple and reliable. `open source`
- **[FluidSynth](https://www.fluidsynth.org/)** — Real-time software synthesizer based on SoundFont. Cross-platform, used in many music apps. `open source`
- **[pretty-midi](https://github.com/craffel/pretty-midi)** — Python library for manipulating and analyzing MIDI data. Great for ML pipelines. `open source`
- **[Suno API (Unofficial)](https://github.com/gcui-art/suno-api)** — Reverse-engineered API client for Suno. Use Suno's generation capabilities programmatically. `open source`
- **[RunAPI Suno SDK](https://github.com/runapi-ai/suno-sdk)** — SDK for Suno text-to-music, cover audio, music extension, stem separation, custom voice, and related audio workflows. `open source`

## 📊 Audio Analysis & MIR

Music Information Retrieval — analyze, classify, and understand audio.

- **[librosa](https://librosa.org/)** — The standard Python library for audio analysis. Feature extraction, visualization, effects. If you're doing ML on audio, you're using librosa. ⭐ 7k+ stars `open source`
- **[Essentia](https://essentia.upf.edu/)** — C++/Python library for audio analysis and music description. Industrial-strength MIR. From UPF Barcelona. `open source`
- **[Spotify Web API](https://developer.spotify.com/documentation/web-api/reference/get-audio-features)** — Audio features endpoint returns danceability, energy, valence, tempo, and more for any Spotify track. `free`
- **[Madmom](https://github.com/CPJKU/madmom)** — Python audio signal processing library focused on MIR. Beat tracking, onset detection, chord recognition. `open source`
- **[Sonic Visualiser](https://www.sonicvisualiser.org/)** — Desktop app for viewing and analyzing audio files. Plugin-based architecture for custom analysis. `open source`
- **[aubio](https://aubio.org/)** — C library for audio labelling. Pitch detection, onset detection, beat tracking. Fast and lightweight. `open source`

## 🎹 Composition & Arrangement

AI tools that help with songwriting, arranging, and music theory.

- **[ACE Studio](https://www.acestudio.ai/)** — AI vocal synthesizer for realistic singing voice generation. Popular in Asian music production. `freemium`
- **[Hookpad](https://www.hooktheory.com/hookpad)** — Intelligent songwriting tool with chord suggestion, melody guides, and music theory integration. `paid`
- **[Orb Composer](https://www.orb-composer.com/)** — AI-assisted orchestral composition. Helps arrange for full ensembles. `paid`
- **[Amper Music](https://www.shutterstock.com/discover/amper)** — AI composition tool (now part of Shutterstock). Generate custom music for media projects. `paid`

## 🎤 Voice & Vocals

AI tools for voice generation, cloning, and vocal processing.

- **[Musicfy](https://musicfy.lol/)** — AI voice cloning for music. Sing in anyone's voice style (with ethical considerations). `freemium`
- **[VITS](https://github.com/jaywalnut310/vits)** — End-to-end text-to-speech model that can be adapted for singing voice synthesis. `open source`
- **[So-VITS-SVC](https://github.com/svc-develop-team/so-vits-svc)** — Singing voice conversion using VITS. Clone singing voices with relatively small datasets. `open source`
- **[RVC (Retrieval-based Voice Conversion)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)** — Real-time voice conversion. Widely used in the AI music community. ⭐ 25k+ stars `open source`
- **[Uberduck](https://uberduck.ai/)** — AI voice and rap generation. Text-to-speech with musical styles. `freemium`
- **[voicetoinstrument.com](https://voicetoinstrument.com)** — Convert voice to instrumental tracks using AI. Extract vocals from any audio and replace with AI-generated instruments. `freemium`

## 🔊 Sound Design & SFX

AI tools for generating sound effects, ambient textures, and audio processing.

- **[ElevenLabs Sound Effects](https://elevenlabs.io/sound-effects)** — Generate sound effects from text descriptions. High quality. `freemium`
- **[AudioGen](https://github.com/facebookresearch/audiocraft)** — Meta's text-to-sound model (part of AudioCraft). Generates environmental sounds and effects. `open source`
- **[Freesound](https://freesound.org/)** — Collaborative database of Creative Commons licensed sounds. Not AI, but essential for any audio project. `free`

## 🌐 Web Audio & Browser

Tools for building music experiences that run in the browser.

- **[Tone.js](https://tonejs.github.io/)** — (Also listed above) Web Audio framework. Synths, effects, scheduling, transport. `open source`
- **[Howler.js](https://howlerjs.com/)** — Audio library for the modern web. Makes Web Audio and HTML5 Audio simple and reliable. ⭐ 24k+ stars `open source`
- **[Pizzicato.js](https://alemangui.github.io/pizzicato/)** — Web Audio library focused on simplicity. Create and manipulate sounds with minimal code. `open source`
- **[Wavesurfer.js](https://wavesurfer.xyz/)** — Audio waveform visualization for the browser. Interactive, customizable, widely used. ⭐ 9k+ stars `open source`
- **[RNBO](https://rnbo.cycling74.com/)** — Export Max/MSP patches to Web Audio, VST, and more. Bridge between visual programming and web deployment. `paid`

## 📄 Research Papers

Key papers that shaped the field.

- **[MusicLM: Generating Music From Text](https://arxiv.org/abs/2301.11325)** (2023) — Google's text-to-music model. Hierarchical sequence-to-sequence approach.
- **[MusicGen: Simple and Controllable Music Generation](https://arxiv.org/abs/2306.05284)** (2023) — Meta's single-stage transformer for music generation. The basis of AudioCraft.
- **[Jukebox: A Generative Model for Music](https://arxiv.org/abs/2005.00341)** (2020) — OpenAI. Raw audio generation with VQ-VAE, including vocals.
- **[Riffusion: Stable Diffusion for Real-Time Music Generation](https://arxiv.org/abs/2401.14045)** (2022) — Novel spectrogram-based approach using image diffusion.
- **[AudioLDM: Text-to-Audio Generation with Latent Diffusion Models](https://arxiv.org/abs/2301.12503)** (2023) — Latent diffusion for general audio, including music.
- **[Neural Audio Synthesis of Musical Notes with WaveNet Autoencoders](https://arxiv.org/abs/1704.01279)** (2017) — Google Magenta's NSynth. Foundational work on neural audio synthesis.
- **[Music Transformer: Generating Music with Long-Term Structure](https://arxiv.org/abs/1809.04281)** (2018) — Google Brain. Attention-based music generation with relative positional encoding.
- **[MuseNet](https://openai.com/index/musenet/)** (2019) — OpenAI's deep neural network that generates 4-minute musical compositions with 10 instruments.
- **[The Science Behind Brain.fm](https://www.brain.fm/science)** — Research on neural phase locking and how modulated music affects focus. Relevant to anyone building focus music tools.

## 💬 Communities

Where people talk about AI music.

- **[r/AIMusic](https://www.reddit.com/r/AIMusic/)** — Reddit community for AI-generated music discussion
- **[r/SunoAI](https://www.reddit.com/r/SunoAI/)** — Suno-focused community, but lots of general AI music discussion
- **[AI Music Discord](https://discord.gg/aimusic)** — Active Discord for AI music creators
- **[Magenta Discuss](https://groups.google.com/g/magenta-discuss)** — Google Magenta's discussion group
- **[HuggingFace Audio](https://huggingface.co/spaces?search=music)** — Browse and try music models on HuggingFace Spaces

---

## Contributing

Found something we're missing? [Open a PR](https://github.com/Full-Vibe/awesome-ai-music/pulls) or [open an issue](https://github.com/Full-Vibe/awesome-ai-music/issues).

Please include:
- Name and link
- One-line description of what it does
- Whether it's free, paid, freemium, or open source

## About

Maintained by [FullVibeAI](https://fullvibe.ai), the team behind [workmusic.ai](https://workmusic.ai) — free AI-powered focus music in your browser.

We built this list because we use these tools every day and wanted a single reference. If it helps you too, that's the whole point.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is public domain. Use it however you want.
