# CUDA_Image_Blur_LodePNG

Essential external library files required for CUDA-accelerated image processing.

## Files in This Repository

* **`lodepng.h`**: The header file for the LodePNG library.
* **`lodepng.cpp`**: The complete C++ implementation of the LodePNG library.

## Usage in CUDA/Colab

To use these files in a CUDA C++ project (`.cu` file), place them in the same directory as your main code and compile using:

```bash
# Example compilation command for your main CUDA file:
nvcc your_main_file.cu lodepng.cpp -o your_executable -std=c++11