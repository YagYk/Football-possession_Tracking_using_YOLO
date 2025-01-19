# Football Possession Tracking using YOLO

This project implements a football possession tracking system using YOLO object detection. It can detect and track players, the ball, and analyze possession statistics in football match videos.

## Features

- Player detection and tracking using YOLOv8
- Ball tracking and possession analysis
- Team color assignment and player classification
- Speed and distance estimation for players
- Camera movement compensation
- Bird's eye level transformation

## Project Structure

├── camera_movement_estimator/   # Camera motion tracking
├── models/                      # YOLO model weights
├── player_ball_assigner/        # Ball possession logic
├── speed_and_distance_estimator/# Player statistics
├── team_assigner/              # Team classification
├── trackers/                   # Core tracking logic
├── utils/                      # Helper functions
├── view_transformer/           # Perspective transformation
├── main.py                     # Main execution script
└── yolo_inference.py          # YOLO inference script

## Installation

1. Clone the repository :
   
2. Install dependencies :
   
3. Download the YOLO model weights and place them in the `models/` directory.

## Usage

1. Place your input video in the `input_videos/` directory

2. Run the inference:
   
3. For full analysis with tracking :
   
## Requirements

- Python 3.8+
- PyTorch
- Ultralytics YOLO
- OpenCV
- NumPy
- Supervision
- scikit-learn

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YOLO v8 by Ultralytics
- ByteTrack for object tracking
