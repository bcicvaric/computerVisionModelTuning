# computerVisionModelTuning

## Into
Example of fine tuning YOLOv8 object detection model on custom dataset from Roboflow.

## Input
Input is downloaded from Roboflow as part of the code. For this you'll need to have a Roboflow account and retreive a key to download the dataset.

## Code
All code is in the fine_tune_model.ipnyb. Includes downloading data from Roboflow and fine tuning the model.
In order to reproduce, except installing libraries, it's also needed to edit data.yaml file (comment how to edit it included in the script).

## Output
Output are the weights for the new model in runs/detect/train32/weights/best.pt.
If you rerun the code, nnew weights will be created, folder will be part pf the output of the training cell.
