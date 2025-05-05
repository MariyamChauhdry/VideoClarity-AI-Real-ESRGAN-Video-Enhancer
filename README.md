# VideoClarity AI-Real-ESRGAN-Video-Enhancer
A deep learning-based video enhancement tool that transforms low-resolution or blurry videos into sharper, high-quality outputs using the Real-ESRGAN model. This project leverages frame-by-frame super-resolution on Google Colab, making it easy to run without any local setup.

## Features
- Enhances video clarity using AI-based super-resolution
- Extracts video frames with ffmpeg
- Upscales each frame using Real-ESRGAN
- Reconstructs a high-resolution video from enhanced frames
- Runs entirely in Google Colab — no installation required

## Demo Videos

▶️ **Input Video**  
[Download/View Input](InputVideo.mp4)

▶️ **Enhanced Output Video**  
[Download/View Output](OutputVideo.mp4)

---

## How It Works

1. **Upload your video** (`.mp4`) to the project
2. **Extract frames** using `ffmpeg`
3. **Enhance frames** using Real-ESRGAN (`inference_realesrgan.py`)
4. **Rebuild video** with `ffmpeg` from enhanced frames
5. **Display output** using embedded video player in Colab

---

## Tech Stack

| Component        | Technology            |
|------------------|------------------------|
| Language         | Python                 |
| Model            | Real-ESRGAN            |
| Video Handling   | ffmpeg, OpenCV         |
| Platform         | Google Colab           |
| Visualization    | IPython / HTML Video   |

---

## Author

Built by **Mariyam Chauhdry** – AI Engineer  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/mariyam-chauhdry-592231270)

