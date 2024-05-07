# Neural Networks Final Project

Final project in which I classify audio clips using a CNN. 

## Setup
To clone repo: 
```bash
   git clone https://github.com/clarej6060/CSCI4366_finalproject.git
   cd CSCI4366_finalproject
   pip install -r requirements.txt
```
After doing this, please go to the following [link](https://www.kaggle.com/datasets/chrisfilo/urbansound8k) to download the dataset (this was too large to include on github). Please include it within the folder ```CSCI4366_finalproject``` on your machine.

The file ```final_project``` was used to train the model. The file ```final_project_model``` is the model which may be used to observe the model classification with any of the files in the urban sounds dataset. To change the model, edit the file path in the line ```test_sound_file = 'urbansounds/<desired_fold>/<filename>.wav' ```.

