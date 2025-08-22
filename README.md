🎨 Real-Time Neural Style Transfer with OpenCV
📌 Overview
<img width="1107" height="880" alt="Screenshot 2025-08-22 183122" src="https://github.com/user-attachments/assets/4631785f-12f1-4149-a1c0-79a543c7dbcc" />

This project brings the magic of art and AI together by applying real-time neural style transfer to live webcam video.
Using Johnson’s Fast Neural Style (ECCV16 models) and OpenCV, the program transforms your video stream into masterpieces inspired by legendary artists such as Van Gogh, Monet, Picasso, and more.

With just your webcam, you can step into Starry Night 🌌, La Muse, or The Wave 🌊 — all happening instantly and interactively.

✨ Features

🎥 Live Webcam Feed: Apply artistic styles to your video in real time.

🖼️ Multiple Styles: Includes models like Starry Night, The Wave, La Muse, Composition VII, and more.

⚡ Fast Inference: Powered by fast-neural-style transfer (far quicker than the original optimization-based method).

🎨 Art Meets AI: Experience the brushstrokes, textures, and palettes of iconic painters.

⌨️ Interactive: Switch between different styles with just a key press.

🚀 Installation

Clone the repo:

git clone https://github.com/Mrez2/aura.git
cd aura


Install dependencies:

pip install opencv-python numpy


Download the pre-trained models (ECCV16 .t7 files):

Download ECCV16 Models

Place them inside a folder named models/eccv16/

▶️ Usage

Run the script:

python style_transfer_webcam.py


Controls:

Press 1 → Apply Starry Night

Press 2 → Apply The Wave

Press 3 → Apply La Muse

Press 4 → Apply Composition VII

Press ESC → Exit

🖼️ Example Styles

🌌 Starry Night – Vincent van Gogh

🌊 The Wave – Katsushika Hokusai

🎭 La Muse – Pablo Picasso

🎨 Composition VII – Wassily Kandinsky

📚 How It Works

The project uses Johnson’s fast-neural-style models trained on famous paintings.

Each .t7 model encodes the brushstrokes, texture, and color of an artist’s work.

OpenCV’s DNN module applies the transformation to every frame of the webcam feed in real time.

💡 Future Improvements

Add more artistic styles (Monet, Munch, etc.)

Allow users to load custom styles dynamically

Enhance performance using GPU acceleration

🏆 Acknowledgements

Johnson et al., ECCV16 – Perceptual Losses for Real-Time Style Transfer and Super-Resolution

jcjohnson/fast-neural-style
