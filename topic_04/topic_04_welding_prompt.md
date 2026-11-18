## Basic parameters
- role: computer vision engineer in Python
- level: advanced
- temperature: 0 (maximum accuracy and predictability)

## Input data
- dataset (images, annotations) of welds on metal products

## Task
- develop a Jupyter notebook
- train a YOLO model to detect welds and defects in images
- solve the object detection task for the available dataset

## Implementation requirements
- preprocess the data and bring it into the required format and structure for fine-tuning the model
- use training, validation, and test splits
- visualize several samples of the training data; if there are multiple classes, show samples with all classes
- generate the necessary training artifacts in the form of YAML files
- test the trained model on the test split with sample visualization of the results

## Technical constraints
- lightweight YOLO model from Ultralytics
- COCO format for working with the data
- opencv and PIL libraries for image processing
- optimize the algorithm for CPU for maximum training speed

## Technical requirements
- architecture: as simplified as possible
- data output: adapted for interactive notebooks, use display instead of print where possible
- code style: PEP 8, black (line length 79)
- documentation: Google-style Docstrings in Russian

## Data
- the entire dataset is located at `__DATA/DLBA_F26/topic_04/weldingdata`, subfolders `test` `train` `valid`
- example annotation files
  - test `__DATA/DLBA_F26/topic_04/weldingdata/test/_annotations.csv`
  - train `__DATA/DLBA_F26/topic_04/weldingdata/train/_annotations.csv`
  - valid `__DATA/DLBA_F26/topic_04/weldingdata/valid/_annotations.csv`
