# Project README - NLP Ticket Classification

## Overview

This Colab notebook `MDSv4_ML_P2_NLP.ipynb` is part of the "NLP Ticket Classification" project and is designed to perform automatic classification of support tickets using Natural Language Processing (NLP) techniques. 

The project utilizes a dataset stored in the `_data` folder, specifically the `complaints.json` file.

## Run the Colab notebook using Google Colaboratory

1. Sign in your Google account
2. From Google Workspace Marketplace install **Colaboratory** extension
3. Copy [complaints.json](https://github.com/marquinamaria/UCB_MDSv4_ML/blob/main/Sub%20Proyecto%202/P2_Proyecto%20-%20NLP%20Clasificacion%20Automatica%20de%20Tickets/_data/complaints.json) in your a Google Drive folder
4. Open Colab notebook [MDSv4_ML_P2_NLP.ipynb](https://github.com/marquinamaria/UCB_MDSv4_ML/blob/bfc1bfe80d87f6002c29fd38b31aa5c41e4715d5/Sub%20Proyecto%202/P2_Proyecto%20-%20NLP%20Clasificacion%20Automatica%20de%20Tickets/MDSv4_ML_P2_NLP.ipynb) from GitHub 
	- In Colab go to File > Open notebook > GitHub
	- Enter a GitHub URL or search by organization or user: [UCB_MDSv4_ML.git](https://github.com/marquinamaria/UCB_MDSv4_ML.git)
	- Select path `Sub Proyecto 2/P2_Proyecto - NLP Clasificacion Automatica de Tickets/MDSv4_ML_P2_NLP.ipynb`
5. Update this line of code with the actual path to file `complaints.json`, for example:
    ```python
	data_file = "/content/drive/My Drive/Colab Notebooks/P2_Proyecto - NLP Clasificacion Automatica de Tickets/_data/complaints.json"
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
6. Open Visual Studio code and open the folder: File > Open Folder and select `PATH_TO_LOCAL_UCB_MDSv4_ML` where `PATH_TO_LOCAL_UCB_MDSv4_ML` is the path where your cloned repository is.
7. Comment the following lines
   ```python
    #from google.colab import drive
	#drive.mount('/content/drive')
   ```	
8. Update this line of code with the actual path to file `complaints.json` where `PATH_TO_LOCAL_UCB_MDSv4_ML
   ```python
	data_file = "PATH_TO_LOCAL_UCB_MDSv4_ML\Sub Proyecto 2\P2_Proyecto - NLP Clasificacion Automatica de Tickets\_data\complaints.json"
	```
9. Run the notebook `PATH_TO_LOCAL_UCB_MDSv4_ML\Sub Proyecto 2\P2_Proyecto - NLP Clasificacion Automatica de Tickets\MDSv4_ML_P2_NLP.ipynb`

