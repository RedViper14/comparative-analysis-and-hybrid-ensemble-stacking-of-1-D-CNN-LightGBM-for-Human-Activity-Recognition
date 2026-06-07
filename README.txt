Human Activity Recognition using 1-D CNN, LightGBM and fusion model (PAMAP2 Dataset)

------------------------------------------------------------------------

PROJECT STRUCTURE


1.  Dataset/ PAMAP2_Dataset/ Protocol/ subject101.dat subject102.dat …
    subject109.dat

2.  Python code-  1D-CNN/ fusion model/ LightGBM.py


------------------------------------------------------------------------

SOFTWARE REQUIREMENTS

-   Python (>= 3.8)
-   Recommended: Python 3.9 – 3.11

Required Libraries: numpy pandas scikit-learn tensorflow matplotlib

Install using: pip install numpy pandas scikit-learn tensorflow
matplotlib

------------------------------------------------------------------------

HOW TO RUN 

Step 1: Set Dataset Path

Open 1D-CNN/ fusion model / LightGBM.py and update:

base_path = “C:_Dataset”

Step 2: Run Program

python 1D-CNN/ fusion model / LightGBM.py

Step 3: Execution

The program will automatically: - Load dataset - Preprocess data -
Create windows - Train CNN / LightGBM/ fusion model - Evaluate results - Generate graphs



------------------------------------------------------------------------

DATASET INFO

PAMAP2 Dataset

Activities: - Lying - Sitting - Standing - Walking - Running - Cycling -
Ascending stairs - Descending stairs

Sensors: - Accelerometer - Gyroscope - Magnetometer - Temperature -
Heart rate


------------------------------------------------------------------------

TROUBLESHOOTING

1.  Check dataset path
2.  Install libraries
3.  Reduce batch size if memory issue
4.  Use GPU for faster training


------------------------------------------------------------------------

AUTHOR

Hari sunmukeswar Baskaran
@00818505
MSc Robotics and Automation
