# **Uncovering the Hidden Treasures of the Mushroom Kingdom: A Classification Analysis**

## **Project Description**
- This project centers on identifying and classifying various mushroom species found across different global regions. The classification process relies on mushroom images, utilizing deep learning techniques to achieve high accuracy in species identification.

- Leveraging transfer learning and advanced neural network models, the system is designed to categorize mushrooms into three primary groups: Boletus, Lactarius, and Russula. These categories encompass distinct mushroom types observed in diverse ecosystems. The key goal is to build a dependable and efficient visual classification model for accurate mushroom species detection..

## **Screenshots**

### Home Page:
<p align="center">
 <img src="https://drive.google.com/file/d/1J6RCnaPjyTbKveSC6_p9_UH30sp8_uh8/view?usp=drivesdk" width="800" height="auto" alt="Your Image Description">

</p>

### Mushroom Classification Result:
<p align="center">
 <img src="https://drive.google.com/file/d/1J8czBIhMOhXhBVp3QK9g7TNq3lNXgCg6/view?usp=drivesdk" width="800" height="auto" alt="Classification Results Display">
</p>

## **Installation and Setup**

### Using Conda (Recommended)

```bash
# Create a new conda environment
conda create -n mushroom_classifier python=3.10

# Activate the environment
conda activate mushroom_classifier

# Clone the repository
git clone https://github.com/Rohitmh09/AI-Mushroom-Classification-Analysis.git
cd AI-Mushroom-Classification-Analysis-master

# Install dependencies
pip install -r requirements.txt
```

### Using Python venv

```bash
# Create a virtual environment
python -m venv mushroom_env

# Activate the environment
# On Windows:
mushroom_env\Scripts\activate
# On macOS/Linux:
source mushroom_env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## **Running the Application**

```bash
# Navigate to the Flask directory
cd Flask

# Start the web application
python app.py

# The application will be available at http://localhost:5000
```

## **Project Structure**
```
AI-Mushroom-Classification-Analysis-master/
├── Documentation...
├── Dataset/
│   ├── test/          # Test dataset
│   └── train/         # Training dataset
├── Flask/
│   ├── static/        # Static assets (JS)
│   ├── templates/     # HTML templates
│   ├── uploads/       # User uploaded images
│   └── app.py         # Main Flask application
├── IBM Files/         # Files related to IBM Cloud deployment
├── Training files/    # Training scripts and notebooks
├── README.md          # Project documentation
└── requirements.txt   # Project dependencies
```
## **Note**
--Install Flask and TensorFlow Separately 

## **Technologies Used**
- Python 3.10.6
- TensorFlow/Keras
- Flask
- HTML/CSS/JavaScript
- OpenCV
- NumPy/Pandas

## **Model Architecture**
The classification model is built using transfer learning with pre-trained neural networks. The trained model is saved as `Mushroom Classification Model.h5` in the root directory.

## **Dataset**
The dataset is organized in the Dataset folder with separate test and train directories. It consists of images of three main mushroom genera:
- Boletus
- Lactarius
- Russula


## **Future Improvements**
- Expand classification capabilities to include more mushroom species
- Implement mobile application for field identification
- Add detailed information about each mushroom species
- Integrate geographical data to enhance classification accuracy

## **Conclusion**
The mushroom classification project utilizes deep learning and transfer learning techniques to build an accurate and efficient classification system. By leveraging pre-trained models and a comprehensive mushroom dataset, we aim to contribute to the field of mushroom recognition and promote the understanding of mushroom species diversity in different regions.

