# MimicScribe

**In-Meeting Notetaker / Transcription for macOS.**

MimicScribe is a menu bar app that runs ASR and diarization models on-device and uses a custom train of [NVIDIA Parakeet Ultra]([https://docs.nvidia.com/nemo-framework/user-guide/latest/nemotoolkit/asr/models.html#parakeet](https://github.com/MimicScribe/parakeet-spoken-form)) via CoreML. 

* It builds the final high-quality transcript during the meeting and associates action items with voice labels.
* It uses signals from the Nemotron 3 and PyAnnote Community 1 diarizers to separate speakers. 99% accurate [benchmark.](https://github.com/MimicScribe/benchmarks/blob/main/diarization/results/RESULTS.md)

### Links

- [Website](https://mimicscribe.app) — Download, pricing, and docs
- [Feedback](https://mimicscribe.app/feedback) — Feature requests, bug reports, and changelog
- [YouTube](https://www.youtube.com/@mimicscribe) — Demos and walkthroughs

Requires macOS 15+ and Apple Silicon (M1 or later).
