# Object Detection Web Application

## Description
This project is a web application that detects objects in images using deep learning techniques. It is designed to allow users to upload images and identify objects within them using a trained YOLO model.

## Technologies Used
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JAVASCRIPT
- **Deep Learning Model**: YOLO (You Only Look Once) for object detection
- 
## Features
- Object detection using deep learning.
- User-friendly interface for image upload and result visualization.
- Flask-based API for handling backend requests.

## Setup Instructions

### Step 1: Clone the repository
To get started, clone the repository to your local machine:
```bash
git clone https://github.com/zikoelj/ALX-Vision-AI.git
cd ALX-Vision-AI
```

### Step 2: Set up a virtual environment
It's recommended to create a virtual environment to manage dependencies:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Step 3: Install dependencies
Install the required packages using pip:
```bash
pip install -r requirements.txt
```

### Step 4: Run the application
After the dependencies are installed, you can start the Flask application:
```bash
flask run
```
You should see output indicating the application is running locally, e.g., Running on http://127.0.0.1:5000/. Open this link in your browser to access the web application.
### Usage 
1) Open your web browser and navigate to http://127.0.0.1:5000/.
2) Upload an image from your computer.
3) The web application will detect objects in the image and display the results.

### Challenges
- Improve the detection model to handle more complex images.

### Future Improvement
- Optimize the front-end experience with additional interactivity using React.
- train my YOLO model more to properly deal with new datasets

### Project Links
- GitHub Repository: https://github.com/zikoelj/ALX-Vision-AI
- Google Slides Presentation: https://docs.google.com/presentation/d/1TshQ6q_uZnNA3-eixhL8l529pOabdBYy/edit? 
                               usp=sharing&ouid=103318707892112694742&rtpof=true&sd=true

### Author
- Name: Zakariaa El Jabiry
- GitHub: zikoelj
- LinkedIn: https://www.linkedin.com/in/zakariaa-el-jabiry-b1a834270/
