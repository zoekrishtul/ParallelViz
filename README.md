# ParallelViz
A simple high-performance Rust implementation of the Fast Fourier Transform (FFT) for audio spectral analysis.

ParallelViz takes a `.wav` audio file, processes it using a parallelized FFT pipeline, and outputs the transformed frequency-domain representation.

---

## 🔧 Compile
```bash
cargo build --release

▶️ Run
cargo run -- audio/<filename>.wav

🎵 Converting .mp3 → .wav (using ffmpeg)
If your audio file is not already a .wav, you can convert it with: ffmpeg -i <input>.mp3 <output>.wav
