# GIF-with-Python

## 🎞️ Create a GIF from Images
<p>This Python script creates an animated GIF from a list of images using the imageio library.</p>

## 📚 Concept:
A GIF (Graphics Interchange Format) is a bitmap image format that supports both static and animated images. An animated GIF is essentially a sequence of images (frames) that are displayed in order, creating the illusion of motion.

Python, with libraries like imageio, makes it easy to read a series of images and combine them into a single animated GIF file.

## 🧰 Tools Used:
Python: A versatile programming language.

ImageIO (imageio): A Python library for reading and writing images in various formats, including GIF.

## ⚙️ How It Works:
Import Library: Use imageio.v2 to maintain compatibility and avoid deprecation warnings.

Load Images: Read individual image files (PNG, JPG, etc.) into a list using imageio.imread.

Validate Images: Ensure each image is either grayscale (2D) or color (3D with RGB/RGBA channels).

Create GIF: Use imageio.mimsave to compile the list of images into an animated GIF.

Control Speed: The duration parameter specifies how long each frame is displayed.

## 🔄 Animation Parameters:
duration: Time (in seconds) to display each frame.

loop: Number of times the GIF should repeat (0 means infinite loop).
