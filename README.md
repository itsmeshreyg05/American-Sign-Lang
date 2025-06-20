# American Sign Language (ASL) Image Classification

This project demonstrates how to classify American Sign Language hand gesture images using a Convolutional Neural Network (CNN) in Python with TensorFlow/Keras.

## Dataset Structure
- `Dataset/asl_dataset/` contains folders for each class (A-Z, 0-9), each with hand gesture images in JPEG format.

## Project Structure
- `ASL_Image_Classification.ipynb`: Main notebook for data loading, visualization, model building, training, and evaluation.
- `Dataset/`: Contains the ASL image dataset.

## How to Run
1. Install requirements:
   ```sh
   pip install tensorflow numpy matplotlib scikit-learn pillow
   ```
2. Open `ASL_Image_Classification.ipynb` in Jupyter or VS Code.
3. Run all cells to:
   - Visualize sample images
   - Preprocess and split the data
   - Build and train a CNN
   - Evaluate and visualize results

## Example Results
- The notebook will show training/validation accuracy and loss plots.
- It will display predictions vs. true labels for sample test images.

## Customization
- You can change the CNN architecture or training parameters in the notebook.
- Try different image sizes, batch sizes, or more advanced models for better accuracy.

## License
MIT (or specify your license)
