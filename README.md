# Neural Networks Final Project

Final project in which I classify audio clips using a CNN. 

## Setup
To clone repo: 
```bash
   git clone https://github.com/clarej6060/CSCI4366_finalproject.git
   cd CSCI4366_finalproject
   pip install -r requirements.txt
```
After doing this, unzip the urbansounds.zip file and retain the file structure. 

The file ```final_project``` was used to train the model. The file ```final_project_model``` is the model which may be used to observe the model classification with any of the files in the urban sounds dataset. To change the model, edit the file path in the line ```test_sound_file = 'urbansounds/<desired_fold>/<filename>.wav' ```.
