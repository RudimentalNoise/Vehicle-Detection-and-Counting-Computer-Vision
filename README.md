# Vehicle Detection and Counting in Photos and Videos

##The system:
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
- `src/main` - used for the training of the dataset

For the data used in the project refer to this link
https://drive.google.com/drive/folders/1XURZidYYk7WnojF2F7bnlGlHmcYG750I?usp=sharing

For the trained models did in this project
https://drive.google.com/drive/folders/1ZJqIdbocwiEd8-72kxsimNePbOKrNVYx?usp=sharing
