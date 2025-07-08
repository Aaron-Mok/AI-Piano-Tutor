# AI Piano Tutor – Real-Time Key and Note Detection

This project uses computer vision and audio processing to assist beginner pianists in learning to sight-read. It maps sheet music to real piano key positions in real time using a webcam and microphone.

## Demo

🎥 [Single Note Demo](https://youtu.be/ToxRqkAhbZA)
🎥 [Chord Detection Demo](https://youtu.be/fyLVFQRLTO8)

## How it Works

- Uses YOLOv8 and segmentation technique to detect 52 piano keys from a webcam feed.
- Maps each note from sheet music to a key position.
- Converts microphone input to a spectrogram via FFT and identifies played notes.
- Only advances the score when the correct note or chord is played.

## Technologies

- Python, OpenCV, MediaPipe, YOLOv8, PyTorch
- music21 (sheet music parsing)
- FFT (audio frequency analysis)

## Try It Yourself

Instructions coming soon.

## Blog

Full write-up: [https://aaron-mok.github.io/blog/pianokeydetection](https://aaron-mok.github.io/blog/pianokeydetection)

⚠️ This project is released under the MIT License for personal and educational use only. Commercial use is prohibited. Please contact me if you're interested in licensing.