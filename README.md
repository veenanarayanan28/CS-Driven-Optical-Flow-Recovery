# CS-Driven-Optical-Flow-Recovery


# 📹 Compressed Sensing for Optical Flow Motion Vector Reconstruction 🚀

## Overview
This project implements a **compressed sensing (CS)** based pipeline to compress and reconstruct **motion vectors** extracted from video sequences using optical flow.  
The goal is to efficiently encode motion information, reconstruct it from compressed measurements, and use it to approximate the next video frame. This technique can reduce data size while maintaining reconstruction quality.

## Features
- 🎥 Video input processing with OpenCV  
- 🌊 Dense optical flow extraction (Farneback method)  
- 📐 Block-based Discrete Cosine Transform (DCT) for sparsifying motion vectors  
- ⚡ Compressive sensing encoding with Gaussian random matrices  
- 🧩 Sparse recovery using Orthogonal Matching Pursuit (OMP)  
- 🎞 Frame reconstruction from compressed motion vectors  
- 📊 Evaluation using PSNR, SSIM, End-Point Error (EPE), and Angular Error  
- 🖼 Visualization of optical flow and reconstruction quality


## Dependencies
- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- scikit-learn  
- joblib  
- matplotlib  
- scikit-image  


## Acknowledgements
Video sample from [Big Buck Bunny](https://test-videos.co.uk/bigbuckbunny/mp4-h264).

---

---

**Feel free to ⭐ star the repo and contribute!**  
