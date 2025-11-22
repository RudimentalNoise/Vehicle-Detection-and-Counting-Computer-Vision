# Vehicle Detection and Counting in Photos and Videos

The system:
- Detects vehicles in each frame using YOLOv8.
- Masks out irrelevant regions of the scene with binary masks.
- Tracks objects across frames with the SORT algorithm.
- Counts vehicles when they cross a virtual line.
- Maintains separate counters for each vehicle class (car, motorbike, truck).

## Project Structure
- `src/detection with images.py` – run inference on images.
- `src/detection with video.py` – detection on videos.
- `src/detection and tracking with videos(total counter).py` – detection + tracking + total vehicle counter detected.
- `src/detection and tracking with videos 2.0(counter for each vehicle).py` – detection + tracking + total vehicle counter detected for each category of vehicle.

for the data used in the project and
