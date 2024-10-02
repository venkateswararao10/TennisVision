
# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints.

## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)

## dataset 
drivelink:https://drive.google.com/drive/folders/1Nc_aGyonVLe_DWhZAYgXJr6ZMEfpxOrj?usp=sharing
download folder in drive link add folder in training/tennis-ball-detection-6
## Approach:
1. Player & Ball Detection (YOLO): Detect players and tennis balls in video frames.

2. Court Keypoints (CNNs): Extract court lines and points for context.

3. Speed Calculation:

  • Player Speed: Measure player movement across frames using court dimensions.

  • Ball Shot Speed: Calculate ball velocity based on movement between frames.

4. Shot Counting: Detect each ball-player interaction as a shot.

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb


## Key Tools:
• YOLO: For detecting players and the tennis ball.

• CNNs: For extracting court keypoints.

• OpenCV: Video processing.

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
