
# Intelligent Camera Decision-Making

This project demonstrates intelligent camera decision-making using object detection and tracking. It utilizes a pre-trained TensorFlow model for object detection and the SORT (Simple Online and Realtime Tracking) algorithm for object tracking.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/repository.git
   ```

2. Install the required packages:

   ```bash
   pip install tensorflow opencv-python
   ```



## Usage

1. Load the pre-trained TensorFlow model:

   ```python
   import tensorflow as tf

   model = tf.saved_model.load("/path/to/saved_model")
   ```

2. Create a SORT tracker:

   ```python
   from sort import Sort

   tracker = Sort()
   ```

3. Upload the video file to Colab and extract it.

4. Replace `'your_video_filename.mp4'` with the actual file name.

5. Run the script:

   ```bash
   python camera_decision_making.py
   ```

6. Press 'q' to exit the application.

## Dependencies

- TensorFlow
- OpenCV

## Contributors

- [Kesahv Kumar](https://github.com/keshav-kumar-01)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Note: Update the URLs, file paths, and contributor information according to your project.
