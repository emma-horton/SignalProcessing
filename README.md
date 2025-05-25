# Spectral Filtering and Visual Segmentation using MATLAB

This project showcases the use of MATLAB for audio signal processing and image analysis. It includes scripts for filtering background noise from audio recordings and performing basic image operations such as color segmentation using k-means clustering and edge detection.

## Features

- Audio signal filtering using Fast Fourier Transform (FFT)
- Background noise identification and removal
- Image segmentation with k-means color clustering
- Edge detection and grayscale conversion
- Frequency domain analysis

## Project Structure
``` bash
├── AudioProcessing/      # MATLAB scripts for filtering noisy audio signals
├── ImageAnalysis/        # Image segmentation and edge detection scripts
├── Report/               # Summary report of methodology and results
```

## Audio Processing

Three audio files were analyzed, each with the same signal of interest but different background noise types. The goal was to identify and filter out the noise frequencies.

### Process

1. **Fourier Analysis**: FFT was used to visualize frequency components.
2. **Noise Frequencies Identified**:
   - **Audio 1**: 600 Hz
   - **Audio 2**: 150 Hz
   - **Audio 3**: 250 Hz and 900 Hz
3. **Filtering**: Custom band-stop filters were applied to remove the identified frequencies.

### Results

- Clear reduction of background noise in all three cases
- Retained integrity of the original signal
- FFT plots confirmed the removal of targeted frequencies

## Image Analysis

Image processing focused on enhancing and segmenting images using color and edge-based methods.

### Techniques Used

- **K-means Color Clustering**: Used to segment images into distinct regions based on color similarity.
- **Grayscale Conversion**: To simplify processing.
- **Edge Detection**: Techniques such as Sobel and Canny were applied to extract edge structures.

### Results

- Effective separation of image regions by dominant colors
- Accurate edge detection around key image features
- Demonstrated contrast between clustered color segments and grayscale/edge versions


## Learnings & Reflections

- Gained practical experience working in both the time and frequency domains.
- Explored the use of unsupervised learning (k-means) for visual data.
- Improved MATLAB proficiency for signal/image processing tasks.

## How to Run

1. Open MATLAB.
2. Navigate to the desired script directory (`AudioProcessing/` or `ImageAnalysis/`).
3. Run the `.m` scripts directly or use `live scripts` for interactive analysis.

## Feedback

Feel free to open issues or submit pull requests for improvements!
