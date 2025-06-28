# ComfyUI-Image-Matting

A ComfyUI extension for image matting using pretrained AI models. This extension allows you to extract precise foreground objects from images by leveraging trimaps that guide the matting process.

## ✨ Features

- 🧠 Uses state-of-the-art pretrained AI matting models
- 🎨 Accepts custom trimaps for fine control over the matting process
- 🖼️ Outputs high-quality alpha mattes and foreground extractions
- 🔌 Seamlessly integrates into ComfyUI as a custom node

## 📦 Installation

Install using **ComfyUI Manager**:

1. Open ComfyUI.
2. Go to the **Manager** tab.
3. Search for `Image Matting` or install via URL
4. Click **Install** and restart ComfyUI.

## 🤝 Contributions

Contributions, bug reports, and suggestions are welcome! Open a pull request or file an issue on [GitHub Issues](https://github.com/Aperolka-AI/ComfyUI-Image-Matting/issues).

## 📄 License

This project is licensed under the MIT License.

## Example Workflow
![image matting](https://github.com/hackkhai/ComfyUI-Image-Matting/blob/master/image_matting.png)

[Download the sample workflow](https://github.com/hackkhai/ComfyUI-Image-Matting/blob/master/image_matting.json)

## Nodes

### MattingModelLoader
Load one of the four supported matting models (download automatically if necessary)

### Create Trimap
Create Trimap with the provided mask

### Apply Matting
Extract the foreground object

## ✨ Credits

**Original Author:** [hackkhai](https://github.com/hackkhai)
**Original Repo:** [ComfyUI-Image-Matting](https://github.com/hackkhai/ComfyUI-Image-Matting)
