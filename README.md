# TypePlant Classification Project
This project utilizes Transfer Learning with a ResNet18 model to classify plant types using the TypePlantDataset. The model leverages pre-trained ImageNet weights to improve accuracy and reduce training time, with fine-tuning performed on the last layers.

## Instructions

### 1. Clone the Repository
Clone the repository to your local machine or save it in your Google Drive:

```bash
git clone https://github.com/p-restani/TypePlantDtaset.git

```

### 2. Download the Dataset
Download the [TypePlantDataset](https://www.kaggle.com/datasets/yudhaislamisulistya/plants-type-datasets) from the provided source. Once downloaded, ensure that the dataset path is correct in the notebook.

````bash
train_dir = '/path-to-your-datset/dataset_type_of_plants/Train_Set_Folder'
val_dir = '/path-to-your-datset/data/dataset_type_of_plants/Validation_Set_Folder'
test_dir = '/path-to-your-datset/data/dataset_type_of_plants/Test_Set_Folder'
````

### 3. Using Google Colab
If you are using Google Colab, follow these steps:

Upload the dataset to your Google Drive.
Connect your Google Drive to Colab by running the following command:

````bash
from google.colab import drive
drive.mount('/content/drive')

````

### 4. Run the Notebook

Once the dataset paths are updated, you can run the entire notebook to train the model:

1. Open the notebook file `TypePlantDataset.ipynb` in Google Colab or Jupyter Notebook.
2. Run each cell sequentially by clicking on the "Run" button or pressing `Shift + Enter`.
3. Make sure the dataset paths are correctly updated as shown in the instructions.
