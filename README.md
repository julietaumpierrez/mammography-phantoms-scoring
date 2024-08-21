# mammography-phantoms-scoring
Repository containing code to do an automatic scoring of structures extracted from mammography phantoms.

This repo is heavily based on the following repository:
https://github.com/hrsht-13/Breast-Cancer-Detection which has the needed code to generate the file:

'training_0/final_training.weights.h5' 

## How to run this repo:
In order to use this repo clone it and run

``pip install -r requirements.txt
``

Then download and unzip the phantoms dataset that you can obtain from [this link](https://drive.google.com/file/d/18Hu_Fg1tY4Cn7pmDTOVNh4Pc1JUZS6A-/view?usp=share_link). The contents have to be placed into the content folder.

Then you can use the evaluation notebook to make the evaluation or the training notebook to train the same or new models.

Every result is reported in [this Comet](https://www.comet.com/julieta-umpierrez/fantomas-mamarios/view/MV7RIrK9eCj9F6Igw9QPxYZZs/panels)

Please do not hesitate to open an issue if you have any questions or directly contact me at: jumpierrez@fing.edu.uy
