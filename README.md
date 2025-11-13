# ktai-assignment-3 
Henry Koers, Ton Hellings, Jurgen de Vries
## File list
- train.html
- live-prediction.html
- test/train.ipynb
- test/live-prediction.ipynb
- report.pdf
- requirements.txt
- readme.md

## Experiments
- train.ipynb contains all of our experiments.
Our used data is available in the github repository and contains the American Sign language dataset from https://public.roboflow.com/object-detection/american-sign-language-letters/1.

## Live prediction application
- live-prediction.ipynb contains our application for live prediction on webcam and recording letters, including an algorithm to refine word prediction

## Data
The data is not included in the zip folder, as the zip would exceed the limit of 25MB. It is available on https://github.com/jurgendevries-ou-student/ktai-assignment-3, just like all other files including most of the ones mentioned here.
To run the notebooks, please download the data/ folder and position it in the same folder as the test/ folder.

## Versions of Python packages
Since Mediapipe requires numpy <= 2.0.0 specific versions of other packages are needed, see requirements.txt
