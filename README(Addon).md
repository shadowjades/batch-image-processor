# Wanling Image Renamer (Addon)

A lightweight **supplemental tool** for the [Batch Image Processor](https://github.com/shadowjades/batch-image-processor), designed to rename processed images in a consistent numeric format.

## 🔧 Features

- Select a folder containing images  
- Specify how many digits for renaming (e.g., `5` → `00001.jpg`)  
- Auto-renames all images in order  
- Retains original image formats (no compression or format conversion)  
- Simple PyQt5 GUI  
- Window title: **"万灵药图片修改器（补充包）"**

Supported formats: `JPG`, `JPEG`, `PNG`, `BMP`, `TIF`, `TIFF`, `WEBP`

## 🖥 Preview

A clean interface with:
- A digit input box to specify rename pattern length  
- A folder picker to select the image directory  
- An instruction label explaining the tool's purpose  

## 📦 Executable Download

Download the packaged version here:  
👉 [万灵药图片修改器（命名补充包）.exe (Google Drive)](https://drive.google.com/file/d/1jo41EffkhKdFat4rRzR8kZq93oYBrY15/view?usp=sharing)

- No installation required  
- No console window  
- Executable icon: `app_icon.ico`  

## 🛠 For Developers

To run from source:

```bash
pip install pyqt5
python image_renamer.py
