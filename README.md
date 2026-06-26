# OpenCV Pipeline

OpenCV-based image processing pipeline with reusable transformation functions.

## Objectives

1. Build an OpenCV-based image processing pipeline for core computer vision operations — reading, writing, and transforming images.
2. Implement geometric transformations — rotation, mirroring, and directional cropping — for spatial image manipulation.
3. Develop grid-based segmentation (4, 8, and 16-cell grids) to simulate partitioning visual data for distributed processing.
4. Apply compression and color-space conversion (grayscale/binary) to optimize storage and processing efficiency.
5. Package all operations as reusable functions in a modular Colab notebook, usable as a backend utility for big data analytics applications.

## What's Inside

- **Image Compression** — reduce file size while saving processed output
- **Rotation** — +90°, +180°, +270° and -90°, -180°, -270°
- **Mirroring** — horizontal flip of the original image
- **Cropping** — vertical (50%, left 30%, right 30%) and horizontal (50%, top 30%, bottom 30%) cuts
- **Grid Segmentation** — 4-grid, 8-grid, and 16-grid overlays
- **Color Conversion** — grayscale and black & white (binary)
- **Framing** — adds a border frame to the image

## Tech Stack

- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Conclusion

This project implements a modular image processing pipeline using OpenCV, covering compression, geometric transformations, directional cropping, grid-based segmentation, color-space conversion, and framing. Built as reusable functions, the pipeline demonstrates practical computer vision fundamentals and lays the groundwork for scaling these techniques into larger big data analytics workflows that process visual data at volume.

## How to Run

1. Open the notebook in Google Colab
2. Run each cell sequentially
3. Upload your own image when prompted in Cell 2
4. All outputs are saved to the `outputs/` folder
