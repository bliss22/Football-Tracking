# Football-Tracking
⚽ Player Re-Identification in a Single Feed (YOLOv5 + Deep SORT)
This project detects and tracks football players throughout a video using a custom YOLOv5 model and Deep SORT. Each player is assigned a unique ID in the first few seconds, which persists even if the player temporarily leaves and re-enters the frame (e.g., near goal events).

📦 Features
Object detection using YOLOv5

Real-time tracking and re-identification using Deep SORT

Consistent player IDs across the video

Bounding boxes that follow players accurately — no shrinking, no drifting

Output is saved as a video with tracking visualized

🛠 Requirements
✅ Python Version

Python 3.8 - 3.10
📚 Dependencies
Install the following via pip:


pip install -r requirements.txt
