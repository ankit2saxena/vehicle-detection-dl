# Vehicle Detection
This project uses multiple image data sources of vehicles that are parked in a parking slot.
The goal of the project is to automate the detection of vehicle in a parking slot given an image.

#### Required Software:
    -> Anaconda 3.6.5 or higher
    -> git
    -> Visual Studio (for C++ tools)
    -> PyCharm
    
#### 1. Create a virtual environment for Python
    python -m venv vehicle-detection-dl-virtenv
    
#### 2. Activate virtual environment for Python
    vehicle-detection-dl-virtenv\Scripts\activate.bat
    
#### 3. Upgrade pip
    python -m pip install --upgrade pip
    
#### 4. Install required libraries
    pip install -r vehicle-detection-dl/requirements.txt
    
#### 5. Create a Jupyter notebook specific to vehicle-detection-dl-virtenv
    ipython kernel install --user --name=vehicle-detection-dl-virtenv
    
#### 6. Get the repository
    git clone https://github.com/ankit2saxena/vehicle-detection-dl.git
    
#### 7. Deactivate virtual environment
    deactivate
    
#### 8. Start Jupyter Notebook (Anaconda)
    jupyter notebook
    
#### 9. Generate Model Training data
    run notebooks/01_download_data.ipynb
    
#### 10. Generate ML Model
    run notebooks/02_build_model.ipynb