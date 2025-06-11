## Beam Damage Classification 

This code follows the pipeline provided by the TA.
1) Damage classification into 3 classes with DenseNet201
2) The YOLO model detects features
3) Crack damage classification  with the ViT model
4) Algorithms to classify the damage detected



## Project Structure

├── Final_Crack_Classification_Inference_Detection_Final_Compilation_Code.ipynb 
├── Final_Damage_Classification_Code.ipynb 
├── requirements.txt # pip-based dependencies
├── environment.yml # Conda-based environment setup
├── README.md 
├── beam11.csv #Final result


### Model weights
Model weight can be found in Google Drive provided by TA (<https://drive.google.com/drive/folders/1XsaZ4mEmq3cFA5pEmkChizpaygxkcpeA?usp=drive_link>) 
1) Damage Classification: `model.pth`
2) Crack Classification: `model_crack.pth`
3) Damage Detection (YOLOv11): `best.pt`
4) Training, Testing, and Validation Dataset: `beam_3class.yaml`


## How to Run the Project 
### 1. Open Visual Studio Code
### 2. Open and run the Final_Crack_Classification_Inference_Detection_Final_Compilation_Code.ipynb 
### 3. Insert all the model weights and dataset into the code
### 4. Obtain the result

