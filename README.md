# Image & Video Redaction using Computer Vision

This project provides Jupyter notebooks for redacting (blurring) sensitive information such as faces and license plates in images and videos using deep learning models (MTCNN and YOLOv8).

## Features

- **Face detection and blurring** using MTCNN and YOLOv8.
- **License plate and object blurring** using YOLOv8.
- Supports both **image** and **video** files.
- Designed for use in Google Colab.

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries:
  - facenet-pytorch
  - Pillow
  - torch, torchvision, torchaudio
  - opencv-python-headless
  - ultralytics
  - numpy
  - matplotlib

All dependencies are installed automatically in the first notebook cells.

## Usage

1. **Open `REdact_for_Image_and_Video.ipynb` in Google Colab or Jupyter Notebook.**
2. **Run the first cells to install dependencies.**
3. **Follow the notebook instructions to upload your image or video.**
4. **Choose whether to process an image or video.**
5. **The notebook will display or download the redacted output.**

## Notebooks

- `REdact_for_Image_and_Video.ipynb`: Main notebook for both image and video redaction.
- `image_redact.ipynb`: Example for image redaction only.

## Example

- Upload an image or video when prompted.
- The notebook will detect faces and/or license plates and blur them.
- The processed file will be displayed or made available for download.

## License

This project is for educational and research purposes.