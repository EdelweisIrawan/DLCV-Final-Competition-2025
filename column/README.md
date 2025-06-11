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
### 1. Open Google Colab
### 2. Clone the GitHub repository
Open a new notebook and run:

```bash
!git clone https://github.com/EdelweisIrawan/DLCV-Final-Competition-2025.git
%cd DLCV-Final-Competition-2025
```
### 3. Open the inference notebook
- Still in Colab, go to: File > Open Notebook > Github tab
- Paste this GitHub link: https://github.com/EdelweisIrawan/DLCV-Final-Competition-2025
- Open the notebook: `Final_Column_Inference_Code.ipynb`

### 4. Run all cells
- Runtime > Run all
- The generated file will be: `final.csv`

