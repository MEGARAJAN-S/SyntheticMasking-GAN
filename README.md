# FaceMask-GAN 🧠😷

A deep learning project that uses **Generative Adversarial Networks (GANs)** to perform synthetic face masking on human face images. This project is built using Python and trained using a custom GAN architecture to apply realistic-looking face masks to images.

## 🧪 Project Overview

This project explores the use of GANs to generate masked versions of facial images, which can be used for dataset augmentation or privacy-preserving applications. The generator learns to apply a synthetic face mask while the discriminator attempts to distinguish between real and generated masked images.

## 📂 Repository Structure
```bash
FaceMask-GAN/

├── gan.ipynb                  # Main training notebook

├── saved_models/              # Saved models of the generator and discriminator

│   ├── generator.pth

│   └── discriminator.pth

├── output/

│   ├── epoch_scores.png       # Epoch vs score graph

│   ├── loss_graph.png         # Generator & Discriminator loss graph

│   ├── video.avi              # Video combining output images

│   └── output_images/         # Generated images at key training steps

│       ├── epoch_001.png

│       ├── epoch_010.png

│       ├── ...

│       └── epoch_200.png

```
## 📊 Results

- Visualizations of output at key training epochs: **1, 10, 25, ..., 200**
- Video showing the gradual improvement in the generated face masks
- Generator and Discriminator loss graphs showing convergence behavior
- Epoch vs Discriminator Score plot

## 💡 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/FaceMask-GAN.git
    cd FaceMask-GAN
    ```

2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook gan.ipynb
    ```

3. (Optional) View the outputs in the `output/` folder or play the video to see progress.

## 🧰 Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib
- OpenCV
- Jupyter Notebook

## 🧠 GAN Architecture

- **Generator**: Takes input noise and generates masked faces.
- **Discriminator**: Classifies real vs. generated images.
- Trained adversarially to improve realism of generated masks.

## 🎥 Sample Output Video

> 📽️ Located at `output/generator-images.avi` — shows progress from epoch 1 to 200.

## 📌 Future Improvements

- Add conditional GANs to apply different types of masks
- Improve image resolution and realism
- Integrate real-world datasets for testing

## 🙋‍♂️ Author

**Megarajan S.**  
Final year Computer Science student 
---

⭐ Feel free to star this repo if you found it useful! Contributions and feedback are welcome.

