# Multiple_Object_Annotation_Tool
It is an annotation tool that will store 17 keypoints and coordinates of the bounding boxes of the object taken into account and will store the same for multiple objects in the json format.
## Pre-Requisites
1. Python      2. openCV

## Usage

Create a folder named "data" and put the image to annotate under ./data/ and the annotations will be stored in "json" format under the file name "manage.json"

## Instructions
1. Run the script "script.py"
2. Draw the rectangular bounding box for each object in the image.
3. Press "c" to go to next step and mark a keypoint. Similarly do it for all 17 other keypoints.
4. Press "n" to go to the next frame/image.
5. (Important)After annotation of last object first press "n" then "q" to exit, otherwise it will not store the values of last object.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
This project is an modified version of the repo https://github.com/ZhaoJ9014/Multi-Human-Parsing/tree/master/Annotation_Tools/Multi-Human_Pose
Modifications:
1. Now, it will store the results in "json" format.
2. It will store 17 keypoints now.


