# Project README - NLP Attention is all you need

## Overview

This Colab notebook `MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb` is part of the "NLP Text Translation" project and is designed to perform spanish to english translation. 

The project uses a dataset stored in the `_data` folder, specifically the `spa.txt` file.

## Run the Colab notebook using Google Colaboratory

1. Sign in your Google account
2. From Google Workspace Marketplace install **Colaboratory** extension
3. Copy [spa.txt](https://github.com/marquinamaria/UCB_MDSv4_ML/blob/main/Sub%20Proyecto%202/P2_Proyecto%20-%20NLP%20Clasificacion%20Automatica%20de%20Tickets/_data/spa.txt) in your a Google Drive folder
4. Open Colab notebook [MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb](https://github.com/marquinamaria/UCB_MDSv4_ML/blob/bfc1bfe80d87f6002c29fd38b31aa5c41e4715d5/Sub%20Proyecto%202/P2_Proyecto%20-%20NLP%20Clasificacion%20Automatica%20de%20Tickets/MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb) from GitHub 
	- In Colab go to File > Open notebook > GitHub
	- Enter a GitHub URL or search by organization or user: [UCB_MDSv4_ML.git](https://github.com/marquinamaria/UCB_MDSv4_ML.git)
	- Select path `Sub Proyecto 2/P2_Proyecto - NLP Clasificacion Automatica de Tickets/MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb`
5. Update this line of code with the actual path to file `spa.txt`, for example:
    ```python
	data_file = "/content/drive/My Drive/Colab Notebooks/Proyecto_Final - NLP Attention is all you need/_data/spa.txt"
	```
6. In Colab notebook Runtime > Run 

## Run notebook in your local env

1. Install Visual Studio Code
2. Install Python 3.11.2 or later 
3. Read and verify this requirements to run jupyter notebooks are satisfied [jupyter-notebook](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
4. Clone this repository [UCB_MDSv4_ML.git](https://github.com/marquinamaria/UCB_MDSv4_ML.git)
   ```bash
	git clone https://github.com/marquinamaria/UCB_MDSv4_ML.git
	```
5. Pull latest version of the code
   ```bash
	git pull
	```
6. Open Visual Studio code and open the folder: File > Open Folder and select `${PATH_TO_LOCAL_UCB_MDSv4_ML}`, replace `${PATH_TO_LOCAL_UCB_MDSv4_ML}` with the path where your cloned repository is.
7. In the file `MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb` make the following changes:
   ```python
    #from google.colab import drive
	#drive.mount('/content/drive')
   ```	
8. In the file `MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb` update this line of code with the actual path to file `spa.txt`
   ```python
	data_file = "${PATH_TO_LOCAL_UCB_MDSv4_ML}\Proyecto Final\Proyecto_Final - NLP Attention is all you need\_data\spa.txt"
	```
9. Run the notebook `${PATH_TO_LOCAL_UCB_MDSv4_ML}\Proyecto Final\Proyecto_Final - NLP Attention is all you need\MDSv4_ML_PFinal_NLP_Attention_is_all_you_need.ipynb`

