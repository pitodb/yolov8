# Real-Time Object Detection with YOLOv8

This project aims to provide real-time object detection capabilities using the YOLOv8 model. YOLOv8 is renowned for its speed and accuracy in object detection tasks.

## Dependencies: 

This project utilizes the Poetry package manager for managing dependencies. Dependencies are listed in the `pyproject.toml` file.

## Installation Instructions (using Poetry):

1. Ensure Python 3.x is installed on your system.

2. Install Poetry using pip:

`pip install poetry`


3. Navigate to the project directory in your terminal.

4. Run the following command to install dependencies:

`poetry install`


## Usage Instructions:

1. Activate the Poetry environment:

`poetry shell`


2. Run the provided Python script to initiate real-time object detection using the computer's camera.

## Additional Notes:

- The `source` parameter in the `predict` function specifies the camera source. Modify it accordingly if using a different camera.
- The `show` parameter controls whether to display the real-time detection results.
- For more advanced usage and customization, refer to the Ultralytics documentation and the YOLOv8 model documentation.

## License:

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

## Credits:

- YOLOv8 model implementation: Ultralytics
- YOLOv8 model weights: [Official Ultralytics repository](https://github.com/ultralytics/yolov5)

