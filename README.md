## Column Damage Classification 

This code follows the pipeline provided by the TA;
1) Damage classification into 3 class with Inceptionv3
2) The YOLO model detects features such as exposed rebar, spalling, and cracks.
3) Crack damage classification  with ViT model



## Project Structure

├── Final Column_Inference Code.ipynb 
├── Final Column_Training Code.ipynb 
├── requirements.txt # pip-based dependencies
├── environment.yml # Conda-based environment setup
├── README.md 



### Model weight
Model weight can be found in Google Drive, (<https://drive.google.com/drive/u/0/folders/1ZrUYZawFrG7BG1qM2iV77smOfTfjCMpE>) 
1) Damage classification: `best_model_column.pth`
2) Feature Classification: `column_detector_best.pt`
3) Crack Classification: vit_model/`best_vit_model.pth`  


## How to Run the Project (GoogleColabRecommended)

1. Download `Final Column_Inference Code.ipynb`, and upload it in Google Colab
2. Run all cells from top to bottom, `Final.ipynb` is generated and the file uploaded to Kaggle
3. To see the training code, check `Final Column_Inference Code.ipynb`
